# link-hover-effect

```css
 a {
  color: #144D73;
  background:
    linear-gradient(
      to left,
      #144D73,
      #144D73
    ),
    linear-gradient(
      to left,
      transparent,
      transparent
    );
  background-size: 100% 1.5px, 0 1.5px;
  background-position: 0 calc(100% - 2px), 100% calc(100% - 2px); 
  background-repeat: no-repeat;
  transition: background-size 400ms, background-position 400ms;
}

a:hover {
  background-size: 0 1.5px, 100% 1.5px;
  background-position: 100% calc(100% - 2px), 0 calc(100% - 2px);
}

```
