# Advanced Topics in Computer Vision and Deep Learning

A collection of Jupyter notebooks covering traditional computer vision, convolutional neural networks, Earth Observation (EO) data processing, segmentation, and generative models.

---

## Repository Overview

### `Traditional CV/`
| Notebook | Description |
|---|---|
| `basics.ipynb` | Introduction to classical image processing with `scikit-image`: image loading, histogram analysis, contrast stretching & normalisation, Gaussian blur, sharpening, Sobel edge detection, morphological operations (dilation, erosion, opening, closing), and Otsu thresholding. |

---

### `CNNs/`
| Notebook | Description |
|---|---|
| `intro_cnn.ipynb` | Hands-on walkthrough of core CNN building blocks using TensorFlow: manual convolution kernels, ReLU / sigmoid / tanh activations, max and average pooling, flattening, and fully-connected (Dense) layers — applied to a sample image. |

---

### `EO Basics/`
| Notebook | Description |
|---|---|
| `load_stac_catalog.ipynb` | Demonstrates how to query and load Earth Observation imagery from a STAC (SpatioTemporal Asset Catalog), inspect collection metadata, and read raster data into Python. |
| `dask_stac.ipynb` | Extends STAC access with Dask for lazy, out-of-core loading of large EO datasets — covers chunked array creation, parallel reads, and basic band visualisation. |

---

### `eo_segmentation/`
| Notebook | Description |
|---|---|
| `eo_semantic_segmentation_clc2023.ipynb` | Semantic segmentation of EO imagery using the CORINE Land Cover 2023 (CLC 2023) dataset — includes data preparation, model training/fine-tuning, and evaluation. |
| `eo_inference.ipynb` | Runs inference with a trained segmentation model on new EO scenes, visualises predicted land-cover masks, and assesses model performance. |

---

### `Generative/`
| Notebook | Description |
|---|---|
| `generative.ipynb` | Builds and trains a convolutional **autoencoder** on MNIST digits using TensorFlow/Keras. Covers encoder/decoder architecture, latent-space visualisation (2-D), image reconstruction, and generating new digit images by sampling the latent space. |

---

## Key Libraries

| Domain | Libraries |
|---|---|
| Image processing | `scikit-image`, `Pillow` |
| Deep learning | `TensorFlow / Keras` |
| EO data | `pystac`, `stackstac`, `Dask`, `rioxarray` |
| Visualisation | `matplotlib`, `numpy` |

---

## Getting Started

```bash
# Install common dependencies
pip install scikit-image pillow tensorflow matplotlib numpy

# For EO notebooks
pip install pystac stackstac dask rioxarray
```

Open any notebook with JupyterLab or the JetBrains IDE and run cells sequentially.

---

## 🔗 Useful Links & Resources

### Traditional Computer Vision
| Resource | Link |
|---|---|
| scikit-image Documentation | https://scikit-image.org/docs/stable/ |
| scikit-image Examples Gallery | https://scikit-image.org/docs/stable/auto_examples/ |
| OpenCV Documentation | https://docs.opencv.org/4.x/ |


### Convolutional Neural Networks
| Resource | Link |
|---|---|
| TensorFlow / Keras Documentation | https://www.tensorflow.org/api_docs/python/tf/keras |
| CS231n: CNNs for Visual Recognition (Stanford) | https://cs231n.github.io/ |
| Deep Learning Book (Goodfellow et al.) | https://www.deeplearningbook.org/ |
| TensorFlow CNN Tutorial | https://www.tensorflow.org/tutorials/images/cnn |

### Earth Observation & Geospatial
| Resource | Link |
|---|---|
| STAC Specification | https://stacspec.org/ |
| PySTAC Documentation | https://pystac.readthedocs.io/ |
| stackstac Documentation | https://stackstac.readthedocs.io/ |
| Dask Documentation | https://docs.dask.org/ |
| rioxarray Documentation | https://corteva.github.io/rioxarray/ |
| CORINE Land Cover (CLC) | https://land.copernicus.eu/pan-european/corine-land-cover |
| EO College (ESA) | https://eo-college.org/ |
| Awesome Satellite Imagery Datasets | https://github.com/satellite-image-deep-learning/datasets |

### Segmentation & Deep Learning for EO
| Resource | Link |
|---|---|
| torchgeo Documentation | https://torchgeo.readthedocs.io/ |
| Segmentation Models (PyTorch) | https://github.com/qubvel/segmentation_models.pytorch |
| PyTorch Documentation | https://pytorch.org/docs/stable/ |
| Papers With Code – Semantic Segmentation | https://paperswithcode.com/task/semantic-segmentation |

### Generative Models
| Resource | Link |
|---|---|
| Keras Autoencoder Tutorial | https://blog.keras.io/building-autoencoders-in-keras.html |
| VAE Tutorial (Kingma & Welling) | https://arxiv.org/abs/1312.6114 |
| GAN Paper (Goodfellow et al.) | https://arxiv.org/abs/1406.2661 |
| Lilian Weng's Blog – VAE | https://lilianweng.github.io/posts/2018-08-12-vae/ |

### General Deep Learning
| Resource | Link |
|---|---|
| fast.ai Practical Deep Learning | https://course.fast.ai/ |
| Dive into Deep Learning (d2l.ai) | https://d2l.ai/ |
| Papers With Code | https://paperswithcode.com/ |
| Hugging Face Hub | https://huggingface.co/ |

### Local Resources (West University of Timisoara)
| Resource         | Link |
|------------------|---|
| UVT ROCS Project | https://rocs.uvt.ro/ |
|EOCube            | https://eocube.ro/ |
|UVT STAC Catalog  | https://browser.stac.eocube.ro/?.language=en |

