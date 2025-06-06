Real-Time Communication Between WebSocket Server, WinForms Client & Serial Port (COM)

Live data exchange between a browser-based WebSocket server, a .NET WinForms client, and RealTerm over Serial COM port — with full duplex messaging.
💬 WebSocket-to-Serial Communication System in .NET
A C# WinForms application and ASP.NET Core Razor Web interface enabling **real-time bi-directional communication** between a WebSocket Server and Serial (COM) Port via a WebSocket Client.

---

## 📁 Project Structure

![image](https://github.com/user-attachments/assets/be73c62d-071c-4051-b9ce-e9b52e6ab47c)
📦 WebSocket-SerialBridge/
├── 🔧 WinForms Client (SerialPort + WebSocket)
├── 🌐 ASP.NET WebSocket Server (Razor Pages)
├── 📄 README.md
└── 📦 SocketSerialBridge.zip

---

## 🔧 Technologies Used

- **C# WinForms** – WebSocket client and Serial port handling
- **ASP.NET Core** – WebSocket server using Razor Pages
- **JavaScript** – Real-time WebSocket frontend for browser
- **System.IO.Ports** – COM port interaction
- **System.Net.WebSockets** – WebSocket client in .NET

---

## 📸 Real-Time Output Snapshot

> Below image shows full communication cycle:  
> 🟢 WebSocket Server → WinForms Client → Serial Port (RealTerm) → Back to WebSocket

![Communication Live Demo](https://github.com/Smruti765/SOCKET_IP_BASED_CLIENT-AND-SERVER/raw/main/Capture.PNG)

---

## 🚀 Features

✅ Connect to WebSocket Server  
✅ Read & Write to Serial Port (COM)  
✅ Forward Serial Data to WebSocket (and vice versa)  
✅ Web-based Live Messaging Console  
✅ UI-based COM port & baud rate selection  
✅ Error handling and message logging

---

## 🔄 Flow Diagram

SerialPort <--> WinForms Client <--> WebSocket Server <--> Web Browser UI


---

## 🧪 How to Run

### 💻 WinForms Client

1. Open solution in Visual Studio
2. Run the `Form1.cs` project
3. Select COM port and Baud rate
4. Click **"Connect Port"**
5. Then click **"Connect WebSocket"** to connect to server

### 🌐 ASP.NET WebSocket Server

1. Run ASP.NET Razor project on `localhost:8080`
2. Open browser → http://localhost:8080
3. Use the input to send messages → it will broadcast to client and serial

---

## 📦 Download

👉 [Download Full Project (ZIP)](https://github.com/Smruti765/SOCKET_IP_BASED_CLIENT-AND-SERVER/releases/download/v1.0/Socket_IP_Based_Chat.zip)

---

## 👩‍💻 Developer

**Smruti Jaiswar**  
💼 .NET & Web Developer  
🔗 [GitHub Profile](https://github.com/Smruti765)

---

## 📜 License

This project is licensed under the MIT License.
