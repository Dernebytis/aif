# aif
DSDdfd
# Simple Artificial Intelligence Example
import random

class SimpleAI:
    def __init__(self):
        self.responses = [
        "Hello! How can I assist you?",
        "I'm here to help. What do you need?",
        "Greetings! What can I do for you today?"
        ]

    def generate_response(self):
        return random.choice(self.responses)

# Example usage
ai = SimpleAI()
response = ai.generate_response()
print(response)
