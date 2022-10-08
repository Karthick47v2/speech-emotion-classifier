<h1 align="center">Welcome to speech-emotion-classifier 👋</h1>
<p>
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

This is a part of [Mock-Buddy](https://github.com/Karthick47v2/mock-buddy) project, used to detect speech confidence. CNN architecture used to build the model to classify emotions. The ensembled model is build with TensorFlow applying bootstrap aggregation apporach.

## Prerequisite

- Python 3.7 or newer

## Dataset

- [RAVDEES](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)
- [SAVEES](https://www.kaggle.com/datasets/ejlok1/surrey-audiovisual-expressed-emotion-savee)
- [TESS](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess)

## Usage

- You can download dataset from `data.ipynb`. Run it and preprocess data.
- Run `train.ipynb` to start training.
- `ser_pred.ipyb` has template for using model inside other applications.

## Author

👤 **Karthick T. Sharma**

- Github: [@Karthick47v2](https://github.com/Karthick47v2)
- LinkedIn: [@Karthick47](https://linkedin.com/in/Karthick47)

## Citation

The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) can be downloaded free of charge at https://zenodo.org/record/1188976.

```
@data{SP2/E8H2MF_2020,
author = {Pichora-Fuller, M. Kathleen and Dupuis, Kate},
publisher = {Scholars Portal Dataverse},
title = "{Toronto emotional speech set (TESS)}",
year = {2020},
version = {DRAFT VERSION},
doi = {10.5683/SP2/E8H2MF},
url = {https://doi.org/10.5683/SP2/E8H2MF}
}

@inproceedings{Vlasenko_combiningframe,
author = {Vlasenko, Bogdan and Schuller, Bjorn and Wendemuth, Andreas and Rigoll, Gerhard},
year = {2007},
month = {01},
pages = {2249-2252},
title = {Combining frame and turn-level information for robust recognition of emotions within speech},
journal = {Proceedings of Interspeech}
}
```

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/Karthick47v2/speech-emotion-classifier/issues).

## Show your support

Give a ⭐️ if this project helped you!
