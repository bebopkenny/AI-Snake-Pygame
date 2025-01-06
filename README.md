# 🐍 Snake Game AI

An AI-powered Snake game built using **Python**, **Pygame**, and **PyTorch**. The AI agent learns to play the Snake game using **Q-Learning** with a **Deep Neural Network**.

---

## 🔗 Live Demo (Optional Section)
[View Gameplay Video](#)  

---

## ⚙️ Tech Stack
- **Python**
- **Pygame**
- **PyTorch**
- **Conda** (for environment management)

---

## 🔋 Features
- AI agent learns to play the Snake game using **Reinforcement Learning**.
- Real-time gameplay with dynamic UI updates.
- The agent improves its performance over time using **Q-Learning**.
- **Graphical Plot** to visualize the agent's progress (score and mean score).
- Fully customizable codebase with detailed comments for learning purposes.

---

## 📸 Screenshots

### Game Interface
![Snake Game Screenshot](path/to/gameplay-image.png)

### Training Graph
![Training Graph Screenshot](path/to/graph-image.png)

---

## 🚀 Installation Guide
### 1️⃣ Prerequisites
Ensure you have the following installed on your machine:
- **Python 3.7+**
- **Conda**

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/bebopkenny/Snake-AI-Game.git
cd Snake-AI-Game
```

### 3️⃣ Create a Conda Environment
```bash
conda create -n pygame_env python=3.7
conda activate pygame_env
```

### 4️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 🎮 Usage
### To Play the Game:
```bash
python game.py
```

### To Train the AI:
```bash
python agent.py
```

---

## 📊 How It Works
The AI agent is trained using **Q-Learning**, a type of reinforcement learning where the agent learns to maximize rewards by taking specific actions.

### AI Logic:
- **State Representation:** The agent observes the game state, including the position of the snake's head, food location, and possible collisions.
- **Action Space:** The agent can move in three directions: straight, left, or right.
- **Reward System:**
  - Positive reward (+10) for eating food.
  - Negative reward (-10) for hitting a wall or itself.
  
### Deep Neural Network:
The agent uses a **Linear Neural Network** built with PyTorch to predict the best possible action based on the current state.

---

## 📈 Graphical Plot
A **real-time graph** is displayed during training to visualize the agent's progress:
- **Number of Games vs. Score**
- **Mean Score over Time**

The graph is generated using **Matplotlib**.

---

## 📧 Contact
- **Kenny Garcia**  
- **Email:** kennygarcia15@yahoo.com  
- **Portfolio:** [kennygarcia.net](https://kennygarcia.net)

---

## 📚 Future Improvements
- Add more complex reward structures to improve the agent's decision-making.
- Optimize the neural network architecture for faster training.
- Implement additional gameplay features such as obstacles and different game modes.

---

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).
