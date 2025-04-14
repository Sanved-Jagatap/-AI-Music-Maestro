# -AI-Music-Maestro
AI Music Maestro is a LSTM-Based MIDI Composition Generator which  Generates original music sequences by predicting pitch, step, and duration using an LSTM neural  network trained on MIDI files.
Interactive Gradio interface lets users control generation parameters like temperature and number ofnotes, enabling real-time creative exploration.

Features:
LSTM-Based Composition: Uses a recurrent neural network to learn musical patterns and generate new melodies.
Interactive Gradio UI: Allows users to customize the number of notes and temperature to shape the output style.
MIDI Support: Works with standard MIDI files using PrettyMIDI and music21 for processing and playback.

How It Works
Preprocessing: MIDI files are converted into sequences of pitches, steps, and durations.
Training: An LSTM network learns temporal dependencies in the musical structure.
Generation: The model outputs a new music sequence, which is saved as a MIDI file and playable through the interface.

Note:
To interact with the music generation model, you need to run the MusApp.ipynb(Gradio interface)
