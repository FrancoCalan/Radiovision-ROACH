# Radiovision-ROACH

Scripts and models for the implementation of Radiovision-ROACH

## Requirements
- [calandigital](https://github.com/francocalan/calandigital)

## Installation instructions

### adc16
This is the ruby package written by David MacMahon to initialize the ADC16x250-8. ADC initialization is a necessary step every time Radiovision system is run.

1. Install ruby: `sudo apt install ruby ruby-dev`
2. Install gem (ruby package manager): `sudo gem install --source http://w.astro.berkeley.edu/~davidm/gems adc16`
3. Install plotting packages: 
    - `sudo apt install pgplot5`
    - `sudo gem install pgplot`
    - `sudo gem install --source http://astro.berkeley.edu/~davidm/gems pgplotter`