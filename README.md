[![Dataset: Urdu Deepfakes](https://img.shields.io/badge/Dataset-%20Urdu%20Deepfakes-yellow?logo=🤗&style=flat-square)](https://huggingface.co/datasets/CSALT/deepfake_detection_dataset_urdu)

# Deepfake Defense: Constructing and Evaluating a Specialized Urdu Deepfake Audio Dataset

This repository contains the Urdu Deepfake Audio Dataset introduced in the ACL 2024 paper "Deepfake Defense: Constructing and Evaluating a Specialized Urdu Deepfake Audio Dataset".

The dataset focuses on two spoofing attacks – Tacotron and VITS TTS – and includes bonafide audio samples for comparison. The dataset construction ensures phonemic cover and balance, making it suitable for training deepfake detection models in Urdu.

### Dataset Statistics

The dataset includes the following four parts:

1. Bonafide Part 1
2. Bonafide Part 2
3. Tacotron
4. VITS TTS

The statistics for each part are as follows:

| **Metric**                   | **Bonafide Part 1** | **Bonafide Part 2** | **Tacotron** | **VITS TTS** |
|------------------------------|---------------------|---------------------|--------------|--------------|
| **Total Duration (mins)**    | 1,302.66            | 1,271.65            | 1,061.96     | 1,340.79     |
| **Max Sample Length (mins)** | 112.42              | 120.75              | 80.34        | 111.01       |
| **Min Sample Length (mins)** | 61.73               | 56.45               | 44.64        | 65.53        |
| **Avg Sample Length (mins)** | 76.63               | 74.80               | 62.47        | 78.87        |
| **Files per Speaker**        | 708 audio files     | 495 audio files     | 495 audio files | 495 audio files |

## Structure

The dataset is organized into folders, each containing audio files for the respective parts mentioned above. Each folder is named according to its part (e.g., `Bonafide_Part1`, `Tacotron`, etc.).

## Usage

The dataset is available on Google Drive and Huggingface datasets through the following links:
- Google Drive: <Add Link>
- Huggingface Datasets: https://huggingface.co/datasets/CSALT/deepfake_detection_dataset_urdu

## Citation
```
@inproceedings{sheza-etal-2024-deepfake,
    title = "Deepfake Defense: Constructing and Evaluating a Specialized Urdu Deepfake Audio Dataset",
    author = "Sheza Munir, Wassay Sajjad, Mukeet Raza, Emaan Mujahid Abbas, Abdul Hameed Azeemi, Ihsan Ayyub Qazi, and Agha Ali Raza",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2024",
    year = "2024",
    publisher = "Association for Computational Linguistics",
}
```

## Legal

CC BY-NC 4.0 license for the data hosted on HuggingFace and Google Drive. 
