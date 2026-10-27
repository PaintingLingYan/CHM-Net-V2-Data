# CHM-Net V2

CHM-Net V2 studies patient-level microbial-density classification using MRI and H&E-derived pathology information. The manuscript also evaluates generalization across four public 3D medical imaging datasets.

## Public Dataset

### NoduleMNIST3D

NoduleMNIST3D is a public 3D CT classification benchmark for distinguishing benign and malignant lung nodules.

- **Modality:** 3D computed tomography (CT)
- **Task:** binary classification of lung nodules
- **Samples:** 1,633, as reported in the manuscript
- **Source:** [MedMNIST](https://medmnist.com/)

The dataset is not mirrored in this repository. Please use the official MedMNIST distribution and follow its current access terms and citation requirements. See [`docs/dataset.md`](docs/dataset.md) for the dataset note and citation.

## Experiments

Performance comparisons reported in the manuscript. Best results are highlighted in blue; second-best results are underlined.

### RSNA-MICCAI and BraTS2020

![Table II: Generalization performance on RSNA-MICCAI and BraTS2020](img/Table2.png)

### NoduleMNIST3D and AdrenalMNIST3D

![Table III: Generalization performance on NoduleMNIST3D and AdrenalMNIST3D](img/Table3.png)

## Visual Comparisons

Visualization results on the four public 3D medical imaging datasets. The figure shows BraTS2020, AdrenalMNIST3D, RSNA-MICCAI, and NoduleMNIST3D examples.

![Visual comparison on public datasets](img/Visual_Public_Four.png)
