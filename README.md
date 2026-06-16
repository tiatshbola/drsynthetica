# Dr Synthetica (Syntribot)

An interactive webcam-based art piece built with **p5.js** and **ml5.js**.

Dr Synthetica uses a Teachable Machine image-classification model to interpret facial expressions captured through a webcam, then initiates a simulated therapy session that adapts its questioning based on the detected emotional state.

The project explores the limitations of emotion-recognition AI and the tendency of humans to project understanding, empathy, and authority onto computational systems.

---

## Features

* Real-time webcam emotion classification
* Teachable Machine image model integration
* Branching conversation paths based on detected emotion
* Interactive text-based "therapy session"
* Conversation transcript log
* Restart functionality
* Browser-based experience with no build process required

---

## Technologies Used

* p5.js
* ml5.js
* Teachable Machine
* HTML
* CSS
* JavaScript

---

## How It Works

1. The application starts the user's webcam and loads a Teachable Machine image-classification model.
2. A short analysis period allows the model to classify the user's facial expression.
3. Based on the detected emotion, Dr Synthetica selects a corresponding bank of questions.
4. The user responds to each question through a text input.
5. The conversation progresses until the selected question sequence is complete.

### Emotion Model

The project uses the following Teachable Machine model:

`https://teachablemachine.withgoogle.com/models/HmMegiSBC/`

---

When prompted, allow camera access in your browser.

---

## Project Structure

| File                 | Description                                        |
| -------------------- | -------------------------------------------------- |
| `index.html`         | Main page markup and library imports               |
| `sketch.js`          | Current project implementation                     |
| `sketch.original.js` | Original prototype version preserved for reference |
| `script.js`          | Additional page functionality                      |
| `style (1).css`      | Project styling                                    |

---

## Project Evolution

The project exists in two versions:

### Current Version

`sketch.js`

Features include:

* HTML-based interface
* Conversation transcript
* Timed facial-expression analysis
* Restart functionality
* Improved interaction flow

### Original Prototype

`p5.js`

The original version:

* Drew interface elements directly onto the canvas
* Used a single p5.js input box
* Served as the initial proof of concept

---

## Conceptual Framework

Dr Synthetica investigates how humans interact with systems that claim to interpret emotion.

By reducing emotional understanding to a simple classification model and pairing it with therapeutic questioning, the project highlights the assumptions, limitations, and biases embedded within emotion-recognition technologies.

The work draws inspiration from early conversational systems such as ELIZA while examining contemporary claims surrounding artificial intelligence and emotional intelligence.

---

## Development Notes

AI tools were used during development for debugging, code assistance, and interface implementation support.

The project concept, artistic direction, interaction design, research, and written content are the author's own.

---

## Author

**Tia Tshabola**

Creative Technologist, Engineer, and Artist exploring the intersection of emerging technologies, culture, identity, and human-computer interaction.
