<div align="center">
    <a href="https://cairtext.com"><h1 align="center">cairrier.com</h1></a>

cairrier.com, built with [Node.js](https://nodejs.org/en/), [Firebase Firestore](https://firebase.google.com/docs/firestore), [Twilio](https://www.twilio.com/en-us), and deployed to [Firebase Hosting](https://firebase.google.com/docs/hosting).

Originally Founded @ 2019.
Kickstarted @ 2023 with the rise of LLMs
</div>

<br/>
<h2>Because we cair.</h2>


cairrier is a HIPAA compliant semi-automated two way messaging system designed for healthcare providers and powered by artificial intelligence.

Our algorithm is a semi-automated two way messaging system designed for health care workers. Our platform implements deep learning to optimize communication with patients. We believe a messaging platform should be trustworthy, intuitive, confidential, and easily customizable to meet the specific needs of your practice.

## Running Locally


```sh-session
git clone https://github.com/caslabs/cAIrrier/
cd cAIrrier
```

### Software Requirements



Create a `.env` file for APIs requirements
```sh-session
FIREBASE_API_KEY=...
TWILIO_API=KEY...
```

Then install dependencies and run the development server:
```sh-session
npm install
npm dev
```
