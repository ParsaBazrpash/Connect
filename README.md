## 💡 Inspiration
One of our team members attended an American Sign Language (ASL) meeting on campus and realized how challenging it can be for the deaf and hard-of-hearing community to communicate in real-time. That experience sparked an idea:

What if we could make communication more seamless and inclusive through technology?

So, a group of friends came together to build Connect — a real-time video calling app designed to bridge the gap between hearing and non-hearing individuals. We believe communication should be a right, not a privilege. 💙

## 📱 What it does
Connect is a web-based video chatting platform that enables deaf and hearing people to communicate more effectively. It features:

- 👋 **Sign Language to Text:** On one end, the app uses a machine learning model to recognize sign language gestures and convert them into text in real-time.
- 🗣️ **Speech to Text:** On the other end, spoken words are transcribed into text instantly, ensuring the conversation flows both ways.

Our goal is to support inclusive communication and reduce barriers between people.

## 🛠️ How we built it
We used a combination of tools and technologies:

- **Frontend:** Typescript (Next.js) for the user interface - TailwindCSS for Styling
- **Video Communication:** WebRTC for real-time video calling
- **Backend:** Flask API to serve our machine learning model
- **ML Model:** A custom-built LSTM sign language recognition computer vision model trained using hand sign gestures.
- **Database & Authentication:** Firestore and Firebase Authentication
- **Firebase:** Used for signaling in WebRTC to establish peer-to-peer connections

## 🚧 Challenges we ran into
We faced several technical challenges while building Connect:

- 🔧 Setting up real-time video calls using WebRTC. We had to understand concepts like signaling servers, ICE candidates, and session description protocols (SDPs).
- 🤖 Integrating the machine learning model into the backend and making real-time predictions available to the frontend.
- 🔗 Ensuring smooth communication between frontend, backend, and ML components using Flask and .pkl model files.
- 🔄 Syncing video streams with live transcriptions in both directions.

We tackled these challenges by watching tutorials, reading documentation, and lots of trial and error!

## 🏆 Accomplishments that we're proud of
- 🔴 Successfully setting up live video chatting between users
- ✋ Building and integrating our own sign-to-text ML model
- 🔊 Combining speech-to-text and sign-to-text features in one app
- 🤝 Creating a product that makes a real difference in communication accessibility

## 📚 What we learned
- How to build and deploy a Flask API that serves machine learning predictions
- The inner workings of WebRTC, including peer connections and media streaming
- How to train a custom ML model and connect it to a frontend
- The importance of building apps that prioritize inclusion and accessibility

## 🚀 What's next for Connect
- 🧠 Improving the accuracy and speed of the sign recognition model
- 🌐 Supporting more sign languages (e.g., BSL, ISL)
- 📲 Making a mobile version for broader accessibility
- 🗨️ Adding text-to-speech for full bidirectional communication
- 🔐 Ensuring user privacy and adding authentication

We hope to keep building Connect into a tool that empowers and unites people through the power of technology. 🌍
