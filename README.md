# 🎨 Neural Style Transfer using VGG19

> Apply artistic styles to images using deep learning with VGG19 and transfer learning.

<p align="center">
  <img src="https://github.com/abhijitjadhav1998/Neural_Style_transfer_using_VGG19/blob/master/assets/stylized-image.png" alt="Stylized Image Output" width="600"/>
</p>

---

## 📌 Table of Contents

- [About](#about)
- [Getting Started](#getting-started)
  - [Run on Google Colab (Recommended)](#️-run-on-google-colab-recommended)
  - [Run Locally](#-run-locally)
- [Dependencies](#dependencies)
- [Show Your Support](#show-your-support)

---

## About

This project implements **Neural Style Transfer** using the **VGG19** convolutional neural network. It blends the *content* of one image with the *artistic style* of another — producing stunning stylized outputs.

---

## Getting Started

### ☁️ Run on Google Colab (Recommended)

> **Note:** Make sure to switch the runtime to **GPU** for best performance.

**Step 1 — Open the notebook from GitHub:**

```
Google Colab → File → Open Notebook → GitHub → Paste the repository URL
```

**Step 2 — Switch to GPU runtime:**

```
Runtime → Change runtime type → Hardware accelerator → GPU → Save
```

**Step 3 — Run each cell sequentially** from top to bottom.

---

### 💻 Run Locally

**Step 1 — Clone the repository:**

```bash
git clone https://github.com/abhijitjadhav1998/Neural_Style_transfer_using_VGG19.git
cd Neural_Style_transfer_using_VGG19
```

**Step 2 — Install dependencies:**

If you encounter any missing library errors, install them using:

```bash
pip install <library-name>
```

For example:

```bash
pip install tensorflow
```

> **Jupyter Notebook users:** Prefix commands with `!` to run them inside a cell:
> ```
> !pip install tensorflow
> ```

**Step 3 — Launch Jupyter and run each cell** from top to bottom.

---

## Dependencies

Key libraries used in this project:

| Library | Purpose |
|---|---|
| `tensorflow` / `keras` | Deep learning framework |
| `numpy` | Numerical computations |
| `matplotlib` | Image visualization |
| `PIL` / `Pillow` | Image loading and processing |

Install all at once (if a `requirements.txt` is present):

```bash
pip install -r requirements.txt
```

---

## Show Your Support

If you found this project helpful, please consider:

- ⭐ **Starring** this repository
- 🍴 **Forking** it to build on top of it
- 📣 **Sharing** it with others

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abhijitjadhav1998/)
