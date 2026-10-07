# IT Support Chatbot

**Author:** Dolly Jain

An IT support chatbot built with Qwen2.5-0.5B-Instruct, fine-tuned using LoRA in Google Colab. It answers questions about email, VPN, Teams, printers, Wi-Fi, and account access through a Gradio chat UI.

## Data and evaluation
- Training: 94 examples; validation: 11; held-out test: 11.
- Training: 3 epochs.
- Manual usefulness score (0–2 per answer): base model 6/22; fine-tuned model 11/22.

## Run
Open `IT_Support_Chatbot.ipynb` in Google Colab and follow its cells. The saved model adapter and project data are kept in the project Google Drive folder.

## Limitation
Some answers are incomplete or incorrect. This is a demonstration, not a replacement for human IT support.

Live chatbot working Link - https://5f967e0e945dcd6f0c.gradio.live/
