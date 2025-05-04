# Image Quality Assessment and Enhancement using HyperIQA + DnCNN + Real-ESRGAN

This project predicts the image quality of an input image, enhances it using denoising and super-resolution, and compares quality before and after enhancement.

## Models Used

- **HyperIQA (ResNet-50)** – Image Quality Assessment
- **DnCNN** – Image Denoising
- **Real-ESRGAN** – Super Resolution Enhancement

## Setup Instructions

1. Clone the repository
2. Open the file `colab_notebook.ipynb` in Google Colab.

3. Upload the following pretrained model files to Google Drive or Colab:
- `HyperIQA-resnet50-koniq10k.pth`
- `RealESRGAN_x4plus.pth`
- `dncnn_15.pth`

4. Run all the cells step by step in the notebook.

5. At the end, you'll see a visual comparison and predicted quality scores.

## Sample Image

Put your test image in `sample_images/` or upload via Colab:
## Output

- `outputs/` contains the enhanced image.
- Side-by-side comparison shown with predicted scores.

## Result Example

| Original | Enhanced |
|----------|----------|
| Quality: 5.2/10 | Quality: 8.3/10 |

## License

MIT License
