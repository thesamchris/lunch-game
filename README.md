# Team Lunch Trivia Game

Welcome to the **Team Lunch Trivia Game**! This interactive and fun-filled game is designed to bring your team together for an engaging activity during your lunch break. Whether you're looking to boost team morale, encourage collaboration, or simply have a good time, this game is the perfect addition to your team events.

<img width="1192" alt="image" src="https://github.com/user-attachments/assets/2098a58f-77bd-45d9-8537-b2b455403717">

*(Screenshot of the game in action)*

---

## 🎉 Why Play This Game?

- **Interactive Fun**: Engage your team with moving answers that add a dynamic twist to traditional trivia.
- **Team Building**: Encourage teamwork and friendly competition as team reps participate.
- **Easy to Set Up**: Simple installation and minimal requirements mean you can get started quickly.
- **Customizable**: Easily add your own questions and answers to tailor the game to your team's interests.
- **Visually Appealing**: High-contrast colors and elegant design make the game visually engaging.

---

## 📝 Game Overview

The Team Lunch Trivia Game is an interactive quiz where questions are displayed on a screen, and the answers move around dynamically. When you press the **Space Bar**, the answers freeze in place. Team representatives, blindfolded, then try to place a sticky note on the projection wall over the correct answer. It's a hilarious and enjoyable way to test knowledge and have fun together!

---

## 📋 Features

- **Dynamic Moving Answers**: Answers bounce around the screen with realistic physics collisions.
- **Easy Navigation**: Use the **Left** and **Right Arrow Keys** to navigate between questions.
- **Pause and Play**: Press the **Space Bar** to freeze or unfreeze the moving answers.
- **Customizable Questions**: Input your own set of questions and answers in a simple Markdown format.
- **Elegant Design**: Minimalistic and high-contrast visuals with beautiful fonts for readability.
- **No Special Software Required**: Runs in any modern web browser.

---

## 🚀 Getting Started

### **Prerequisites**

- A computer with a modern web browser (Chrome, Firefox, Edge, etc.).
- Ability to run a local web server (instructions provided below).

### **Installation**

1. **Download the Game Files**

   - Clone or download the repository containing the `team_lunch_game.html` and `questions.md` files.
   - Alternatively, you can copy the code provided and save them into their respective files.

2. **Set Up Your Questions**

   - Open `questions.md` in a text editor.
   - Replace the existing questions and answers with your own, following the specified format.

     **Markdown Format Example:**

     ```
     What is the capital of France?
     - Berlin
     - London
     - Paris
     - Madrid

     Who painted the Mona Lisa?
     - Vincent Van Gogh
     - Pablo Picasso
     - Leonardo da Vinci
     - Claude Monet
     ```

3. **Run a Local Web Server**

   For the game to load the `questions.md` file, you need to serve the files via a local web server due to browser security restrictions.

   **Using Python 3:**

   ```bash
   python -m http.server 8000
   ```

   **Using Node.js:**

   ```bash
   npx http-server -p 8000
   ```

   **Using Live Server Extension (VS Code):**

   - Install the **Live Server** extension.
   - Open the folder containing the game files.
   - Right-click `team_lunch_game.html` and select **Open with Live Server**.

4. **Launch the Game**

   - Open your web browser and navigate to `http://localhost:8000/team_lunch_game.html`.

---

## 🎮 How to Play

1. **Start the Game**

   - The first question will display at the top of the screen.
   - Answers will move around dynamically.

2. **Control the Game**

   - **Freeze/Unfreeze Answers**: Press the **Space Bar** to freeze or unfreeze the moving answers.
   - **Navigate Questions**: Use the **Left Arrow** and **Right Arrow** keys to move between questions.

3. **Team Participation**

   - Select team representatives to participate.
   - Blindfold the participants and have them try to place a sticky note on the projected screen over the correct answer when the answers are frozen.
   - Enjoy the fun as they navigate the screen!

---

## 📖 Game Rules

- **Fair Play**: Participants should be blindfolded to ensure fairness.
- **One Try Per Turn**: Each participant gets one attempt per question.
- **Team Collaboration**: Teams can guide their representative verbally.
- **Scoring**: Keep track of correct answers to determine the winning team.

---

## 🛠 Customization

### **Adding Your Own Questions**

- Open `questions.md` and edit the content using the provided format.
- Ensure each question is followed by its answers, each starting with `- `.
- Leave an empty line between questions.

### **Adjusting Game Settings**

- **Answer Size**: Modify the `.answer` class in the CSS section of `team_lunch_game.html` to adjust font size and padding.
- **Answer Colors**: Change the colors in the `answerColors` array in the JavaScript section to customize answer block colors.
- **Fonts**: Replace the Google Fonts links with your preferred fonts and update the CSS `font-family` properties accordingly.

---

## 📷 Screenshot

<img width="1192" alt="image" src="https://github.com/user-attachments/assets/aa5f8f8c-81a4-445d-890d-021b3d115ec1">


---

## 🤝 Contributing

We welcome contributions to enhance the game! Feel free to submit pull requests with improvements, new features, or bug fixes.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 📞 Contact

For questions or support, please reach out to [your email/contact information].

---

## 🌟 Let's Play!

Gather your team, set up the game, and enjoy a memorable and laughter-filled team lunch activity. The Team Lunch Trivia Game is not just a game—it's an experience that brings people together. So, are you ready to test your knowledge and have some fun?

---

**Happy Gaming!**
