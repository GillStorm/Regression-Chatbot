# Regression-Chatbot

This project is a **simple neural-network based chatbot** built using **PyTorch** upon the machine learning concept of Linear Regression.  
The chatbot learns to classify user input into predefined **intents** using a *Bag-of-Words model* and a small feed-forward neural network.

---

 Features

- ✅ Written in **Python** with **PyTorch**
- ✅ Uses Bag-of-Words for text representation
- ✅ Neural network with 2 hidden layers (ReLU activation)
- ✅ Predicts user intent using softmax confidence score
- ✅ Simple training on hard-coded patterns
- ✅ Interactive chat mode in terminal



 How It Works

1. The chatbot has predefined **intents** like `greeting`, `goodbye`, `thanks`, etc.
2. Each intent contains:
   - patterns (training sentences)
   - responses (what bot replies)
3. Text patterns are tokenized and converted to **Bag-of-Words vectors**.
4. These vectors are fed to a **feed-forward neural network**.
5. The model outputs probabilities → highest probability = predicted intent.

---

Technologies Used

| Component | Library |
|----------|---------|
| Deep Learning Framework | PyTorch |
| Numerical Computation | NumPy |
| Model Training | Adam Optimizer + CrossEntropy Loss |
