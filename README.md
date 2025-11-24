
# 📌Quote Generator
A simple web application that fetches and displays a new inspirational quote every time you click the New Quote button. It also allows users to tweet the quote directly with one click.
## 🌟Features
* Fetches real-time quotes from ZenQuotes API
* Displays both quote text and author
* Clean UI with smooth styling
* "Tweet" button to directly share the quote on Twitter
* Responsive design using HTML, CSS, and vanilla JavaScript
* Error handling for API failures

## 📡API Used
The project fetches quotes using:
```
https://api.allorigins.win/raw?url=https://zenquotes.io/api/random
```
## ➕Dynamic Content Rendering
The following elements update dynamically:
```
<blockquote> → Quote text
<span> → Author name
```
Users see the new quote instantly on button click.

## 🛑Error Handling
If the API fails or responds slowly:
* A fallback message appears
* Errors are logged in the console
This ensures the app doesn’t break unexpectedly.

## ✨Result

<img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/a7c3c71b-b89a-4efb-aa94-a07364caef32" />

## 🪜Additional Information
* When we click 'New Quote', the API may take time to generate a new quote due to traffic.
* When we click 'Tweet', it will open into your twitter account, or ask you to login/signup for it.

## ✨Animation


https://github.com/user-attachments/assets/54c45f7b-2980-4135-8beb-2e41e3adf41c


