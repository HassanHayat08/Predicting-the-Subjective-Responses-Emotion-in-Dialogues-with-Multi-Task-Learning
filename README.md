# Predicting the Subjective Responses Emotion in Dialogues with Multi-Task Learning

This repository contains the source code and supplementary materials for the paper:

**[Predicting the Subjective Responses Emotion in Dialogues with Multi-Task Learning](https://link.springer.com/chapter/10.1007/978-3-031-36616-1_55)**

Anticipating the subjective emotional responses of the user is a critical capability for automatic dialogue systems. In this work, given a piece of dialogue, we address the problem of predicting the subjective emotional response of upcoming utterances—that is, forecasting the emotion that will be expressed by the next speaker.

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

- **Python 3.x** – Ensure you have Python 3 installed.
- **Jupyter Notebook or JupyterLab** – Required to run the provided `.ipynb` files.
- Additional Python libraries as specified within the notebooks.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **(Optional) Create and Activate a Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. **Install Required Packages:**

   Install any necessary dependencies using pip. Refer to the notebook cells for specific instructions if needed.

## Usage

Open the desired Jupyter Notebook using Jupyter Notebook or JupyterLab. For example, to run the multi-task learning experiment for 3 emotional classes:

```bash
jupyter notebook Multi-Task_for_3Emotional_Classes.ipynb
```

Each notebook is self-contained and includes instructions on how to run the experiments, along with code and comments to guide you through the process.

## Citation

If you find this work useful in your research, please consider citing our paper:

```bibtex
@inproceedings{hayat2021predicting,
  title={Predicting the Subjective Responses Emotion in Dialogues with Multi-Task Learning},
  author={Hayat, Hassan and Ventura, Carles and Lapedriza, Agata},
  booktitle={Proceedings of the Conference on Affective Computing and Intelligent Interaction},
  year={2021},
  publisher={Springer}
}
```

For the complete reference, please refer to the paper available [here](https://link.springer.com/chapter/10.1007/978-3-031-36616-1_55).

## Contact

For any questions or further information regarding this repository, please contact:

**Mr. Hassan Hayat**  
Email: [hhassan0@uoc.edu](mailto:hhassan0@uoc.edu)

## License

This project is licensed under the MIT License. You are free to use this code for academic and research purposes at your own risk.
```
