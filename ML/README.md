# What we do?

We started with a dataset containing three mood labels, preprocessed by removing stop-words, tokenizing text, embedding tokens into vectors, and labeling data. Our model architecture included an embedding layer, SpatialDropout1D to prevent overfitting, three LSTM layers to capture temporal dependencies, GlobalMaxPooling1D to reduce dimensionality, and dense layers with dropout for classification. Training was conducted up to 200 epochs, using callbacks for early stopping. Upon achieving desired performance, the model was deployed to TensorFlow JS, enabling seamless integration into a web application. The resulting SereLuna app effectively tracks and analyzes users' moods, offering valuable insights for mental health management.

## Result

![WhatsApp Image 2024-06-21 at 14 57 58_575c1c18](https://github.com/Zwar1/SereLunaApp/assets/121994660/46fb59f2-c7c5-4b4c-9828-cc06ee5b142b)

![WhatsApp Image 2024-06-21 at 14 57 59_d1ac2098](https://github.com/Zwar1/SereLunaApp/assets/121994660/ca341f66-b94c-4ead-a336-95c39885be6d)
