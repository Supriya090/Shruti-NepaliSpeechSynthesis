# Shruti - Nepali Speech Synthesis

Speech Synthesis Component of [Shruti - A Nepali Audiobook Platform](https://gitlab.com/shrutiaudio/shrutiapplication)

<hr>

The text-to-speech system has two components:

1. **Melspectrogram Generation**
  -  Finetuning Tacotron2([Shen et.al])(https://arxiv.org/abs/1712.05884) for melspectrogram generation
2. **Vocoder Output**
  -  Using WaveGLOW([Prenger et.al])(https://arxiv.org/abs/1811.00002) and HifiGAN([Kong et.al])(https://arxiv.org/abs/2010.05646) for vocoder output

### Training Data

- Pretrained Tacotron2 model trained on The LJSpeech Dataset([Ito and Johnson])(https://keithito.com/LJ-Speech-Dataset/)
- Finetuning Phase 1 - High quality TTS data for Nepali([Sodimana et.al])(https://www.openslr.org/43/)
- Finetuning Phase 2 - Created own Dataset;Nepali Text-to-Speech Data (Male and Female)([Khadka et.al])(https://openslr.elda.org/143/)


Find the output samples [here](https://shruti-audios.netlify.app) and the paper [here](https://www.isca-archive.org/sigul_2023/khadka23_sigul.pdf).

<hr>

If you use the code or dataset, please cite our work and all the references that we have cited.

```@inproceedings{khadka2023nepali,
  title={Nepali Text-to-Speech Synthesis using Tacotron2 for Melspectrogram Generation},
  author={Khadka, Supriya and Ranju, GC and Paudel, Prabin and Shah, Rahul and Joshi, Basanta},
  booktitle={Proc. 2nd Annual Meeting of the ELRA/ISCA SIG on Under-resourced Languages (SIGUL 2023)},
  pages={73--77},
  year={2023}
}
```

