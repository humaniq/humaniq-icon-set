# Humaniq Icons set

### List of icons
[see here](https://htmlpreview.github.io/?https://raw.githubusercontent.com/humaniq/humaniq-icon-set/master/demo.html?token=ACAT5ZCGO4JMW6P7E6B3MVTBUCOJE)

### Demands
- icons must be in a frame 512x512 px
- plain svg
- only one path (remove groups, multipath etc...)
- Remove all fills and colors.
- Remove all FAT line attributes.
- Join all contours to a single outline.

### Preparing images in Inkscape
  - Select all
  - Document Properties -> Resize page to drawing or selection
  - Object -> Ungroup
  - (Path -> Stroke to Path – use only if necessary, fixes various issues but makes file a lot larger)
  - Path -> Union
  - Path -> Combine
  - File -> Clean up document (or Vacuum Defs)
  - Set the document to use PX units
  - Save as -> Plain SVG 

### Use fontello to transform svg images to font
    - https://fontello.com/

### Resources
- https://github.com/fontello/fontello/wiki/How-to-use-custom-images#importing-svg-images