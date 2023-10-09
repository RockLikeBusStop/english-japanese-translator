# english-japanese-translator

This is an English to Japanese translator using a sequence to sequence neural network. Once trained, it can translate simple English sentences.

### Prerequisites

Ensure you have Python 3.x installed along with the necessary libraries.

```bash
pip install -r requirements.txt
```

### Data Preparation

To load the training data and prepare it for training use:

```bash
python process_data.py
```

### Training

Once data preparation is complete, train the model using the following command:

```bash
python train.py
```

This will begin training the sequence-to-sequence neural network. The training parameters and settings can be adjusted in the `train.py` and `constants.py` file.

### Running the Translator

After training, you can use the trained model to translate English sentences to Japanese:

  ```bash
  python run.py
  ```

This will prompt you for an English sentence, and the program will provide its Japanese translation.
