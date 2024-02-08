# Voice Classification with MFCC Features

These are Google Colab scripts written for various music-related projects. This repo focuses on different aspects of music analysis such as classifying audio tracks as either containing voice or not using Mel-Frequency Cepstral Coefficients (MFCC) features to identify the presence of lyrics in music, or just decomposition of music, and identifying bpm etc. 

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/voice-classification.git
    cd voice-classification
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

For voice classification 
1. Music can be downloaded here:

   voiced https://www.jamendo.com/playlist/500608900/indie

   no-voice https://www.jamendo.com/playlist/500605606/cool-instrumentals
   
3. Ensure your audio tracks are stored in the 'music' directory. 
4. Run the main script:

    ```bash
    python voice_classification.py
    ```

5. View the results and confusion matrix in the console.

## Features

- Extracts MFCC features from audio tracks.
- Builds and trains a neural network for voice classification.
- Provides a confusion matrix for evaluation.

## Dataset

The code assumes you have a dataset of music tracks labeled as 'voice' or 'no_voice' stored in the 'music' directory.

## Results

The current model achieves an accuracy of approximately 60%. Further optimizations are required for higher accuracy.

## Troubleshooting

- If you encounter memory issues, consider reducing the size of the dataset or using a machine with more resources.

## License

This project is licensed under the [MIT License](LICENSE.md).

## Acknowledgments

- The code utilizes the `pydub` and `python_speech_features` libraries.
- Inspired by the task of voice classification in audio tracks.

