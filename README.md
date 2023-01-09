## ETracker

##### Functionality:

ETracker uses exercise tracker, meal planning, goal setting, and user personalization to create a web-app that allows you to reach your goals. ETracker makes use of wearable integration which allows the user to connect their fitness watches and send their activity data to ETracker [website in progress]



```bash
bundle exec jekyll serve -H 0.0.0.0 -P 4001 # -H and -P are optional
```

4. Customizing style (CSS).  This project uses `/assets/css/style.scss` as the location to customize your CSS. To avoid warnings in VSCode make sure you install `SCSS IntelliSense` plugin.  To understand default style, make sure you ***Preview Site*** and refer to build generated `_site/assets/css/style.css` (this is worth 1000 lectures).  For the reunion site `gallery.md` uses custom style from `assets/css/style.css` to support 3 images per row.  Observe file and position of import and custom CSS, order is important as clarified in Midnight Theme readme. ...

```css
---
---

@import "{{ site.theme }}";

/* "row style" is flexible size and aligns pictures in center */
.row {
    align-items: center;
    display: flex;
  }
  
  /* "column style" is one-third of the width with padding */
  .column {
    flex: 33.33%;
    padding: 5px;
  }
```

