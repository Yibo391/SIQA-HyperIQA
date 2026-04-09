# HyperIQA Model Training and Inference (SIQA-S)

This notebook trains a HyperIQA model on the SIQA-S dataset.

## 🛠 Prerequisites

* **Hardware:** An NVIDIA GPU is required. The code automatically sets the device to `cuda`.
* **Environment:** Jupyter Notebook or JupyterLab installed on the server.
* **Libraries:** The necessary packages are installed and contained in the code. However, if you want to run it on local, you may need to install more dependencies because the Colab version is already sealed and installed some basic libs.

## 📂 Required Directory Structure

For my colab directory tree. It looks like below. If you want to change the veriso

```text
/
└── content/
    ├── drive/
    │   └── MyDrive/
    │       └── TrainSet.zip          <-- (Optional if you extract manually, see Note 1)
    ├── TrainSet/                     <-- Directory containing training images
    │   └── train_SIQA-S.jsonl        <-- Training labels and metadata
    └── SIQA-test.jsonl               <-- Test set metadata for inference
