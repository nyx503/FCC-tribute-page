# FreeCodeCamp Tribute Page

My solution for FCC's [Responsive Web Design project](https://www.freecodecamp.org/learn/responsive-web-design/).

## My biggest issues were:
1. Getting the bottom grid track to be the same size as the top one. The solution was setting the `grid-template-rows` to `25% auto minmax(0, 1fr) auto 25%` instead of `25% auto auto auto 25%` so the original image size wouldn't make the content of the grid cell to overlap with the one below.
2. Centering the image horizontally within the grid area. This was due to giving the parent element a declaration that interfered with the image's placement.

## Future improvements
- Replace the placeholder tribute information.
- Disable the grid area with the image if the screen gets too small.
- Improve font and color palette.
