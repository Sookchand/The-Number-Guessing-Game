
#  Guess The Number {Python Game}
This Python code is a number guessing game. Here's a breakdown of its functionality:

1. **Import Statements:** The code begins by importing the `random` module, which is used to generate random numbers, and a `logo` from a module named `num_logo`.

2. **Constant Variables:** Two constant variables `EASY_LEVEL_TURNS` and `HARD_LEVEL_TURNS` are defined, representing the number of turns for easy and hard difficulty levels, respectively.

3. **Function Definitions:** The code defines several functions:
   - `check_answer(guess, answer, turns)`: This function checks if the user's guess is higher or lower than the actual number. If the guess is incorrect, it reduces the number of turns by 1 and returns the updated number of turns.
   - `set_difficulty()`: This function asks the user to choose a difficulty level and returns the corresponding number of turns.
   - `game()`: This is the main function that runs the game. It first prints a welcome message and generates a random number between 1 and 100. Then it calls `set_difficulty()` to determine the number of turns. It enters a loop where it repeatedly asks the user to guess the number until they guess correctly or run out of turns.

4. **Game Execution:** Finally, the `game()` function is called to start the game.

The game continues to prompt the user for guesses until they either guess correctly or exhaust their allotted turns based on the difficulty level they chose at the beginning of the game. If they guess correctly, they win; if they run out of turns, they lose.
#  Acknowledgements
I would like to thank Dr. Angela Yu.
## Authors

- [@Sookchand](https://github.com/Sookchand)


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Tech Stack
This game is a simple number guessing game written in Python. Here are the technologies used:

1. **Python:** This is the programming language in which the game is written. Python is a high-level, interpreted language known for its easy readability and vast library support.

2. **Python's `random` module:** This module is used to generate random numbers in Python. In this game, it's used to generate the number that the user has to guess.

3. **Python's `input` function:** This built-in function is used to get input from the user. In this game, it's used to get the user's guess and their chosen difficulty level.

4. **Python functions:** Functions are a fundamental concept in Python (and most programming languages), allowing for code reuse and modularization. In this game, different aspects of the game logic are encapsulated in different functions.

5. **Python's `print` function:** This built-in function is used to output text to the console. In this game, it's used to display messages to the user, such as telling them whether their guess was too high or too low.

6. **Imported `logo` from `num_logo` module:** The `logo` is likely a string of characters arranged to form a picture or design, which is printed to the console at the start of the game for a bit of added flair.

Please note that this game runs on a console and doesn't require any additional technologies or libraries beyond a basic Python environment.
## Documentation
Sure, here are the official documentation resources for the technologies used in the game:

1. **Python:** Python's official documentation is comprehensive, covering everything from beginner's guides to advanced topics. You can find it on the [Python.org website](^17^) or [docs.python.org](^18^).

2. **Python's `random` module:** This module is used for generating random numbers. You can find its official documentation on the [Python.org website](^1^).

3. **Python's `input` function:** This built-in function is used to get input from the user. Its official documentation can be found in the [Python 3.11.5 documentation](^10^) and [Built-in Functions — Python 3.11.5 documentation](^6^).

4. **Python functions:** Functions are a fundamental concept in Python, allowing for code reuse and modularization. You can learn more about them in the [Built-in Functions — Python 3.11.5 documentation](^6^).

5. **Python's `print` function:** This built-in function is used to output text to the console. Its official documentation can be found in the [Built-in Functions — Python 3.11.5 documentation](^6^).

Remember, Python's official documentation is a great resource, but there are also many other tutorials and guides available online that can help you understand these concepts better.

Source: Conversation with Bing, 9/29/2023
(1) Our Documentation | Python.org. https://www.python.org/doc/.
(2) Python 3.11.5 documentation. https://docs.python.org/.
(3) random — Generate pseudo-random numbers — Python 3.11.5 documentation. https://docs.python.org/3/library/random.html.
(4) 7. Input and Output — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/inputoutput.html.
(5) Built-in Functions — Python 3.11.5 documentation. https://docs.python.org/3/library/functions.html.
(6) Built-in Functions — Python 3.11.5 documentation. https://docs.python.org/3/library/functions.html.
(7) Built-in Functions — Python 3.11.5 documentation. https://docs.python.org/3/library/functions.html.
(8) Python Random Module - W3Schools. https://www.w3schools.com/python/module_random.asp.
(9) random – generate random numbers — MicroPython latest documentation. https://docs.micropython.org/en/latest/library/random.html.
(10) Python Random Module: Generate Random Numbers and Data - PYnative. https://pynative.com/python/random/.
(11) Lecture 4 - CS50's Introduction to Programming with Python. https://cs50.harvard.edu/python/2022/notes/4/.
(12) Documenting Python Code: A Complete Guide – Real Python. https://realpython.com/documenting-python-code/.
(13) How to Document Functions in Python - codingem.com. https://www.codingem.com/python-how-to-document-functions/.
(14) Functional Programming HOWTO — Python 3.11.5 documentation. https://docs.python.org/3/howto/functional.html.
(15) How to print your function's documentation python. https://stackoverflow.com/questions/34277363/how-to-print-your-functions-documentation-python.
(16) How to print module documentation in Python - Stack Overflow. https://stackoverflow.com/questions/13054970/how-to-print-module-documentation-in-python.
(17) How to print Docstring of python function from inside the function .... https://stackoverflow.com/questions/8822701/how-to-print-docstring-of-python-function-from-inside-the-function-itself.
(18) A Complete Guide to User Input in Python | by Chaitanya Baweja .... https://towardsdatascience.com/a-complete-guide-to-user-input-in-python-727561fc16e1.
(19) Python input() - Programiz. https://www.programiz.com/python-programming/methods/built-in/input.
(20) Basic Input, Output, and String Formatting in Python. https://realpython.com/python-input-output/.
(21) Python Developer's Guide | Python.org. https://www.python.org/dev/.
(22) The Python Language Reference — Python 3.11.5 documentation. https://docs.python.org/3/reference/index.html.
(23) undefined. https://devguide.python.org/.
## Lessons Learned
Building a number guessing game in Python like this can provide several valuable lessons:

1. **Understanding Python Basics:** This project helps reinforce understanding of Python basics such as variables, functions, loops, and conditionals.

2. **Modular Programming:** The use of functions to encapsulate different parts of the game (like checking the answer and setting the difficulty level) demonstrates the concept of modular programming. This is a key software design principle where a program is divided into separate modules, each performing a specific task.

3. **User Interaction:** The game involves user interaction, which can help you understand how to take user input and provide appropriate output based on that input.

4. **Use of Python Libraries:** The use of Python's `random` module demonstrates how to leverage Python's extensive standard library to add functionality to your programs.

5. **Debugging and Testing:** Building a game like this can also improve debugging and testing skills. You'll need to test the game thoroughly to ensure it works as expected and debug any issues that arise.

6. **Problem Solving:** Finally, creating a game like this involves problem-solving skills. You need to figure out how to translate the rules of the game into code, handle different user inputs, and ensure the game runs smoothly.

The best way to learn programming is by doing. So, building projects like this is a great way to reinforce what you've learned and gain new skills.
# Hi, I'm Sookchand! 👋

Strive to improve with each passing moment, surpassing the person I was in the previous minute, the previous hour, and even the person you were yesterday.
## 🚀 About Me
I have experience as a data scientist and machine learning engineer. I have worked on projects involving the development of predictive models, the optimization of machine learning algorithms, and the deployment of machine learning models. I have also worked on projects involving the analysis of large datasets, the development of data-driven insights, and the creation of data visualizations.
## 🛠 Skills
I possess a wide range of skills including:

- **Data Analysis**: Proficient in Data Exploration and Visualization, Model Evaluation and Analysis, and Regression Analysis.
- **Machine Learning**: Experienced in Neural Network and Deep Learning, Supervised Learning (including Classification, Regression, and Time Series), Decision Trees and Random Forests, Ensemble Learning, and Hyperparameter Tuning.
- **Libraries and Frameworks**: Skilled in using TensorFlow 2.0, NumPy, Scikit Learn, Keras, Pandas, React.js, Node.js, Express.js with Node.js.
- **Big Data Technologies**: Familiar with Hadoop, Apache Spark, Kafka, and Apache Flink.
- **Image Processing**: Capable of performing Image Recognition and Classification, and Transfer Learning.
- **Programming Languages**: Proficient in Python and R. Also have experience with HTML, CSS, JavaScript ES6, DOM, JQuery.
- **Database Management**: Knowledgeable in SQL and MongoDB along with Mongoose.
- **Web Development**: Experienced in HTML, CSS, Bootstrap 4, JavaScript ES6, DOM, JQuery.
- **Version Control Systems**: Comfortable with Git, GitHub.
- **Data Visualization Tools**: Proficient in Tableau and Power BI.
- **Authentication and Security**: Familiar with various authentication and security protocols.
- **Other Skills**: Comfortable working with GPU on Google Collab. Familiar with Unix Command-Line.

This diverse skill set allows me to tackle a variety of data science and web development projects.