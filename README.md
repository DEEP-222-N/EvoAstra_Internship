## Image Captioning Model

Here’s my deep learning project, where I built an image caption generator using a combination of CNNs and LSTM with attention—for real-time caption generation!

### Highlight Features

- **Feature Extractor**: Started with VGG16 and Pretrained RestNet 50 model for better memory efficiency in resource-limited environments.
- **Model Structure**: Includes caption preprocessing, LSTM-based generator, and attention mechanism for context-aware captions.
- **Dataset Used**: Trained and evaluated on the [Flickr8k dataset](https://www.kaggle.com/adityajn105/flickr8k), which includes 8,091 images each paired with 5 descriptive captions.
- **Interactive Demo**: Deployed as a Streamlit app, enabling easy, interactive caption generation.

   [Live Demo](https://evoastrainternship-img.streamlit.app/)

### Installation Steps

```bash
# Clone the project
git clone https://github.com/DEEP-222-N/EvoAstra_Internship.git
cd EvoAstra_Internship

# Install dependencies
pip install -r requirements.txt
