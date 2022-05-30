# transformers-papers
Papers club from the AI team in D-ID  - this time transformers from attention to vision lectures are in Hebrew

מועדון קריאת מאמרים שלנו - כל ההרצאות בעיברית
| Lecture | Paper / Resource | Year | Why is it interesting? | Asignee | Recording | Presentation |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Transformers are worth your attention** | [Attention is all you need](https://arxiv.org/abs/1706.03762) | 2017 | <details><summary>read why</summary>The paper that started it all, introduction to the basic concept & comparison to previous methods like RNN. The transformer here has both encoder & decoder layers creating a seq2seq model</details> | [@matan-feldman](https://github.com/matan-feldman) | [zoom](https://us02web.zoom.us/rec/share/kZvYM3MCuiYUSMEvmhizJe2qMYgcDXoauCzRIVc-6wAb1-D1voWsHykIXoYQoum0._4_HD8RGKeb2KX-O) (K%32MLKi) | [slides](https://docs.google.com/presentation/d/1Qwbj3V7-GAnEJnsAHBFS4AG_k6bVQsP41VcaZObz1Kw/edit#slide=id.g1157f5f83be_0_279) |
| **Transformers tricks -  Positional Encoding, Layer Norm, Residual Connections. In code!** | [The annotated transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html) | 2017 | <details><summary>read why</summary>Going into depth into the various tricks used to make transformers work. Implementing a trnasformer without them would lead to poor results</details> | x | x | x |
| **Visualizing Attention** | [Visualizing Attention in Transformer-Based Language Representation Models](https://arxiv.org/abs/1904.02679) [On the Relationship between Self-Attention and Convolutional Layers](https://github.com/epfml/attention-cnn)  | 2017 | <details><summary>read why</summary>Attention is useful for explainability too, we can see what the network is using for the task. In this lecture we will exammine visualizations of this in NLP & vision</details> | x | x | x |
| **BERT** | [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805) | 2018 | <details><summary>read why</summary>This model from Google used only encoders & achived state of the art on many NLP tasks</details> | [@leong-deid](https://github.com/leong-deid) | [zoom](https://us02web.zoom.us/rec/share/e5v6NUg-7YyWwlZh9ah471sk7himZNBJCt6UpnGLVJaTkc03ETQMtu7rwelO6yAw.767Kzjh9RGmNormj) (LW$8fQ6f) | [slides](https://docs.google.com/presentation/d/1Nw72FAjAzCBc7pM4Je-KVZ5GBHnpMJBMbXm3S7BPf64/edit?usp=sharing) |
| **GPT** | [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) | 2020 | <details><summary>read why</summary>This model from OpenAI used only decoders & achived state of the art text generation. Its authors first didn't release it becuase they said it is too dangerous. It is now the backbone of Github Co-Pilot</details> | x | x | x |
| **Wav2Vec U** | [Wav-to-vec U - Unsupervised Speech Recognition](https://ai.facebook.com/blog/wav2vec-unsupervised-speech-recognition-without-supervision/) | 2021 | <details><summary>read why</summary>this unsupervised model from Facebook, is able to learn language representations. we use the supervised version in our A2K input</details> | [@matan-feldman](https://github.com/matan-feldman) | [zoom](https://us02web.zoom.us/rec/share/Dk9cf7-iXgCv13_FEBSSYMDc1ZWeEbaVAtLERa9-UPVAZjKKttn-6Rx9I-0G2Jj3.iXL0WXaHG4HIof5o) (p.qE+Q59) | [slides](https://docs.google.com/presentation/u/0/d/1Zn2JETCpCcNDsSLsrMlVgsf8fNDJ35s50ymOzAA1d8U/edit) |
| **DETR for object detection & segmentations** | [End-to-End Object Detection with Transformers](https://arxiv.org/abs/2005.12872) | 2020 | <details><summary>read why</summary>Taking transformers even further to other CV tasks in this paper the autors from FacebookAI combine CNN with transformers to reduce some of the human prio needed in designing object detection & segmentation models</details> | [@talbenh](https://github.com/talbenh) | [zoom](https://us02web.zoom.us/rec/share/2EJyfh4SdomCLkHxBPFskQYZ1jKeX0gCvK5Fkqc2EgcYzseOVIlsIXKVSMwlZHSW.Q9fdGBPkOnA-39pi) (17K%NSf3) | [slides](https://docs.google.com/presentation/u/0/d/15MM4QR1-XTs--W3TZUPwE1gy3-dkqq_27gfAY-G0b8o/edit) |
| **ViT** | [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929) | 2020 | <details><summary>read why</summary>Treats the image as a sentence of 16x16 patches words. The model acheives SoTA in classiciation tasks with significant less compute. with supervision from large scale images datasets</details> | [@alon-mengi](https://github.com/alon-mengi) | [zoom](https://us02web.zoom.us/rec/share/bEbm9wFxv_Srgf8WXJ3W9g-8_Wp3HFns8sataa9vj8Yn1D1OMfkXdRpSwR137W8F.v1gKK36WE8mYaRqM) (ve1VHEM=) | [slides](https://docs.google.com/presentation/u/0/d/1el_a1OJ2RMkiIvSS8FlvUp2B8Z-xhpqEiQN1_ZOFGfE/edit) |
| **CLIP** | [Learning Transferable Visual Models From Natural Language Supervision](https://openai.com/blog/clip/) | 2021 | <details><summary>read why</summary>OpenAI model that learns two encoders from images &text & via contrastive learning achive SoTA result on image classification while increasing dramatically the robustness over previous methods. Using internet scraped data instead of expesive annotated datasets.</details> | [@amitay-nachmani](https://github.com/amitay-nachmani) | [zoom](https://us02web.zoom.us/rec/share/6w64udHDc0hg91pTn2vFjSTpZ18AcvGOx2dtXMsltGSr7hOaIE5PWkg1Pj72BDFM.io0ww9YZ8YO_Lk9z) (^a1!1BJf) | [slides](https://docs.google.com/presentation/d/1i7TwJ-2NgP3GEYEF8mWYP4kksdFqVNXdBBHo2RdraCw/edit?usp=sharing) |
| **Preceiver** | [Perceiver IO: A General Architecture for Structured Inputs & Outputs](https://arxiv.org/abs/2107.14795) | 2021 | <details><summary>read why</summary>Preceivers models use cross-attention & learned latent dictionaries to work on many modalities by reducing the self attention complexity. The authors demostrate that the model produces baseline results on many tasks</details> | [@orgoro](https://github.com/orgoro) | [zoom](https://us02web.zoom.us/rec/share/hzf27YYtJoTlgiGaCqoJwdC7yqwsFSssMdKGJUcK3lD2j8qL8e8yKGo-2Ou8zuIE.j6OURm7XUsCxuFlX) (Ba9DQ&Ef) | [slides](https://docs.google.com/presentation/d/19tGtIMAyb8MVplQlSzObAxN3xnMPpUsZC5G3PJwV8bo/edit) |
| **Dall-E2 & Imagen**  | [Hierarchical Text-Conditional Image Generation with CLIP Latents](https://arxiv.org/abs/2204.06125) | 2022 | <details><summary>read why</summary>DALL·E 2 is a new AI system that can create realistic images and art from a description in natural language from OpenAI. The model uses CLIP embedding & diffusion models to generate images from a text description. Google DeepMind also came up with a competing model called Imagen that argues for superior quality</details> | [@talbenh](https://github.com/talbenh) | zoom () | slides |
