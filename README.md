# Humaniq Icons set

### List of icons
[see here](https://humaniq.github.io/humaniq-icon-set/demo.html)

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
    - icomoon.io

### Resources
- https://www.reactnative.guide/12-svg-icons-using-react-native-vector-icons/12.1-creating-custom-iconset.html