## How to Run

This project is designed to run on **Google Colab** with GPU acceleration.

### Prerequisites

1. A Google account with Google Drive access
2. The dataset (`archive.zip`) uploaded to your Google Drive

### Steps

1. Open `Final_Project_DL.ipynb` in Google Colab
2. Set the runtime to **GPU** (Runtime → Change runtime type → T4 GPU)
3. Mount your Google Drive when prompted
4. Update the dataset path in the notebook to match where `archive.zip` is stored in your Drive
5. Run all cells in order (Runtime → Run all)

### Dependencies

All dependencies are installed automatically within the notebook:
- `torch`, `torchvision`
- `openai-clip`
- `pandas`, `numpy`, `matplotlib`, `tqdm`
- `Pillow`

### Testing / Inference

The notebook includes 20 predefined game-themed prompts at the end for testing the generator. Run the inference cells to generate images from text descriptions like `"epic fantasy battle scene with knights and dragons"`.
