# Changelog
All notable changes to this project will be documented in
this file.

## [1.1.0] - 2020-08-16
- New Recurrent Neural Network module.
- New modal filter module.
- Added 4x oversampling to Chow Tape.
- Refactored delay lines to use Lagrange interpolation instead of sinc
  interpolation. This improves performance and removes dependency on
  libsamplerate.

## [1.0.0] - 2019-07-30
- Initial release for ChowDSP VCV Rack modules. Modules include
  tape model, phaser feedback, phaser modulation, and feedback
  delay network reverb.