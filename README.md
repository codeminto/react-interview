### **React Developer Interview Challenge**


#### **Objective:**
Build a real-time chat application using **React.js** for the frontend and **Firebase** for authentication and database, with **OpenAI API** integration for enhancing messages (e.g., sentiment analysis or automated replies). Additionally, implement **file and image upload** functionality.


### **Core Requirements with Screen Details**

#### **1. Authentication Screen**
- **Purpose:**
  - Allow users to sign up, log in, and log out using **Firebase Authentication**.

- **Features:**
  - Enable email/password-based signup and login.
  - Validate input fields (e.g., email format and password length).
  - Display error messages for failed authentication attempts.
  - Provide a "Sign Out" button for logged-in users.

- **UI Expectations:**
  - A clean form with input fields for email and password.
  - Buttons for "Login," "Sign Up," and "Logout."
  - Responsive design for desktop and mobile.

- **Resources:**
  - [Firebase Authentication Documentation](https://firebase.google.com/docs/auth)


#### **2. Chat Room Screen**
- **Purpose:**
  - Display a real-time chat interface where users can send and receive messages.

- **Features:**
  - Show a real-time list of chat messages fetched from **Firebase Firestore**.
  - Include an input box for users to type messages and send them.
  - Display sender information, timestamps, and content.
  - Automatically update the chat interface when new messages arrive.

- **UI Expectations:**
  - A vertically scrollable chat area.
  - Input field at the bottom with a "Send" button.
  - Messages styled differently for the sender and other users.

- **Resources:**
  - [Firestore Realtime Database Guide](https://firebase.google.com/docs/firestore/quickstart)

---

#### **3. OpenAI API Integration**
- **Purpose:**
  - Add intelligence to the chat by integrating the OpenAI API.

- **Features:**
  - When a user sends a message:
    - Send the message to the OpenAI API for analysis or reply generation.
    - Display the API-generated response in the chat.
  - Example Use Case:
    - Analyze the sentiment of the user's message and display a sentiment tag.
    - Generate an automated reply for user interaction.

- **UI Expectations:**
  - AI-generated messages appear in the chat with a unique style or label.
  - Sentiment tags (e.g., "Positive," "Neutral," "Negative") can be displayed below user messages.

- **Resources:**
  - [OpenAI API Documentation](https://platform.openai.com/docs/)


#### **4. File and Image Upload Screen**
- **Purpose:**
  - Allow users to upload files or images and share them in the chat.

- **Features:**
  - Include an "Upload" button next to the message input field.
  - Allow users to upload images or files directly to **Firebase Storage**.
  - Store file URLs in **Firestore** and display uploaded files/images in the chat interface.
  - Images:
    - Display inline in the chat.
  - Other files:
    - Provide a downloadable link.

- **UI Expectations:**
  - Add a file upload icon/button near the input box.
  - Show uploaded images directly in the chat.
  - Show file names with clickable download links for non-image files.

- **Resources:**
  - [Firebase Storage Documentation](https://firebase.google.com/docs/storage)

---

#### **5. Error and Loading States**
- **Purpose:**
  - Handle errors and display loading indicators.

- **Features:**
  - Show error messages for authentication issues, failed file uploads, or API errors.
  - Display a loading spinner during API calls, message sending, or file uploads.

- **UI Expectations:**
  - Use toast notifications or inline error messages.
  - Add spinners for asynchronous operations.

- **Resources:**
  - [React Error Boundaries](https://react.dev/reference/react/Component#catching-rendering-errors-with-an-error-boundary)

---

### **Deliverables**
1. Fully functional application with:
   - Authentication, real-time chat, OpenAI integration, and file upload features.
2. A **GitHub repository** with:
   - Source code.
   - A `README.md` file explaining setup and functionality.
3. A **hosted application** (e.g., Firebase Hosting, Vercel).

---

### **Evaluation Criteria**
1. **Functionality:** Does the app fulfill all core requirements?
2. **Code Quality:** Is the code clean, modular, and adheres to React best practices?
3. **UI/UX:** Is the interface intuitive and responsive?
4. **Integration:** How effectively Firebase and OpenAI API are integrated.
5. **Error Handling:** Are errors properly handled and communicated to the user?
6. **File Uploads:** Smooth and secure file upload and display functionality.

Good luck with the challenge! 🚀
