# Peer-to-Peer-using-UDP
This project is very easy to implement. The main purpose of this project is to implement the High Availability Cluster on 
the basis of Peer to Peer architecture. The peers that we wish to exchange the message are hard-coded and added in the Array
List. At first Server program runs so that it can start the seeding process. When the seeding process is complete. The thread
startSending starts to send the message to all of its Peers except itself from the list. This process continues until it 
reaches end of the list. 
