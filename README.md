<h1 align="center">📸 Instaclone</h1>

<p align="center">
  <b>An Instagram-inspired social media application built with React.js and Firebase</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-17-blue" />
  <img src="https://img.shields.io/badge/Firebase-Backend-orange" />
</p>

<hr />

<h2>📖 About</h2>
<p>
Instaclone is a modern social media platform that allows users to create profiles,
share content, interact with others, and chat in real time.
The project focuses on clean UI, real-world features, and scalable frontend architecture.
</p>

<hr />

<h2>✨ Features</h2>

<h3>🔐 Authentication</h3>
<ul>
  <li>Email & Password login</li>
  <li>Google, Twitter & GitHub sign-in</li>
  <li>Password recovery</li>
  <li>Public / Private accounts</li>
</ul>

<h3>👤 User Profiles</h3>
<ul>
  <li>Profile photo and bio</li>
  <li>Follow / Unfollow users</li>
  <li>Followers & Following lists</li>
  <li>Online / Offline status</li>
  <li>Block & Unblock users</li>
</ul>

<h3>📝 Content Creation</h3>
<ul>
  <li>Image posts (crop & filters)</li>
  <li>Video uploads</li>
  <li>Audio sharing</li>
  <li>Text posts & polls</li>
  <li>YouTube video embeds</li>
  <li>Short video reels</li>
</ul>

<h3>❤️ Social Interaction</h3>
<ul>
  <li>Like & dislike posts</li>
  <li>Comments & replies</li>
  <li>Emoji reactions</li>
  <li>Save & share posts</li>
</ul>

<h3>💬 Real-Time Messaging</h3>
<ul>
  <li>One-to-one chat</li>
  <li>Media sharing</li>
  <li>Typing indicators</li>
  <li>Delete / unsend messages</li>
</ul>

<hr />

<h2>🛠 Tech Stack</h2>

<ul>
  <li><b>Frontend:</b> React.js, Redux, Context API, SCSS</li>
  <li><b>Backend:</b> Firebase Authentication, Realtime Database</li>
  <li><b>Storage:</b> Firebase Cloud Storage</li>
  <li><b>UI:</b> Material-UI, Bootstrap</li>
  <li><b>Testing:</b> Cypress, Jest</li>
</ul>

<hr />

<h2>🚀 Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
  <li>Node.js (v12+)</li>
  <li>npm or yarn</li>
  <li>Firebase account</li>
</ul>

<h3>Installation</h3>

<pre>
npm install
npm start
</pre>

<p>The application will run on <b>http://localhost:3000</b></p>

<hr />

<h2>⚙️ Firebase Setup</h2>

<p>
Create a Firebase project and enable Authentication, Realtime Database, and Storage.
Add your Firebase configuration inside:
</p>

<pre>
src/Config/firebase-config.js
</pre>

<p><b>⚠️ Never commit your API keys publicly.</b></p>

<hr />

<h2>📁 Project Structure</h2>

<pre>
instagram-clone-master/
├── public/
├── src/
│   ├── Components/
│   ├── Pages/
│   ├── Redux/
│   ├── Context/
│   ├── Config/
│   └── Styles/
├── cypress/
└── README.md
</pre>

<hr />

<h2>🚀 Deployment</h2>

<h3>Firebase Hosting</h3>
<pre>
npm run build
firebase deploy
</pre>

<h3>Netlify</h3>
<p>Upload the <code>build</code> folder to Netlify (netlify.toml is preconfigured).</p>

<hr />



<hr />

<h2>🙌 Acknowledgements</h2>
<ul>
  <li>React & Create React App</li>
  <li>Firebase</li>
  <li>Material-UI</li>
  <li>Open-source community</li>
</ul>

<p align="center">
  ⭐ If you like this project, consider giving it a star!
</p>
