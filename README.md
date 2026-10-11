# 🕶️ ShadowRAT – Basic Python Remote Access Tool for beginners (Educational)

ShadowRAT is a simple Python-based Remote Access Tool (RAT) designed for **educational purposes only**. It allows a user to remotely interact with another machine through a socket connection and execute various commands such as taking screenshots, typing text, moving the mouse, locking the screen, and more.

---

## 📁 Files in This Repository

- `client.py` – Run this script on the **target/victim machine**
- `server.py` – Run this script on the **admin/attacker machine**

---

## ⚙️ How It Works

ShadowRAT uses basic **TCP socket programming** in Python. The client connects to the server, waits for commands, and executes them on the victim machine. The server sends commands and receives output.

---

## 🚀 Setup & Usage

** change the ip on client.py and server.py to your ip (the atacker ip)


### 1. Install Requirements

On the **client machine**, install required packages:

#### on Windows:
1. download the project 
2. open cmd or powershell
3. run this command:
```bash
cd path\to\your\BasicPythonRat
```
4. then run:
```bash
pip install -r requirements.txt
```
5. if 4. does not work run this:
```bash
python -m pip install -r requirements.txt
```

##### on Linux and mac:
1. open bash and run:
```bash
git clone https://github.com/Noambh0/BasicPythonRat/tree/main
```
2. run this command:
```bash
cd BasicPythonRat
```
3. run:
```bash
pip install -r requirements.txt
```
4. if 4. does not work run this:
```bash
python -m pip install -r requirements.txt
```




