# Fine-Tuning Small Multimodal Models

An interactive guide to 11 papers on how small open models read text, see images and hear speech, and how to fine-tune them with LoRA and QLoRA on a single free GPU.

Open `index.html` in a browser, or visit the GitHub Pages site. Begin with **Start here**, a visual primer on tokens, vision and audio encoders, omni models, LoRA/QLoRA, the free Colab/Kaggle GPU, data, metrics, text normalization and fairness, and a map of the papers. Each paper tab opens with a narrated "Before you read" intro, then covers the paper with every figure redrawn as a diagram, every equation, the results tables and a "Putting it into practice" box: which inputs the model accepts, whether it plausibly fits a free T4 with QLoRA, where to put LoRA, and a fairness or normalization angle.

- **Guides:** every block has a collapsed "Guide" note. Link to one directly with `index.html#g-<guide-id>`, for example `#g-qlora-fig-01`.
- **Intros and guided tours:** each paper has a short narrated intro and a narrated tour (about 4 to 5 minutes) that scrolls through the key blocks. The narration is in `audio/` (Google Cloud Text-to-Speech, voice en-US-Chirp3-HD-Charon) and the scripts in `tours/`.
- **`atlas-guides.json`:** all guide texts, with paper, block type and label.

| Group | Papers |
|---|---|
| The fine-tuning toolkit | QLoRA |
| Seeing: vision-language models | TinyLLaVA Factory, SmolVLM |
| Hearing: speech-language models | Voxtral, Voxtral Realtime |
| An efficient small-model backbone | LFM2 |
| Omni: text, image and voice together | MiniMind-O, Qwen2.5-Omni, Qwen3-Omni, MiniCPM-o 4.5, Gemma 4 |

The diagrams are redrawn illustrations for teaching. Where a plot was redrawn from its shape rather than from printed numbers, the caption says so. Refer to the original papers for exact figures.
