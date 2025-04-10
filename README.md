# CLASP: Contrastive Language-Speech Pretraining for Multilingual Multimodal Information Retrieval

This includes the original implementation of [CLASP: Contrastive Language-Speech Pretraining for Multilingual Multimodal Information Retrieval](https://arxiv.org/abs/2412.13071) ([ECIR 2025](https://link.springer.com/chapter/10.1007/978-3-031-88717-8_2)) by Mohammad Mahdi Abootorabi and Ehsaneddin Asgari.

[Models](https://huggingface.co/llm-lab/CLASP) | [Springer Link](https://link.springer.com/chapter/10.1007/978-3-031-88717-8_2) | [arXiv Link](https://arxiv.org/abs/2412.13071v1) | [Proposed Dataset](https://huggingface.co/datasets/llm-lab/SpeechBrown)

## Abstract
This study introduces CLASP (Contrastive Language-Speech Pretraining), a multilingual, multimodal representation tailored for audio-text information retrieval. CLASP leverages the synergy between spoken content and textual data. During training, we utilize our newly introduced speech-text dataset, which encompasses 15 diverse categories ranging from fiction to religion. CLASP's audio component integrates audio spectrograms with a pre-trained self-supervised speech model, while its language encoding counterpart employs a sentence encoder pre-trained on over 100 languages. This unified lightweight model bridges the gap between various modalities and languages, enhancing its effectiveness in handling and retrieving multilingual and multimodal data. Our evaluations across multiple languages demonstrate that CLASP establishes new benchmarks in HITS@1, MRR, and meanR metrics, outperforming traditional ASR-based retrieval methods that rely on transcribing speech into text for subsequent text retrieval in specific scenarios.

![CLASP-panel5](https://github.com/user-attachments/assets/472c5a52-29dd-4c59-af65-22a43fadc47e)


## Contributions
1. We introduce CLASP (Contrastive Language-Speech Pretraining), a novel lightweight multilingual, multimodal representation designed for audio-text retrieval.
2. We introduce a diverse paired speech-text dataset (Speech Brown) in 15 categories, encompassing a wide range of topics from fiction to religion.
3. We show that the combination of audio spectrograms with a pre-trained self-supervised speech model improves audio encoding in retrieval applications.
4. Evaluations in multiple languages demonstrate that CLASP sets new benchmarks in HITS@1, Mean Reciprocal Rank (MRR), and Mean Rank (meanR) metrics.

## Citations
If you find our paper, code, data, or models useful, please cite the paper:
```
@misc{abootorabi2024claspcontrastivelanguagespeechpretraining,
      title={CLASP: Contrastive Language-Speech Pretraining for Multilingual Multimodal Information Retrieval}, 
      author={Mohammad Mahdi Abootorabi and Ehsaneddin Asgari},
      year={2024},
      eprint={2412.13071},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2412.13071}, 
}
```

## Contact
If you have questions, please send an email to mahdi.abootorabi2@gmail.com or asgari@berkeley.edu.
