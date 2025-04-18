🌿 Plant Disease Classification with GPU Support

This project uses deep learning to classify plant diseases using the [New Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset). It leverages a GPU-enabled setup with CUDA Toolkit 12.6 and PyTorch for efficient training.

---

## 🛠️ Setup Instructions

### 1. ✅ Install Python

- Install **Python 3.12.6** or any compatible version from [python.org](https://www.python.org/).

---

### 2. ✅ Clone the Repository

```bash
git clone https://github.com/your-username/project445.git
cd project445
```

---

### 3. 📁 Download the Dataset

Download the dataset from Kaggle:  
🔗 [New Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

Unzip and arrange the directory as follows:

```
project445/
├── train/
│   ├── img1.jpg
│   ├── ...
├── valid/
│   ├── img1.jpg
│   ├── ...
├── test/
│   ├── img1.jpg
│   ├── ...
├── code.ipynb
├── gpu_monitor/
├── hudai.py
```

---

### 4. 🧪 Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

---

### 5. 📦 Install VSCode Jupyter Extension

Install the Jupyter extension in VSCode:
- Go to Extensions → Search: **Jupyter** → Install

---

### 6. ⚙️ GPU Setup

#### Ensure you have an NVIDIA GPU:
- Check using `nvidia-smi`

#### Update GPU Driver:
- Open **NVIDIA GeForce Experience App**
- Check for and install the latest **Game Ready / Studio Driver**

---

### 7. ⚡ Install CUDA Toolkit 12.6

Download from NVIDIA's official website:  
🔗 [CUDA Toolkit 12.6](https://developer.nvidia.com/cuda-downloads)

---

### 8. 📚 Install Python Dependencies (except PyTorch)

```bash
pip install -r requirements.txt
```

<details>
<summary>Sample <code>requirements.txt</code></summary>

```
numpy
matplotlib
scikit-learn
pandas
opencv-python
jupyter
torchvision
```

</details>

---

### 9. 🔥 Install PyTorch with CUDA Support

Go to: [https://pytorch.org/](https://pytorch.org/)

- Select:
  - OS: Windows/Linux
  - Package: pip
  - Language: Python
  - Compute Platform: CUDA 12.6

Use the generated install command (example below):

```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
```

---

## 🚀 Running the Notebook

1. Open VSCode
2. Launch `code.ipynb`
3. Run all cells

---

## 📁 Directory Structure

```
project445/
├── train/
├── valid/
├── test/
├── code.ipynb
├── hudai.py
├── gpu_monitor/
└── README.md
```

---

## 📊 GPU Monitoring

You can monitor your GPU during training using:

```bash
watch -n 1 nvidia-smi
```

Or use Python-based solutions in `gpu_monitor/`.

---

## 📌 Notes

- Make sure virtual environment is activated before running the notebook.
- Dataset should be properly structured inside `train/`, `valid/`, and `test/`.

---

## Author

- Showrav solaiman hossain, Durjoy barua, Nafees mahmud, Shahriar ratul
- GitHub:
