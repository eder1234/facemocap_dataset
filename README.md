# Facemocap Dataset
Welcome to the GitHub repository for the FaceMoCap dataset. This repository provides some codes to explore the dataset and to exploit some of its functionalities. For a more detailed information, please refer to the article.

<img src="markers_cv-0.jpg" width="700" height="850">

## Description
The FaceMoCap dataset provides a novel resource for the analysis and quantification of facial movements. Our dataset includes point cloud sequences that depict a variety of facial gestures from both healthy adults and patients with facial palsy. This dataset has been carefully collected and processed into a readily accessible Python dataframe, offering potential applications in areas such as facial gesture recognition, patient follow-up, and imputation of missing values. 

## Dataset

Below is a simplified representation of the described dataframe. 
| SPC original | SPC dental | SPC imputed | Mocap platform | Date of acquisition | Age at Acquisition | Public ID | Protocol name | Protocol ID | Protocol ID clinicaltrials.gov |
|--------------|------------|-------------|----------------|---------------------|--------------------|----|---------------|-------------|--------------------------------|
| `data` | `data` | `data` | Sport Health Technology | 2023-11-28 | 31 | 9 | SIMOVI 1 | ID-RCB 2011-A00532-39 | NCT 02002572 |
| `data` | `data` | `data` | Institute Faire Faces | 2023-06-27 | 28 | 1 | SIMOVI 2 | ID-RCB 2016-A00716-45 | NCT 03115203 |
| `data` | `data` | `data` | Sport Health Technology | 2021-01-15 | 24 | 32 | SIMOVI 1 | ID-RCB 2011-A00532-39 | NCT 02002572 |
| `data` | `data` | `data` | Institute Faire Faces | 2022-03-07 | 20 | 22 | SIMOVI 2 | ID-RCB 2016-A00716-45 | NCT 03115203 |

## Access to the Dataset
Due to privacy considerations, the FaceMoCap dataset is not publicly available in this repository. If you wish to gain access to the dataset, please send me an email request detailing your planned usage.

## Getting Started
This repository includes a Python guide that will help you understand and utilize the dataset effectively. In order to use this guide, please clone the repository and install the requirements detailed in the requirements.txt file. 

```bash
git clone https://github.com/eder1234/facemocap_dataset.git
cd facemocap_dataset
pip install -r requirements.txt
```

Once installed, you can navigate the dataset using the included Python tutorial.

## Citation
Pending...

## Contact information
Owner
- Name: Eder Alejandro Rodriguez Martinez
- Email: eder_rdz_mtz@hotmail.com
