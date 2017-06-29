# makeIcons
## Create resized icon assets for mobile devices from the command line

Based on prepare_icons.sh from https://github.com/coronalabs-samples/CoronaCannon

## Usage
- Install ImageMagick (https://www.imagemagick.org/script/download.php)
- Put original large version of icons in same folder as this script.
  - Original iOS icon file should be named *IOSIcon.png* (preferably at least 2048x2048).
  - Original Android icon file should be named *AndroidIcon.png* (preferably at least 512x512).
- run the script from the command line:
$ bash makeIcons.sh
