# Audio Processing Code

This code is designed for processing audio files using the librosa library. It loads multiple audio files, extracts information such as audio data, shape, and sample rate, and displays the audio using IPython.

## Requirements

- Python 3.x
- Required libraries: pandas, numpy, matplotlib, seaborn, librosa, IPython etc

## SENTENCE:
"Learning is a complex and multifaceted process that involves acquiring knowledge, understanding concepts, developing skills, and altering behaviors through study, experience, or practice. It is a fundamental aspect of human growth and adaptation, occurring throughout a person's life and often influenced by various factors such as environment, motivation, and prior knowledge."

## Install the necessary libraries using:
pip install pandas numpy matplotlib seaborn librosa ipython

## Implemented in code the following steps:
1. Perform data pre-processing to normalize the audio in terms of duration, sampling rate, and noise reduction.
2. Sub-Step-1: Setup Folder and File Paths and Load the Audio Files into variables
   Sub-Step-2: Play 1-2 sample audios using appropriate library
   Sub-Step-3: Use Librosa library to extract Sampling Rate and other useful audio features, refer https://librosa.org/
   Sub-Step-4: Perform Fourier Transforms from Time-domain to Frequency Domain using Numpy discrete FFT function in Librosa
   Sub-Step-5: Plot the FFT of the various sounds
   Sub-Step-6: Plot the mean /avg difference of audio files across 1) Morning 2) Afternoon 3) Evening 4) Night

## Usage
- Clone the repository or download the code files.
- Set the file paths for your audio files:
- Run the code
- The code will display information about each audio file, including a snippet of the audio data and its shape.

## Additional Information
- The code uses the librosa library for audio processing.
- Audio files are loaded and their information is printed to the console.
- The IPython library is used to display audio files.
