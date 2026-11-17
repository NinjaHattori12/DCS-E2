# Experiment 2: Java RMI Calculator (Addition)

A distributed application demonstrating Remote Method Invocation (RMI) in Java.

---

## 📁 Files

- `AddServerIntf.java` – Remote interface
- `AddServerImpl.java` – Implementation of the remote interface
- `AddServer.java` – Server that hosts the registry & remote object
- `AddClient.java` – Client that invokes the remote method

---

## 🚀 Execution Commands & Sequence

### Step 1: Compile All Files
Open terminal in the project folder and run:
```bash
javac *.java
```

### Step 2: Run the Server (Terminal 1)
```bash
java AddServer
```
> Keep this terminal running.

### Step 3: Run the Client (Terminal 2)
Open a new terminal window/tab in the same directory and run:
```bash
java AddClient
```

---

## 🖥️ Example Output

### Terminal 1 (Server):
```text
RMI Server is ready...
Waiting for client...
```

### Terminal 2 (Client):
```text
Enter first number: 25.5
Enter second number: 14.5
Sum = 40.0
```
