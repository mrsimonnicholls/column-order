#Ordering columns in a two-column grid

Use the css property **order** to change the order of grid items within your grid container.

In this demo i have created two classes:

.first-item & .second-item
```
.first-item {
    order:1;
}

.second-item {
    order:2;
}
```

This allows you to force reordering, especially useful when using media queries.

eg. your mobile version can be a different order to the desktop version of your site.

