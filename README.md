# 💬 Real-time Chat Application

A real-time chat application built using Spring Boot for the backend and HTML, CSS, JavaScript for the frontend. This project demonstrates WebSocket-based real-time communication between users.

🚀 **Features**

* ✅ Real-time Messaging using WebSockets
* ✅ User-friendly Interface with HTML, CSS, and JavaScript
* ✅ Spring Boot Backend for handling connections and messages
* ✅ WebSocket Protocol for efficient message transfer
* ✅ Multi-user Chat Support

🛠️ **Tech Stack**

* **Backend:**
    * ☕ Java (Spring Boot 3.x)
    * 🔗 WebSockets (Spring Boot Starter WebSocket)
    * ✨ Lombok for reducing boilerplate code
* **Frontend:**
    * 🎨 HTML5, CSS3
    * ⚡ JavaScript (Vanilla JS / jQuery)

📌 **Installation Guide**

**📋 Prerequisites:**

* 🖥️ Java 17 or higher (recommended)
* 🏗️ Maven
* 🛠️ An IDE (IntelliJ IDEA, VS Code, Eclipse, etc.)

**🔧 Steps to Run Locally:**

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/chat-application.git](https://github.com/your-username/chat-application.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd chat-application
    ```
3.  **Build and run the application using Maven:**
    ```bash
    mvn clean install
    mvn spring-boot:run
    ```
4.  **Access the application:**
    Open your browser and go to: `http://localhost:8080`

📂 **Project Structure**

chat-application/
├── src/
│   ├── main/
│   │   ├── java/com/alibou/chat/
│   │   │   ├── config/          # ⚙️ WebSocket Configurations
│   │   │   ├── controller/      # 🎮 Chat Controller
│   │   │   ├── model/           # 📜 Message Model
│   │   │   ├── service/         # 🛠 Business Logic
│   ├── resources/
│   │   ├── static/
│   │   │   ├── css/             # 🎨 Stylesheets
│   │   │   ├── js/              # ⚡ JavaScript Files
│   │   │   ├── index.html       # 🏠 Chat UI
│   │   ├── application.yml      # ⚙️ App Configuration
├── pom.xml                      # 📌 Maven Dependencies


🔗 **WebSocket API Endpoints**

| Endpoint      | Method | Description                                      |
| :------------ | :----- | :----------------------------------------------- |
| `/chat`       | `GET`  | Main chat page                                   |
| `/ws`         | `WebSocket` | WebSocket connection for real-time messaging |

🏗️ **How It Works**

1.  Users open the chat page (`index.html`).
2.  A WebSocket connection is established with the server (`ws://localhost:8080/ws`).
3.  Messages are exchanged in real-time using WebSocket protocols.

🔮 **Future Enhancements**

* ✨ User Authentication (Login/Signup)
* ✨ Message History with Database Storage
* ✨ Private Chats and Group Messaging
* ✨ Emoji & File Sharing Support

📜 **License**

This project is licensed under the MIT License - see the `LICENSE` file for details.

🤝 **Contributing**

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.


