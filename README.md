# Alfred-workflow-search-for-pdfs
Search for PDFs (using Alfred 5.5 and later)

# Introduction

The workflow searches for PDF files in a folder within Alfred's default search scope. You select the folder and the workflow displays thumbnails of the PDF files from that folder in a grid. You can then view within Alfred's PDF View a selected PDF file and page through that file.

# Usage

Type the workflow keyword (the default is `fpf`—for "Find PDF"—but you can change it in the configuration). You will be prompted to choose a folder in which to search. Press <kbd><space></kbd> and start typing the name of the folder in which you wish to search. Press <kbd>⏎</kbd> when the relevant folder name is displayed (or select the relevant folder if more than one is displayed) and you will see a grid of thumbnails of the PDF files in that folder with the full name of and path to the selected thumbnail displayed at the bottom.

In that view you can do a number of things:
- Move through the thumbnails using the arrow keys.
- Search for thumbnails in the grid by typing in the box at the top of the window.
- Click on a thumbnail, or press <kbd>⏎</kbd> on a highlighted thumbnail, to view only that file in Alfred's PDF View. If you wish you can then press <kbd>esc</kbd> in PDF View to return to the grid view.
- Press <kbd>⌘</kbd><kbd>O</kbd> (“O” for “open”) on a highlighted thumbnail to open the PDF file in your default PDF viewer.
- Use commands common to both Grid View and PDF View (see below).
- Press <kbd>esc</kbd> to end the workflow.

# PDF View

PDF View displays a single selected PDF from the grid view when you press <kbd>⏎</kbd> or click on a thumbnail in the grid view.

In PDF View you can do the following:
- Press <kbd>fn</kbd><kbd>↓</kbd> and <kbd>fn</kbd><kbd>↑</kbd> to move through the PDF page by page.
- Press <kbd>esc</kbd> to take you back to grid view.
- Press <kbd>⏎</kbd> or <kbd>⌘</kbd><kbd>O</kbd> (“O” for “open”) to open the PDF file in your default PDF viewer.
- Use commands common to both Grid View and PDF View (see below).
- Press <kbd>⌘</kbd><kbd>esc</kbd> to end the workflow.

# Commands common to both Grid View and PDF View
- Press <kbd>⌘</kbd><kbd>0</kbd> (command zero) to toggle the size of the window.
- With a selected thumbnail in Grid View or in any event in PDF View hold down either <kbd>⌘</kbd> or <kbd>⌥</kbd> and press <kbd>⏎</kbd>—the former to allow you to action the selected file in Alfred and the latter to reveal the selected file in Finder.
