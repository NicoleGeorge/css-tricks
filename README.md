# css-tricks

Creative Code snippets: Excercises in cool CSS tricks

1. Parallax Header using Multiple Images

- line that makes parallax possible, background-attachment: fixed;

2. Vieport Width

- width and height properties: vw + vh
- changed the header from 800px => 80vh
- this takes up 80% of the viewport height

3. Font Shorthand

- cleaner code, more effective and shorter
- order for font shorhand: font-style font-variant font-weight font-size/line-height font-family

4. Text Stroke

- creates an outline of the text, and fill color
- CSS properties applied: -webkit-text-fill-stroke + -webkit-text-stroke
- fallback propert = text-shadow
- this is applied if there are browser compatibility issues

5. Drop Shadow

- a CSS function that applies a drop shadow effect to an image element
- works with transparent images the best
- box-shadow will drop the shadow around the entire image frame

6. Filter Blur

- filter property and blur effect applied to the plant images
- value inside the function determines the amount of distortion

7. Character unit (ch)

- represents the width of the ch '0' in current font
- adjusts the width of text based on character units

8. First Letter
- inspired by print elements (drop-case)
- using pseudo-classes to isolate :first-letter of the word 