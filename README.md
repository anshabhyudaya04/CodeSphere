# 🧠 CodeSphere: Real-Time Collaborative Code Editor

**CodeSphere** is a real-time collaborative coding platform designed for pair programming, remote technical interviews, and distributed team development. It supports live multi-user code editing, chat, and whiteboarding with seamless synchronization—offering both web and desktop versions for maximum flexibility.

---

## 🚀 Features

- 👨‍💻 **Real-Time Collaborative Editing**  
  Multiple users can write and edit code together in real-time with instant sync.

- 🧠 **Syntax Highlighting**  
  Code editors support syntax highlighting for an intuitive editing experience.

- 💬 **Live Chat & Whiteboard**  
  Integrated chat system and collaborative whiteboard (Excalidraw on web / RichTextFX on desktop) enhance communication and planning.

- 🖥️ **Cross-Platform Interface**  
  - Web interface built with **React.js**  
  - Desktop version built with **JavaFX**

- 🌐 **Low-Latency Communication**  
  WebSocket (STOMP) protocol ensures real-time sync with minimal delay.

- 🗃️ **Document History & Session Management**  
  Temporary storage and version tracking with **PostgreSQL**.

- ✅ **Production-Ready UX**  
  Clean, responsive UI with zero linter issues and smooth multi-user workflows.

---

## 🛠️ Tech Stack

### Frontend
- **React.js** (Web UI)
- **JavaFX** (Desktop UI)
- **Excalidraw** (Web Whiteboard)
- **RichTextFX** (JavaFX Editor)

### Backend
- **Spring Boot**  
  - REST APIs  
  - WebSocket endpoints (STOMP protocol)

### Database
- **PostgreSQL**  
  Used for:
  - User session tracking  
  - Temporary document version history

### Communication Protocols
- **WebSocket (STOMP)** for real-time collaboration

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/anshabhyudaya04/CodeSphere.git
cd codesphere
````

### 2. Backend (Spring Boot)

```bash
cd backend
./mvnw spring-boot:run
```

* Configure PostgreSQL credentials in `application.properties`

### 3. Web Frontend (React.js)

```bash
cd frontend-web
npm install
npm run dev
```

### 4. Desktop Client (JavaFX)

Open the `desktop-client` module in your preferred Java IDE (e.g., IntelliJ or Eclipse) and run the main class.

---


## 💡 Use Cases

* **Remote Pair Programming**
* **Live Technical Interviews**
* **Code Review Sessions**
* **Online Teaching or Workshops**

---

## 🧪 Testing

* Unit and integration tests available for backend endpoints.
* WebSocket sync tested across multiple concurrent clients.
* UI tested for cross-browser and OS compatibility.

---


## 📬 Contact

**Ansh Abhyudaya**
📧 [ansh.abhyudaya04@gmail.com](mailto:ansh.abhyudaya04@gmail.com)     
💻 [GitHub](https://github.com/anshabhyudaya04)

---

## 📄 License

MIT License © 2025 Ansh Abhyudaya
