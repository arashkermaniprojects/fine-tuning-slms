# Read · See · Hear: Fine-Tuning Small Multimodal Language Models

An interactive guide to the 11 papers for MAI 656 Natural Language Processing, Assignment 1 (Canadian University Dubai, Fall 2026). The topic is how small open models read text, see images and hear speech, and how to fine-tune them with LoRA or QLoRA.

Open `index.html` in a browser and begin with **Start here**, a visual primer on tokens, vision and audio encoders, LoRA/QLoRA, the free GPU, metrics, normalization and fairness, and a map of the papers. Each paper tab starts with a narrated "Before you read" intro. Each tab covers one paper, with every figure redrawn as a diagram, every equation, the results tables and a "For your assignment" box: which inputs the model accepts, whether it plausibly fits a free Colab T4 with QLoRA, where to put LoRA, and a fairness or normalization angle.

- **Guides:** every block has a collapsed "Guide" note. Link to one directly with `index.html#g-<guide-id>`, for example `#g-qlora-fig-01`.
- **Guided tours:** each paper has a narrated tour (about 4 to 5 minutes) that scrolls through the key blocks. The narration is in `audio/`, generated with Google Cloud Text-to-Speech (voice en-US-Chirp3-HD-Charon). The scripts are in `tours/`.
- **`atlas-guides.json`:** all guide texts, with paper, block type and label.

| Group | Papers |
|---|---|
| The fine-tuning toolkit | QLoRA |
| Seeing: vision-language models | TinyLLaVA Factory, SmolVLM |
| Hearing: speech-language models | Voxtral, Voxtral Realtime |
| An efficient small-model backbone | LFM2 |
| Omni: text, image and voice together | MiniMind-O, Qwen2.5-Omni, Qwen3-Omni (reference), MiniCPM-o 4.5, Gemma 4 |

The diagrams are redrawn illustrations for teaching. Where a plot was redrawn from its shape rather than from printed numbers, the caption says so. Refer to the original papers for exact figures.
