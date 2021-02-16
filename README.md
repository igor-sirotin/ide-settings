## Content

My custom settings for IDEs:
- Qt Creator
- Visual Studio

Settings contain:
- code highlight colors
- code style setgins
- keyboard shortcuts

## QtCreator instructions:

There's actually a workaround, which I use (example for Windows users):

### Export

1. In Qt Creator go to Options → Text Editor → Fonts & Colors
1. Choose a Color scheme which fits your wishes the most and change the colors to the ones you want
1. Click "Copy..." and input the name for the copy
1. Open explorer and go to C:\Users\%USERNAME%\AppData\Roaming\QtProject\qtcreator\styles
1. There you will find a file "creator-dark_copy.xml", you can give it to your friends

### Import

This one's a bit tricky, because you can only import files with names "creator-dark_copy.xml", "creator-dark_copy_copy.xml" and so on.

1. Copy your color scheme to C:\Users\%USERNAME%\AppData\Roaming\QtProject\qtcreator\styles
1. Ensure that the name of the file is creator-dark_copy.xml
1. Restart QtCreator, go to Options → Text Editor → Fonts & Colors
1. Now you can find your scheme in the list with the name it was exported (not the name of the file)