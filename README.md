# Audio Classification using MLPClassifier

This project focuses on classifying audio data using features like **MFCC**, **Chroma**, and **Mel Spectrogram**, extracted from audio signals. The classification is performed using a **Multi-Layer Perceptron (MLPClassifier)** from scikit-learn.

## 🔍 Features Used
- **MFCC (Mel-Frequency Cepstral Coefficients)**: Captures timbral texture of sound.
- **Chroma Features**: Represents the 12 different pitch classes (useful for music analysis).
- **Mel Spectrogram**: Represents frequency content on a perceptual scale.

These features are extracted using the `librosa` library.

## 🤖 Model
- **Classifier**: `MLPClassifier` from `sklearn.neural_network`
- **Architecture**:
  - Hidden layers: Tunable (e.g., `(100,)`, `(128, 64)`, etc.)
  - Activation: `'relu'` (default)
  - Solver: `'adam'` (adaptive moment estimation)
- **Input**: Concatenated audio features (MFCC, Chroma, Mel)

## 🛠️ Tech Stack
- Python
- scikit-learn
- librosa
- NumPy
- pandas


## 🧪 Workflow
1. Load and preprocess audio data
2. Extract MFCC, Chroma, and Mel features
3. Concatenate features into a single feature vector
4. Split dataset into training and test sets
5. Train `MLPClassifier` on the training data
6. Evaluate model performance

## 📈 Example Results
Accuracy, confusion matrix, and classification report will be provided after training and evaluation.

## 📚 References
Livingstone, S. R., & Russo, F. A. (2018). The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS): A dynamic, multimodal set of facial and vocal expressions in North American English. PloS one, 13(5), e0196391.

## 📬 Contact
For any queries, please contact [senitha02@gmail.com].
