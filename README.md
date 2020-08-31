# Dynamic_Meteor_Spectra
Data to reproduce the spectra of small-mass meteors from optical data.
The folders are named for each meteor with date and UT time, in the format met_spectra_MMDDYYYY_hhmmss. The files are named similarly, with a lowercase letter tag from a-z denoting the chronological frame of the data. Each frame is from an optical telescope at 22 fps, "a" being the first instance the meteor was seen. A folder for the calibration to a known F0 star is included, with a file for the star's spectrum. Each file contains a list of brightness counts of the meteor and spectrum. The wavelength calculation can be determined by starting at index 1 at the brightest count value (the image of the meteor), and the wavelength (nm) increases "upward" from the image of the meteor using the following equation.

wavelength = 7.3408*index - 73.3781 (nanometers)


