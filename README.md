# CLIP Image-Text Matching (Custom Model)

This project demonstrates how to run image-text similarity using a custom-trained CLIP model.

## How to Use

1. Open `inference.ipynb` in Google Colab
2. Upload two test images (e.g., a dog and an airplane)
3. Provide corresponding text (e.g., "This is a dog", "This is an airplane")
4. Run all cells to see matching scores!

## Files

- `custom_clip.py`: Loads and runs the custom CLIP model
- `custom_tokenizer.py`: Custom tokenizer used in the project
- `bpe_simple_vocab_16e6.txt.gz`: Tokenizer vocabulary file
- `test_images/`: Example test images
- `inference.ipynb`: Interactive notebook for demo
- `inference.py`: Optional Python script version

## 🔗 Model Weights Download

Please manually download the pre-trained model file (approx. 150MB):

📦 [Click here to download the model file `clip-imp-pretrained_128_6_after_4.pt`](https://stanfordmedicine.app.box.com/s/dbebk0jr5651dj8x1cu6b6kqyuuvz3ml)

After downloading, place it inside the `model/` directory of this project.


📦 [点击下载模型文件 clip-imp-pretrained_128_6_after_4.pt](https://stanfordmedicine.app.box.com/s/dbebk0jr5651dj8x1cu6b6kqyuuvz3ml)

下载后将其放入项目的 `model/` 文件夹中。

