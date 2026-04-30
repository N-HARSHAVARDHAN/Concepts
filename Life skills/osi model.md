
## **OSI Model:**

* The OSI model is a conceptual framework which helps us to understand the transfer of data between two computers.  
* OSI consists of seven layers.



### **1. Application Layer:**

* This layer provides services to applications like Chrome, Firefox, etc.  
* There are different protocols in this layer, including HTTP/HTTPS, which help in web browsing, and FTP for file transfer, etc.



### **2. Presentation Layer:**

* The Presentation layer converts data into binary form. This process is called translation.  
* This layer also performs data compression, encryption, and decryption.



### **3. Session Layer:**

* The Session layer establishes, maintains, and terminates the connection between two devices.  
* This layer is also responsible for authorization and authentication.



### **4. Transport Layer:**

* This layer is responsible for data transfer between the sender and receiver.  
* It divides large data into smaller units called segments. Each segment contains a sequence number and port numbers. This process is called segmentation.  
* This layer also provides flow control and error control.



### **5. Network Layer:**

* The Network layer is responsible for delivering data from one computer to another.  
* Devices in this network are assigned an IP address. The Network layer adds the sender’s and receiver’s IP addresses to each data packet.  
* It also performs path determination.



### **6. Data Link Layer:**

* It receives packets from the Network layer and converts them into frames.  
* This layer adds physical addresses, that is, MAC addresses, to the data.


### **7. Physical Layer:**

* The Physical layer is the last layer of the OSI model. It is responsible for transmitting raw bits, that is, 0s and 1s.  
* At the receiver’s side, the Physical layer converts the signals back into bits and passes them to the Data Link layer.

### References:
* https://www.youtube.com/watch?v=Q3WpcO6vtQ8
* https://youtu.be/vv4y_uOneC0?si=qINnPz1xvYwAkenA
* https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/
