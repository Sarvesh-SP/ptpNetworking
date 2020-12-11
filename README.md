# ptpNetworking
* Implementation of a three nodes point –to –point network with duplex links between them, used to simulate the communication between the nodes and to find the number of packets droped by varying the Bandwidht.

![alt tag](https://github.com/Sarvesh-SP/ptpNetworking/blob/master/ptpn_nam.png)

##### Set up(only for Linux Users).
1. Clone the repo.

        git clone https://github.com/Sarvesh-SP/ptpNetworking.git

2. Navigate into the repo and compile the .tcl file

        sudo ns ptpn.tcl
        

3. Run the ptpngraph file using Xgraph

        xgraph -x "Bandwidth(Mbps)" -y "Packet drop count" -t "Performance Analysis" ptpngraph
   
4. Now take the ScreenShot of the graph
![alt tag](https://github.com/Sarvesh-SP/ptpNetworking/blob/master/ptpngraph.png)
