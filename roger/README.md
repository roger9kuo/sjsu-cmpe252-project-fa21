# Intro

Domain: Personal Assistant

Use Case: Scheduling Appointments/Events

Note: The chat bot is only capable of handling one event in this iteration.

---

# Setup & Instructions to Run

## Project Environment
- Windows 10
- Python 3.8.1

## Steps

Run venv first
- Command Prompt:
  - > .\venv\Scripts\activate
- Bash: 
  - > source .\venv\Scripts\activate

Create training models before running/testing
- > rasa train

Run the server
- > rasa run actions

In a separate(second) shell, run the program
- > rasa shell

---

# Sample Conversational Flows

You can enter/test the following:
- Hello
  - What is your name?
  - How is the weather?
  - What do you do?

- Hello
  - Can you help me schedule an event?
    - Dental Appointment
    - October 13, 1964
    - 11:56 PM
    - Yes
  - Check my schedule.
  - Help me edit my task.
    - Birthday Party
    - 28 June 1839
    - 3:26 AM
    - Yes
  - What is my task?

---

# Guides

https://rasa.com/docs/rasa/playground

https://rasa.com/docs/rasa/command-line-interface
