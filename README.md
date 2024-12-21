# MoodCanvas: A Multimodal Emotion Recognition System

MoodCanvas is an advanced emotion recognition system that integrates data from multiple modalities—audio, video, and text—to identify and analyze human emotions with high accuracy. By leveraging cutting-edge deep learning techniques such as Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), and Transformers, MoodCanvas provides a comprehensive understanding of emotional states. This project is designed to support applications in mental health monitoring, interactive virtual assistants, and other AI-driven emotional intelligence tools.

---

## Key Features

- **Multimodal Integration**: Combines data from audio, video, and text inputs for robust emotion detection.
- **Deep Learning-Based Architecture**:
  - **CNNs** for analyzing facial expressions in video frames.
  - **RNNs** for processing audio signals and extracting temporal patterns.
  - **Transformers** for interpreting textual sentiment and context.
- **Real-Time Analysis**: Processes input data in real-time for interactive applications.
- **Scalability**: Modular architecture allows easy integration with different datasets and deployment environments.

---

## Applications

- **Mental Health Monitoring**: Helps detect emotional distress, providing insights into mental well-being.
- **Interactive Virtual Assistants**: Enhances the emotional intelligence of virtual agents for more empathetic interactions.
- **Market Research**: Analyzes customer sentiment during focus groups or interviews.
- **Educational Tools**: Monitors student engagement and emotional responses in learning environments.

---

## Technology Stack

### Frameworks and Libraries
- **Python**: Core programming language.
- **PyTorch**: Deep learning framework for building and training models.
- **Transformers**: Library for natural language processing (NLP).
- **OpenCV**: Video processing and facial recognition.
- **Librosa**: Audio signal processing.
- **Streamlit**: Web-based interface for visualizing results.

### Data Sources
- **Video**: Facial expressions from video streams.
- **Audio**: Vocal cues and tones.
- **Text**: Sentiment and semantic analysis of textual input.

---

## System Architecture

1. **Data Preprocessing**:
   - Video: Frame extraction, face detection, and normalization.
   - Audio: Noise reduction, feature extraction (e.g., MFCCs).
   - Text: Tokenization, sentiment extraction, and embedding generation.

2. **Model Components**:
   - **CNN**: Extracts features from facial expressions.
   - **RNN**: Analyzes temporal dynamics in audio signals.
   - **Transformer**: Processes textual data for semantic understanding.

3. **Fusion Model**:
   - Combines outputs from the CNN, RNN, and Transformer using late fusion techniques.

4. **Output Layer**:
   - Predicts the emotional state (e.g., happy, sad, angry) based on the fused features.

---

## Installation

### Prerequisites
- Python 3.8 or above
- GPU (optional but recommended for faster processing)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/moodcanvas.git
   cd moodcanvas
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. **Provide Input**: Upload video, audio, or text data.
2. **Real-Time Analysis**: View detected emotions via the interactive Streamlit dashboard.
3. **Export Results**: Save analysis outputs for further study.

---

## Contributing

Contributions are welcome! If you have ideas for improving the project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Commit your changes and push to your branch.
4. Submit a pull request.

---

## Acknowledgments

- OpenAI for providing resources and inspiration.
- Developers and researchers contributing to open-source AI tools.

---

## Contact

For inquiries, suggestions, or collaboration opportunities, reach out to:
- **Email**: durbadalapadhan2004@gmail.com
- **GitHub**: [https://github.com/badal1221](https://github.com/badal1221)

We hope MoodCanvas inspires advancements in emotional intelligence systems!

