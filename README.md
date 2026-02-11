# Seq2Seq LSTM Chatbot

A smart AI chatbot built with Seq2Seq architecture using LSTM layers and an attention mechanism. It generates human-like responses and supports step-by-step inference for interactive chatting.

🚀 Key Features

Seq2Seq LSTM Architecture: Separate encoder and decoder LSTM layers for robust sequence-to-sequence modeling.

Step-by-Step Inference: Generates responses one word at a time for natural conversational flow.

Separate Models: Encoder and decoder models saved independently for flexible deployment.

Tokenizer Integration: Handles text preprocessing and consistent word-to-token mapping.

Interactive Chat: Python script allows live conversation with the trained chatbot.

Training Pipeline: Includes early stopping, learning rate scheduler, and model checkpointing.

📁 Project Structure

encoder_model.keras – Trained encoder model.

decoder_model.keras – Trained decoder model.

tokenizer.pkl – Pre-fitted tokenizer.

best_model.keras – Full training model.



## 💡 How It Works

Encoding: Encoder LSTM converts user input into hidden states.

Decoding: Decoder LSTM predicts next words step-by-step, using attention to focus on important tokens.

Token Mapping: Converts predicted indices back to words via tokenizer.

Interactive Loop: Users can chat continuously; type quit to exit.

## 🌟 Benefits

Great for NLP portfolios and showcasing deep learning skills.

Modular design for easy upgrades: attention tweaks, beam search, or transformer integration.

Ready for integration with chat apps or web deployment.

#Seq2Seq #LSTM #Attention #Chatbot #DeepLearning #NLP #Python #AI #MachineLearning #EncoderDecoder #InteractiveChatbot #NeuralNetworks #Tokenization #ArtificialIntelligence #DeepLearningProjects #AIChat
