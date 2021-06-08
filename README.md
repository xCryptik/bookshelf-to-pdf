# Print a book from Bookshelf to PDF

This simulates click in the next page button and takes screenshot
of current page in the opened book.

## Usage

```bash
python install -r requirements.txt
python bookshelf-to-pdf.py top_left right_bottom next_button total_page
# Ex: python bookshelf-to-pdf.py 153,78 892,990 941,537 785
```

## Finding Cursor Coordinates

To find the coordinates you will need to supply as inputs for the
script, you may use "position()" function of the pyautogui module.

```bash
python
>>> import pyautogui
>>> pyautogui.position() # while cursor is on desired location
```

### Extras

Use [OCRmyPDF](https://github.com/jbarlow83/OCRmyPDF) to adds an OCR text layer to scanned PDF files, allowing them to be searched or copy-pasted.
