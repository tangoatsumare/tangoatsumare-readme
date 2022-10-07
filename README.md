# Tango Atsumare
<p align="center">
    <img src="assets/tango.png">
</p>

# Introduction

- Tango Atsumare helps users expand their vocabulary by making the process of creating high quality flashcards easier and more fun than ever before.
- You can use Tango Atsumare to review your new vocabulary using a spaced repetition flashcard review system, which contains an algorithm that allows users to spend less time studying, while improving retention.
- Tango Atsumare is also a community as newly created flashcards are added into a public feed.
    - Browse for new words at your leisure, adding them to your flashcard deck as you go.
    - Search for a new word you’ve recently encountered and find pictures that other users have uploaded containing that word.
    - See real world examples of those words in context.

## Media Links

- Video of our features:

[![Watch the video](assets/tango-video-thumbnail2.jpg)](https://www.youtube.com/watch?v=PSH1h7tCUjM)

# Features

### OCR to Flashcard

We wanted to create the OCR to Flashcard feature because in most cases it would take 2 or 3 apps just to recreate the process that we have streamlined in this one step. In order to retain visual context for the target vocabulary, in other applications you’d need to:

- Take a picture of the target vocabulary.
- Use an OCR to Text application to convert the image to text
- Extract both the sentence and the target vocabulary
- Search a dictionary for the meaning of the word
- Go back and forth filling out fields just to create a single entry into your flashcard app of choice
- Copy and paste the sentence, the target word, the meaning, and to retain as much context as possible, the original picture as well

### Picture Dictionary

A feed containing all recently uploaded pictures. Here you can see the pictures users have uploaded and the word they chose for their picture. On the feed you can:

- Scroll through and see what users have uploaded recently
- Click on an individual picture to get more details and upon clicking you can:
    - See more in-depth information on the card such as the full sentence, the chosen word, and the English meaning
    - Like the card
    - Add the card to your own collection
    - Report if the image is inappropriate
    - See tags that the original uploader has chosen for said card

### SRS Review

Short for “Spaced Repetition System” 

**Spaced repetition**
 is a flashcard based system for learning. Difficult flashcards are shown more frequently, while older and less difficult flashcards are shown less frequently. SRS’s have been proven to increase the rate of learning

## Future Features

- Initial tutorial for new users
- Localization for Japan
- Dark mode
- Public/private switch for user created flashcards
- Gamification - achievements/levels/progress bar/etc.

## How To Get It Running

Our app uses Google Firebase and Google Vision API on the frontend and mongoDB on the backend. Make sure you have accounts for each of these.

### Setting up the backend
- Clone the backend repository
-

### Setting up the frontend
- Clone the frontend repository
- Open the repo with VS Code
- Type ```npm install``` in the console to install all dependencies
- Create a ```.env``` file in the root directory with these required variables
    - ```
        GOOGLE_CLOUD_VISION_API_KEY=Your_cloud_vision_api_key
        FIREBASE_API_KEY=Your_firebase_vision_api_key
        FIREBASE_AUTH_DOMAIN=Your_firebase_auth_domain
        FIREBASE_PROJECT_ID=Your_firebase_project_id
        FIREBASE_STORAGE_BUCKET=Your_firebase_storage_bucket
        FIREBASE_MESSAGING_SENDER_ID=Your_firebase_sender_id
        FIREBASE_APP_ID=Your_firebase_app_id
- Type ```expo start``` in the console to run the app!

## Meet the Team

<img src="assets/Keith.png" width="200" height="200" alt="Keith">

[![Keith's GitHub](assets/GitHub-Mark-32px.png)](https://github.com/keithching)
Keith

<img src="assets/Graeme.png" width="200" height="200" alt="Graeme">

[![Graeme's GitHub](assets/GitHub-Mark-32px.png)](https://github.com/graememick)
Graeme 

<img src="assets/Kenny.png" width="200" height="200" alt="Kenny">

[![Kenny's GitHub](assets/GitHub-Mark-32px.png)](https://github.com/khiz125)
Kenny

<img src="assets/Dean.png" width="200" height="200" alt="Dean">

[![Dean's GitHub](assets/GitHub-Mark-32px.png)](https://github.com/gomizilla)
Dean

## Feedback and Questions

If you have any feedback or questions for us at Tango Atsumare, feel free to contact any of us and let us know!