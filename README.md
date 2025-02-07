# Server-Client-Java-Project2                                           
💬Simple Chat Application in Java (TCP Client-Server) | Java Networking📡                                                                                        

🌐Description->                                                                                                                                                                                                                      
This is a basic console-based chat system built with Java using TCP socket programming. The application follows a client-server architecture, where the server listens for incoming client connections and facilitates real-time communication between connected clients, also enable you to see ip addresses, list of connected clients. You can add as many features/functionalies as you can.🚀                                                                                                                                                             
                
✨Features                                                            

💠Supports multiple clients connecting to the server.                                                                                                       
💠Real-time message exchange using TCP sockets.                                                                                                                   
💠Splits messages using "$" for processing.                                                                                                                                                            
💠Recognizes keywords like send, ip for specific actions.                                                                                                                                                                     
💠Console-based chat interface.                                                                                                                                                                                         
💠Simple and efficient implementation of networking concepts.                                                                                                                                                  
💠Built for learning Java & networking, not real-world production use.                                                                                                                      

🛡 Technologies Used- Java, IntelliJ IDEA.                                                                                                      

🛠 How to Run                                                                                                      

✔ Use any IDE like Netbeans, Intellij IDEA, VS code or follow the instructions below-                                                                                               

1. Compile the Java Files                                                                   
  Ensure you have Java & JDK installed on your system. Open a terminal or command prompt and navigate to the directory where the Java files are stored & use the following commands.                                    
    -javac Server.java                                                                               
    -javac Client.java                                                                                                                                             

2. Start the Server                                                                                                                                                                 
    -Run the following command to start the server:                                                                                                                    
      -java Server                                                                                                                                                                   

The server will start and wait for client connections.                                                                                                                                                     

3. Start the Client                                                                                                                                                                                                                                                   
  In a new terminal window, run the client application:                                                                                                   
    -java Client
*You can start multiple clients by using IDE or opening additional terminals and running the same command.(SS below)*

💬 Example Usage-                                                                                               
                                 
👉Start the server first.                                                                                                                                                                             
👉Run one or more clients.                                                                                                                                                                       
👉Clients can send messages to the server and the server will broadcast messages/ip to all connected clients.                                                                                                                       
                                                                                                           
📲Snapshots:                                                                                         

👇Server starts...                                                         

![image](https://github.com/user-attachments/assets/abb45aca-f8b2-42c6-a0b2-49fb14882e5b)

👇ClientMain starts...                                                                      

![image](https://github.com/user-attachments/assets/6a46004e-377e-41f9-8ad1-5cd4e932d000)

👇How to run multiple clients -> go to the 3dot icon -> edit configuration -> Go to the + icon above application -> create another client under clientMain -> SS below for clear understanding-                                                            

![image](https://github.com/user-attachments/assets/a584fdb9-6147-47a8-8a11-8614961efe63)

👇Client2 (Taoshif) starts...                                                                                                                                                                         

![image](https://github.com/user-attachments/assets/01436d0c-2df2-429c-a9ab-f26e54a58a30)                                                                                       
                                       
👇Client2 (Taoshif) requested for list(connected clients)-                                                                                                                                                  

![image](https://github.com/user-attachments/assets/52acfef4-77ec-43a9-b4ec-c8042a6b9650)                                                                                                                                           
                                                                            
👇ClientMain requested for ip address-   
                                     
![image](https://github.com/user-attachments/assets/7fc8c7a5-7d77-4ded-8fe3-56b200693fc4)                                                                                                                                                                              
                                                                                                                                                                                             
👇ClientMain sent a message to Client2(Taoshif)-                                                                                                                                                                                                                                                                                                                          
![image](https://github.com/user-attachments/assets/48877b42-cd66-4cd7-bcbc-b5b7ee380a02)                                                                                                                                                                                                                                                                                                                                                                                                                      
👇Client2 (Taoshif) recieved and replied to ClientMain-                                                                                                                                                                                                                                                                                                                             
![image](https://github.com/user-attachments/assets/568f45c4-0aab-4b61-8783-c6eaba62d617)                                                                                                                                                 
[You can chat like this using the same wifi network but from different computers, no problem. Also as i am running both clients from the same computer thats why the ip is same]                                                                 
                                                        
👇ServerMain the whole time-                                                                                                                                          
                                                    
![image](https://github.com/user-attachments/assets/ad081b72-3983-4e4e-826a-0e694d74454f)                                                                                                          

🔧 How It Works                                                                             

1. Server starts first and listens for connections. ⚡                                                                                                              
2. Clients connect and send messages. 💬                                                                                                                                       
3. Messages are processed using "$" to differentiate parts. ✉️                                                                                     
4. Special keywords like send, ip trigger certain actions. 📝                                                                                                                     
5. Messages are delivered to respective clients via TCP. 📡                                                                                                                                                                                                  
                                                                       
🚀 Future Improvements                                                                                                                                                                

💠Add GUI (JavaFX, Swing) for a user-friendly interface 🖥️                                                                                                        
💠Implement encryption for secure communication 🔒                                                                                  
💠Improve scalability for handling more users 🌍                                                                                         

📌 Installation & Usage                                                                                                                     

1. Clone the repository: git clone [GitHub Repo Link] 🖥️                                                                                        
2. Open in IntelliJ IDEA (or any Java IDE) 💡                                                                                                                                    
3. Run ServerMain.java first, then ClientMain.java ▶️                                                                                       
4. Create multiple clients.(Optional) 💬                                                                                                         
5. Start chatting! 🎉                                                                                                                                                

💡This project was created for learning Java networking. Inspired by how modern chat applications work! 🔥                                                                                                                       
💡Feel free to contribute to this project or reach out with suggestions!💬                                                                                                                                                            
💡This README provides all necessary details to set up and use the chat application. Let me know if you need modifications!👨‍💻                                                                                                                  
