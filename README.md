Open iOS-Icon-Creator in Automator.
Select Run(Command-R)
Select a 1024x1024 image
Select the output folder (its contents will be deleted)
Give it a second to complete

The destination folder will contain the following scaled images:

Icon-1024.png
Icon-29.png
Icon-29@2x.png
Icon-29@3x.png
Icon-40.png
Icon-40@2x.png
Icon-40@3x.png
Icon-50.png
Icon-50@2x.png
Icon-512.png
Icon-57.png
Icon-57@2x.png
Icon-60.png
Icon-60@2x.png
Icon-60@3x.png
Icon-72.png
Icon-72@2x.png
Icon-76.png
Icon-76@2x.png
Icon-83_5@2x.png
iTunesArtwork
iTunesArtwork@2x

(these are all that you need as of iOS 9 and the release of iPad Pro)

Make sure to check the images. Depending on the fine details in your source image, the resulting images might be pixelated or colors may be incorrect.


If you want, you can convert the workflow into an application by: 
File > Convert To... Then save the duplication as an application.

Known Issues
 
Ordinary PNG files from Photoshop or Pixelmator seem to work fine.
However the image scaling action in automator cannot handle heavily compressed PNG images.
