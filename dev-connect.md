# 🚀 Dev-Connect: A Better Way to Share Applications P2P  

Dev-Connect is a VSCode extension that enables **peer-to-peer (P2P) connections** between applications running on localhost. It allows developers to seamlessly share and run full-stack applications across different machines **without exposing them to the internet**.  

---

## 🔹 How to Use  



  [![Watch the video]](https://github.com/user-attachments/assets/23183940-5361-4b4f-99ad-8ee19e019958
)

### 1️⃣ Install Dev-Connect Extension  
Install the extension in VSCode.  

### 2️⃣ Set Up Your Application  
Specify ports for:  
   - **Frontend (FE)**  
   - **Backend (BE)**  
   - **Database (DB)**  
   - **Others** (Custom services)  

### 3️⃣ Generate a Connection Key  
   - After setup, Dev-Connect generates a **unique key**.  
   - This key contains all necessary information for the connection.  

### 4️⃣ Share & Connect  
   - Send the key to another developer.  
   - They enter the key in their Dev-Connect extension.  

### 5️⃣ Application Starts Running on Their Localhost  
   - The receiver’s system establishes a direct connection and **mirrors the application**, making it accessible as if it were running locally.
   - Share
![Dev-Share](https://github.com/user-attachments/assets/67e705e0-2b78-46c5-b809-04776a8cdff9)

   - Connect
![Dev-Connect](https://github.com/user-attachments/assets/fd79530d-03c8-40aa-a346-993e9c0f8a24)

---

## 🔹 How It Works Internally  

### 1️⃣ Establishing a P2P Connection  
- Dev-Connect uses **HyperDHT**, a decentralized networking protocol, to create a direct **peer-to-peer** connection.  
- It generates a **unique key pair** (public & private key) for identification and **secure communication**.  

### 2️⃣ Forwarding Application Traffic  
- When a developer shares an application, Dev-Connect sets up a **secure tunnel** that forwards traffic from the defined ports.  
- The traffic is relayed **peer-to-peer without any intermediary servers**, ensuring direct communication.  
- **libNet** is used to efficiently transfer data over **TCP or UDP** connections.  

### 3️⃣ Running the Application on the Receiver’s Localhost  
- The receiver connects using the **shared key**, and Dev-Connect creates a **local proxy** on their machine.  
- This proxy **maps the incoming data**, making the application behave as if it’s running **natively on their system**.  

---

## 🔹 Why Dev-Connect is Better Than Other Solutions? 

 ![Comparison Chart](https://github.com/user-attachments/assets/3563ff62-954a-4d61-a340-a3a7c30e183e)

---

## 🔹 Why Choose Dev-Connect?  
✅ **Truly P2P** – No third-party servers, no cloud dependencies.  
✅ **No Configuration Hassles** – No need to tweak firewalls, open ports, or sign up for accounts.  
✅ **Works with Any Stack** – Share your entire app (Frontend, Backend, DB) in seconds.  
✅ **More Secure** – Keeps everything on localhost without exposing services to the internet.  
✅ **Faster & Lower Latency** – Direct peer-to-peer connection means no relay bottlenecks.  

🚀 **Dev-Connect makes real-time collaboration easier, faster, and more secure than any other solution!**  
