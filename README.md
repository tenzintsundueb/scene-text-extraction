# Scene Text Extraction From Natural Scene Image
This project focuses on building a custom Optical Character Recognition (OCR) model tailored for extracting text from natural scene images. Leveraging the detection capabilities of the EasyOCR framework, the primary goal is to improve the accuracy and efficiency of text recognition in varied real-world environments. The recognition component is based on a Convolutional Recurrent Neural Network (CRNN) pipeline, integrating CNN and LSTM architectures for robust sequence modeling.

## Dataset:
A subset of the MJSynth dataset was used for training and evaluation.<br>
Link: https://huggingface.co/datasets/priyank-m/MJSynth_text_recognition

## Model:
The file C_LSTM_best.hdf5 contains the trained model weights, which are utilized in the demo script scene-text-extraction to perform text extraction from images.


