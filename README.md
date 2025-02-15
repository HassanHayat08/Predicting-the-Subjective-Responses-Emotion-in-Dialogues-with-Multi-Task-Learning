```markdown
# Predicting the Subjective Responses Emotion in Dialogues with Multi-Task Learning

This repository contains the source code and supplementary materials for the paper:

**[Predicting the Subjective Responses Emotion in Dialogues with Multi-Task Learning](https://link.springer.com/chapter/10.1007/978-3-031-36616-1_55)**

## Overview

Anticipating the subjective emotional responses of users is a critical capability for automatic dialogue systems. In this work, given a segment of dialogue, we address the problem of predicting the subjective emotional response that will be expressed by the next speaker. Our approach leverages both single-task and multi-task learning paradigms to predict emotions across different granularities:
- **3 Emotional Classes**
- **7 Emotional Classes**

This repository provides Jupyter notebooks for both learning settings along with supplementary materials detailing the experimental setup and results.

## Repository Contents

- **Multi-Task_for_3Emotional_Classes.ipynb**  
  Notebook for multi-task learning experiments with 3 emotional classes.
  
- **Multi-Task_for_7Emotional_Classes.ipynb**  
  Notebook for multi-task learning experiments with 7 emotional classes.
  
- **Single-Task_for_3Emotional_Classes.ipynb**  
  Notebook for single-task learning experiments with 3 emotional classes.
  
- **Single-Task_for_7Emotional_Classes.ipynb**  
  Notebook for single-task learning experiments with 7 emotional classes.
  
- **Supplementary_Materials.pdf**  
  Supplementary document providing additional details on the methodology, experimental setup, and results.

## Getting Started

### Prerequisites

- **Python 3.x** – Ensure that you have Python 3 installed on your system.
- **Jupyter Notebook** – Required to run the provided `.ipynb` files.
- Additional Python packages as needed (refer to each notebook for specific dependencies).

### Setup

1. Clone this repository to your local machine:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies. You may refer to the notebook cells for any additional package installations required.

## Usage

Open the desired Jupyter Notebook using Jupyter Notebook or JupyterLab:

```bash
jupyter notebook Multi-Task_for_3Emotional_Classes.ipynb
```

Each notebook is self-contained and includes instructions on how to run the experiments for:
- **Multi-Task Learning**: Experiments for predicting emotions using a multi-task approach.
- **Single-Task Learning**: Experiments for predicting emotions using a single-task approach.

Choose the notebook corresponding to the number of emotional classes you wish to work with (3 or 7).

## Citation

If you find this work useful in your research, please consider citing our paper:

```
@inproceedings{hayat2021predicting,
  title={Predicting the Subjective Responses Emotion in Dialogues with Multi-Task Learning},
  author={Hayat, Hassan and Ventura, Carles and Lapedriza, Agata},
  booktitle={Proceedings of the [Conference Name, Year]},
  year={2021},
  publisher={Springer}
}
```

For the complete reference, please see the paper: [Springer Link](https://link.springer.com/chapter/10.1007/978-3-031-36616-1_55).

## Contact

For any questions or further information regarding this package, please contact:

**Mr. Hassan Hayat**  
Email: [hhassan0@uoc.edu](mailto:hhassan0@uoc.edu)

## License

This project is licensed under the MIT License. You are free to use this code for academic and research purposes at your own risk.
```
