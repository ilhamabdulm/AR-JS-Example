# Code Examples
https://github.com/stemkoski/AR-Examples

# Spike
## Show asset on marker
### [Good Marker](https://github.com/Carnaux/NFT-Marker-Creator/wiki/Creating-good-markers)
* **Visual Complexity**
  * the more the better
* **Resolution**
  * the more the better
  * \> 300 DPI = good stabilization
  * < 72 DPI = needs camera to stay still
* **Physical Marker**
  * Screen
    * Luminosity (the more the better)
  * Printed
    * Contrast to the background (the more the better)
    
### Basics:
* Hiro
* Barcode
  * [Barcode collection](https://github.com/nicolocarpignoli/artoolkit-barcode-markers-collection)
* Pattern
  * [.patt generator](https://ar-js-org.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)

## UI Events
This capability needs `A-Frame`, so `ThreeJS` is not an option yet

The easiest way is to render overlayed DOM on top of `a-scene`

## Device Limitation and Compatibility
It works on any phone with webgl and webrtc

* https://caniuse.com/webgl
* https://caniuse.com/stream

although it has known issue in chrome, so firefox is recommended

marker based is extremely more CPU efficient compared to image tracking

## Dynamic Asset (e.g. text)
Have ready entities, render handled on FE

## Image Tracking
`smooth`, `smoothCount` and `smoothTolerance`
