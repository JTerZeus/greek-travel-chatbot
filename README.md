# TravelBuddy - A Greek Travel Chatbot

TravelBuddy is a simple, pattern-matching chatbot written in Python that engages in travel-related conversations in Greek. It can recognize user intent related to destinations, budget, travel style, and past experiences to provide relevant and engaging responses.

---

## Features

*   **Pattern-Based Recognition**: Uses regular expressions to identify user intent across 10 different patterns.
*   **Conversational Topics**: Can discuss:
    *   Desired travel destinations
    *   Past travel experiences
    *   Budget constraints
    *   Preferred travel season and duration
    *   Vacation styles (beach, mountain, city life)
    *   Food preferences
*   **Dynamic Responses**: Provides a variety of randomized responses for each recognized pattern to make the conversation feel more natural.
*   **Default Fallbacks**: When user input doesn't match any pattern, it gives a generic, engaging reply to keep the conversation going.
*   **Helpful Travel Tips**: Offers random travel tips upon request or at the end of a conversation.
*   **Greek Language**: The entire interaction is designed for Greek-speaking users.

## Technical Details

*   **Language**: Python 3
*   **Core Logic**: The chatbot is built around the `re` module for regular expression matching, inspired by the classic "ELIZA" chatbot architecture.
*   **Dependencies**: The only dependency is the `random` module, which is part of the Python standard library. No external packages are needed.

## How to Run

1.  Make sure you have Python 3 installed.
2.  Save the code as a Python file (e.g., `Travel_Buddy.py`).
3.  Run the script from your terminal:
    ```bash
    python Travel_Buddy.py
    ```
4.  Start chatting with your Travel Buddy! Type `αντίο` to end the session.

---

### University Project Context

This chatbot was created for the "Theory of Computation" course at the **University of Macedonia**. The goal was to create an ELIZA-style chatbot focused on a specific domain (travel) by implementing a system of pattern-recognition rules.
