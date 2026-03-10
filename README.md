# 🤖 Voiceflow AI Healthcare Chatbot

A simple project that demonstrates how to integrate a **Voiceflow AI chatbot widget** into a website using HTML and JavaScript.

This chatbot helps users interact with an **AI-powered healthcare assistant** directly from the website.

---

## 🌐 Live Project

🔗 **Project Link:**
https://healthcarebot.ccbp.tech/

---

## 📌 Features

* AI Healthcare Chatbot
* Voiceflow chatbot integration
* Real-time user interaction
* Simple HTML & JavaScript implementation
* Lightweight chatbot widget
* Easy website deployment

---

## 📂 Project Structure

```
voiceflow-healthcare-chatbot
│
├── index.html
└── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/voiceflow-healthcare-chatbot.git
```

### 2️⃣ Open the Project

Open the folder in **VS Code** or any code editor.

### 3️⃣ Run the Project

Open the `index.html` file in your browser.

---

## 💻 Chatbot Integration Code

Add the following script to your HTML file:

```html
<!DOCTYPE html>
<html>

<head>
</head>

<body>

<script type="text/javascript">
(function(d, t) {
    var v = d.createElement(t),
        s = d.getElementsByTagName(t)[0];
    v.onload = function() {
        window.voiceflow.chat.load({
            verify: {
                projectID: '69ae8a9cbffdab9af8208069'
            },
            url: 'https://general-runtime.voiceflow.com',
            versionID: 'production',
            voice: {
                url: "https://runtime-api.voiceflow.com"
            }
        });
    }
    v.src = "https://cdn.voiceflow.com/widget-next/bundle.mjs";
    v.type = "text/javascript";
    s.parentNode.insertBefore(v, s);
})(document, 'script');
</script>

</body>

</html>
```

---

## ⚙️ Configuration

Replace the **projectID** with your Voiceflow project ID.

Example:

```
projectID: 'YOUR_PROJECT_ID'
```

You can find it in your **Voiceflow project settings**.

---

## 🧠 Use Cases

* Healthcare Assistance Chatbot
* Patient Support System
* Clinic Appointment Chatbot
* Medical Information Assistant
* AI Customer Support

---

## 🛠 Technologies Used

* HTML5
* JavaScript
* Voiceflow AI Platform

---

## 👨‍💻 Author

**Durga Prasad Mokara**

AI Automation Developer
Building AI Chatbots, AI Agents, and Automation Systems.

---

⭐ If you like this project, please **star the repository**.
