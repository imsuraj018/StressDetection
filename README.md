# Stress Detection Using CCTV 🎥🧠

This project detects stress levels from CCTV footage using a trained machine learning model in a Jupyter Notebook.

## Contents
- `Stress_Detection(CCTV).ipynb`: Jupyter notebook for running inference.
- `stress_model.h5`: Trained Keras model file.
- `requirements.txt`: List of required Python libraries.

## Setup

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Notebook:**
   - Here few changes are required that you have to put cctv camera credentials in proper format
   ```bash
   jupyter notebook "Stress_Detection(CCTV).ipynb"
   ```

4. **Load and Test the Model:**
   - Make sure the `stress_model.h5` is in the same directory.
   - Run the cells in the notebook to see the inference pipeline.
   - Sometimes .h5 not perform well so try to build on your own.

## Notes
- Uses `facenet-pytorch` for face detection.
- Developed for educational/demo purposes.

## Author
KATKAR SURAJ
