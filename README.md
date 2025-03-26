# Instrument Recognition
Classifies 5 instruments(Guitar, Piano, Violin, Flute, Drums) from 3-second WAV clips.

## Setup
1. Install: `pip install librosa numpy scikit-learn joblib`
2. Run `train.ipynb`.

## Data
- It is trained by very small dataset
- 20-30 WAVs per instrument (Guitar, Piano, Drums, Violin, Flute).
├── data/
│   ├── Guitar/       
│   ├── Piano/
│   ├── Drums/
│   ├── Violin/
│   ├── Flute/
│   └── tests/ # for adding more songs and test the model