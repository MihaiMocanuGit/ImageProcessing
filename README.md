# ImageProcessing
This app is an image processing application that can process plain ppm, pgm or pbm file formats.

## Abilities
* Brightness and contrast adjustment. 
* Gamma correction. 
* Image convolutions: 
  * Mean blur
  * Gaussian blur
  * Horizontal Sobel
  * Vertical Sobel
* Cropping.
* Basic drawing.

## Dependencies
* CMake
* Catch2v3 (for tests)
* AddressSanitizer (Debugging)
* C++20 (recommended)

## Notes
This was only tested on Linux, format of file paths might pose a problem in Windows.