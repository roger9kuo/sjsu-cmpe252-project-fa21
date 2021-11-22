# Intro

Domain: Personal Assistant

Use Case: Message management

---

# Setup & Instructions to Run

## Project Environment
- Windows 10
- Python 3.8.1
- Rasa

## Steps

Activate rasa environment

Create training models
- > rasa train

Talk to the bot
- > rasa shell

---

# Sample Conversational Flows

- Chitchats
  - Hello
  - How is the weather?
  - How are you?
  - Thank you
- Ask bot to self introduce
  - What can you do for me?
  - How can you help me?(Follow up)
- Checking message
  - Do I have new messages?
  - Read it for me(Follow up)
  - Yes("No" will end the conversation)
  - I would love to come
- send message
  - I want to send a message
  - Tell Bob that I might be late(Follow up)
- misc function
  - redo
  - Mark the messages as read
  - remove notifications
  - turn on/off notifications
  - turn on/off don't disturb mode

---

# Guides

https://rasa.com/docs/rasa/playground

https://rasa.com/docs/rasa/command-line-interface
