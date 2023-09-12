# Develop-a-text-based-quiz-game-where-users-can-answer-questions
questions = {
    "What is the capital of France?": "Paris",
    "Which planet is known as the Red Planet?": "Mars",
    "What is the largest mammal in the world?": "Blue whale",
}

score = 0

for question, answer in questions.items():
    user_answer = input(question + " ")
    if user_answer.lower() == answer.lower():
        print("Correct!")
        score += 1
    else:
        print("Incorrect. The correct answer is:", answer)

print("Your final score:", score)
