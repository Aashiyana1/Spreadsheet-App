# Google Sheets Clone:

> A spreadsheet editing app.

# Steps to run project:
`npm install`
`npm start`

## Features:

1. Editing cells.
2. Applying styles to cells.
   1. Bold.
   2. Italic.
   3. Underline.
   4. Alignment (left, center, right)
   5. Font Family.
   6. Font Size.
   7. Color.
   8. Background Color.
3. Creating and Editing multiple sheets.
4. Formula Evaluation.
   1. Dependent cell value change causes other cell which are dependent on this to update as well.
   2. Changing the cell contents of a cell directly removes the formula from the content cell directly.
   3. Formula Evaluation does not support unary operators. eg to do 10 _ (-20) write the formula as 10 _ (0 - 20) {unary '-' is not supported}
5. Conversion of sheets to json and reading from json.
6. Copying and Pasting of a Single Cell (including formula and styles if any).
>
