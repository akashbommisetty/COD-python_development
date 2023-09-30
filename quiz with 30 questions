# python_development
import random
questions = [
    {"question": "What is the capital of France?", "answer": "Paris"},
    {"question": "Which planet is known as the 'Red Planet'?", "answer": "Mars"},
    {"question": "What is the largest mammal in the world?", "answer": "Blue Whale"},
    {"question": "Who wrote the play 'Romeo and Juliet'?", "answer": "William Shakespeare"},
    {"question": "What gas do plants absorb from the atmosphere?", "answer": "Carbon dioxide"},
    {"question": "What is the chemical symbol for the element gold?", "answer": "Au"},
    {"question": "What is the tallest mountain in the world?", "answer": "Mount Everest"},
    {"question": "Which gas do humans breathe out when they exhale?", "answer": "Carbon dioxide"},
    {"question": "What is the currency of Japan?", "answer": "Japanese Yen"},
    {"question": "Which gas makes up the majority of Earth's atmosphere?", "answer": "Nitrogen"},
    {"question": "What is the largest organ in the human body?", "answer": "Skin"},
    {"question": "In which country is the Great Barrier Reef located?", "answer": "Australia"},
    {"question": "What is the capital of Canada?", "answer": "Ottawa"},
    {"question": "Who painted the Mona Lisa?", "answer": "Leonardo da Vinci"},
    {"question": "What is the freezing point of water in degrees Fahrenheit?", "answer": "32°F"},
    {"question": "What is the chemical symbol for water?", "answer": "H2O"},
    {"question": "What is the primary language spoken in Brazil?", "answer": "Portuguese"},
    {"question": "Who is known as the 'Father of Modern Physics'?", "answer": "Albert Einstein"},
    {"question": "Which gas is responsible for the Earth's ozone layer?", "answer": "Ozone (O3)"},
    {"question": "What is the largest desert in the world?", "answer": "Antarctica (Ice Desert)"},
    {"question": "Which planet is known as the 'Morning Star'?", "answer": "Venus"},
    {"question": "What is the chemical symbol for oxygen?", "answer": "O2"},
    # Define a list of 30 questions and their corresponding answers.
    {"question": "What is the largest planet in our solar system?", "answer": "Jupiter"},
    {"question": "Who wrote 'Pride and Prejudice'?", "answer": "Jane Austen"},
    {"question": "What is the smallest prime number?", "answer": "2"},
    {"question": "Which gas do plants release during photosynthesis?", "answer": "Oxygen"},
    {"question": "What is the chemical symbol for silver?", "answer": "Ag"},
    {"question": "Which country is known as the Land of the Rising Sun?", "answer": "Japan"},
    {"question": "What is the SI unit for measuring temperature?", "answer": "Kelvin"},
    {"question": "What is the currency of Russia?", "answer": "Russian Ruble"},
    {"question": "What is the rarest blood type among humans?", "answer": "AB Negative"},
    {"question": "What is the world's second-largest ocean?", "answer": "Atlantic Ocean"},
    {"question": "Which gas is responsible for the greenhouse effect on Earth?", "answer": "Carbon dioxide"},
    {"question": "What is the chemical symbol for iron?", "answer": "Fe"},
    {"question": "Who wrote 'The Catcher in the Rye'?", "answer": "J.D. Salinger"},
    {"question": "What is the largest continent by land area?", "answer": "Asia"},
    {"question": "What is the main component of Earth's core?", "answer": "Iron"},
    {"question": "In which city is the famous statue of Christ the Redeemer located?", "answer": "Rio de Janeiro"},
    {"question": "What is the most widely spoken language in the world?", "answer": "Mandarin Chinese"},
    {"question": "Who discovered the law of gravity?", "answer": "Isaac Newton"},
    {"question": "What is the chemical symbol for hydrogen?", "answer": "H"},
    {"question": "What is the main gas in Earth's atmosphere?", "answer": "Nitrogen"},
    ]
def get_random_question():
    return random.choice(questions)
def play_quiz():
    score = 0
    num_questions = 5  # Change this to the number of questions you want in each quiz.

    print("Welcome to the Quiz!")
    
    for _ in range(num_questions):
        question = get_random_question()
        print("\nQuestion:", question["question"])
        user_answer = input("Your answer: ")

        if user_answer.lower() == question["answer"].lower():
            print("Correct!\n")
            score += 1
        else:
            print(f"Wrong! The correct answer is: {question['answer']}\n")

    print(f"Quiz completed! Your score: {score}/{num_questions}")
if _name_ == "__main__":
    play_quiz()
