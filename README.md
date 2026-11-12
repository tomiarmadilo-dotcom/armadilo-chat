# Armadilo Chat

**Armadilo Chat** is a lightweight, decentralized, and privacy-first web-based chat application. Built entirely on client-side technologies, it allows you to communicate directly with your peers without relying on a centralized chat server. 

Whether you are looking for a quick way to share updates or a private space to chat away from mainstream platforms, Armadilo Chat provides a seamless, real-time experience straight from your browser.

## ✨ Key Features

*   **No Third-Party Sign-In Required:** Skip the hassle of linking your phone number or signing in with Google, Facebook, or other external accounts. Just create a simple local username and you are ready to chat. Your privacy is entirely in your hands.
*   **Peer-to-Peer Communication:** Powered by WebRTC (via PeerJS), messages are sent directly between users, minimizing third-party data exposure.
*   **Account & Session Security:** User passwords are securely hashed using PBKDF2 with SHA-256 and salt, ensuring your local credentials remain safe.
*   **Custom Invite Codes:** Create your own easy-to-remember invite codes (e.g., `bayiberuangmadu`). No complex numbers to memorize.
*   **Real-time Message Management:** Edit or delete messages even after they are sent (within a 15-minute window). 
*   **Privacy Controls:** Hide contacts from your main list whenever you want, and easily find them again using the built-in search feature when you want to reconnect.
*   **Smart Storage Management:** Built-in alerts notify you when local storage is reaching its limit, with options to clear chat history to maintain optimal performance.
*   **Modern UI:** A clean, responsive, and elegant interface with automatic dark mode support based on your system preferences.

## 🛠️ Technology Stack

*   **HTML5 & CSS3:** For a responsive and modern user interface.
*   **Vanilla JavaScript:** Core logic and state management.
*   **PeerJS (WebRTC):** For real-time, peer-to-peer data transmission.
*   **Web Crypto API:** For secure password hashing (PBKDF2).
*   **Local Storage:** For zero-configuration, local data persistence.

## 🚀 How to Use

1.  **Access the App:** Open Armadilo Chat in your web browser. No installation, no Google account needed.
2.  **Create an Account:** Register with a unique username, a secure password, and your preferred invite code.
3.  **Connect:** Share your invite code with a friend, or enter their code to start a conversation.
4.  **Chat Securely:** Enjoy real-time, direct messaging!

## ⚠️ Disclaimer

Armadilo Chat is a decentralized application. While it uses secure hashing for local accounts, message history and contacts are stored locally on your device using `localStorage`. It is not recommended to store highly sensitive information, as data is tied to the browser and device you are currently using.
