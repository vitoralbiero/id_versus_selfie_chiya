# Identity Document to Selfie Face Matching Across Adolescence

This repository contains the fine-tuned model proposed in the paper ["Identity Document to Selfie Face Matching Across Adolescence"](https://arxiv.org/abs/1912.10021).

The model can be download [here](https://drive.google.com/open?id=1wpDk77bfjMxSu2_eKNfg6M4exVM7lO4U).

The cleaned Public-IvS that is used in the paper can be found [here](https://drive.google.com/open?id=1qSwX7hDmww-A2Zwo5EUP9nZaOpc3RLJw).

To extract features using the model provided, use [insightface_feature_extraction](https://github.com/vitoralbiero/face_matching/blob/master/insightface_feature_extraction.py).

And to match features, use [mult_feature_match_list](https://github.com/vitoralbiero/face_matching/blob/master/mult_feature_match_list.py).

You will need a copy of the InsighFace [deploy folder](https://github.com/deepinsight/insightface/tree/master/deploy).

If you use our model, please cite the paper below.

```
@misc{albiero2019identity,
    title={Identity Document to Selfie Face Matching Across Adolescence},
    author={Vítor Albiero and Nisha Srinivas and Esteban Villalobos and Jorge Perez-Facuse and Roberto Rosenthal and Domingo Mery and Karl Ricanek and Kevin W. Bowyer},
    year={2019},
    eprint={1912.10021},
    archivePrefix={arXiv}
}
```
