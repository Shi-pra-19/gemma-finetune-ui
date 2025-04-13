# Gemma 2B Fine-Tuning Dashboard

This project provides an interactive **Streamlit dashboard** for fine-tuning Google's **Gemma-2B instruction-tuned model** 

---

## 🚀 Features

- **Dataset Selection**: Choose from curated datasets like Code Alpaca, Databricks Dolly 15K, OpenAssistant OASST1, and Guanaco OpenAssistant.
- **Custom Field Mapping**: Assign dataset columns. 
- **Model Loading**: Load the quantized Gemma-2B model with 4-bit precision using `BitsAndBytesConfig` for efficient training.
- **Parameter Configuration**: Adjust training parameters including batch size, learning rate, gradient accumulation steps, and maximum training steps.
- **Real-Time Visualization**: Monitor training progress with dynamic loss curves and step-wise updates using Plotly charts.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Shi-pra-19/gemma-finetune-ui.git
   cd gemma-finetune-ui
   ```

3. **Set Up Authentication**:
   - **Hugging Face**: Obtain your Hugging Face API token and set it in the environment.
   - **Ngrok**: Sign up for Ngrok, obtain your auth token, and set it in the environment.
  
4.
   - **Weights & Biases (Optional)**: For experiment tracking, set up your W&B API key.
---


 **Access via Ngrok**:
   The application will automatically start Ngrok and display a public URL in the terminal. Use this URL to access the dashboard remotely.

