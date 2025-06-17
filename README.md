# chord-detector
This project trains models to detect the musical chords from audio input.

Training/testing data is prepared by averaging chroma data over time paired with labeled chord data.

## How to Set Up
1. Download the McGill Billboard dataset from:
   https://www.kaggle.com/datasets/jacobvs/mcgill-billboard

   Contains chroma data at each frame for random top songs from the '50s to '90s

2. Unzip it into the `data/mcgill-billboard/` folder inside this project directory:

    project_root/

    ├── data/

    │ └── mcgill-billboard/

3. Dependencies
    In the terminal, run:
    pip install pandas numpy tqdm sklearn matplotlib librosa

4. Open and run the `chord_detector.ipynb` notebook