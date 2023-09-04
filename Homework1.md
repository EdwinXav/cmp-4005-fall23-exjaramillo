# Study Guide: Chapter 1 - Computer Networks: A Systems Approach

## Introduction
Welcome to the study guide for Chapter 1 of the textbook "Computer Networks: A Systems Approach" by Larry Peterson and Bruce Davie. This guide will help you understand the fundamental concepts of computer networks and provide you with questions and exercises to reinforce your understanding. Let's get started!

### Required reading
Sections: 1.1, 1.2, 1.3 and 1.5 

## 1. Building a Scalable Network
- What are the key considerations when building a scalable network?

    Bandwidth: Having adequate bandwidth is necessary for a scalable network. It is important to assess the current and future bandwidth requirements of the network and ensure that the network infrastructure can handle the expected volume of traffic.
    
    Redundancy: Having redundancy in the network helps us minimize downtime.

    Security: It is necessary to have strong security measures in order to protect the network from possible threats.

    Future growth: An attempt should be made to predict future growth, considering factors such as the number of users, devices, and applications that the network will need to support in the future.

    Network architecture: You must have a well-thought-out architecture that can accommodate growth.

    Network monitoring and administration: To monitor and manage networks, effective tools must be available which allow us to identify and solve problems promptly.


- Explain the concept of network scalability and why it is important.

    The scalability of a network refers to its ability to grow and adapt without compromising its performance or functionality, as well as providing flexibility to add new devices, applications and services without disturbing the existing infrastructure. This is important since it allows development in a constantly evolving technological environment, where new devices and technologies continually emerge. A key factor when designing a network from scratch, since it allows it to expand according to the changing needs of an organization .

    Likewise, considering scalability is essential to ensure that the network can handle future increases in users, devices and data traffic, since without this capacity, the network could become overloaded, experience slowness, congestion and even failures.


- Provide examples of different applications that require a scalable network.

    Cloud computing: Cloud service providers need a scalable network infrastructure to handle the growing demand for storage, processing power, and data transfer.

    Internet of Things (IoT): IoT devices such as smart home devices or wearables generate a large amount of data that needs to be transmitted and processed, requiring a scalable network to handle the growing number of connected devices.

    Video streaming: A scalable network is needed to deliver high-quality video content to a large number of users simultaneously.

    Social Media Platforms: Social media sites have many active users who generate and consume large amounts of data, so having a scalable network is necessary to handle the constant flow of information.

    Online gaming: Online gaming requires a scalable network to support realtime communication and interaction between players.


 - Why does a network need to be cost-effective, fair, and have robust connectivity?

    Profitability: A network must be costeffective in order to ensure that the resources and infrastructure required to establish and maintain the network are optimized. So that in this way services and connectivity can be provided at an affordable price, and in this way a greater number of users can be obtained.

    Equity: The network must guarantee that all users have the same opportunities to access and use network services without discrimination or prejudice. This in order for a single user or group to monopolize network resources.

    Robust connectivity: The network must have robust connectivity in order to handle high volumes of traffic, provide low latency, and maintain consistent performance even during periods of peak usage.
    

 - Discuss the challenges involved in designing a network that can support various applications.

    Bandwidth: Designing a network that can allocate enough bandwidth to each application can be challenging as different applications have different bandwidth requirements.

    Scalability: Designing a network that can handle growth without compromising performance or stability can be challenging, so the network should scale as the number of applications and users on the network increases.

    Compatibility: Various applications may have different protocols or communication requirements. Designing a network that can support different protocols and ensure compatibility between applications can be challenging.

    Security: Designing a network that is completely secure for each application can be a complex task, as different applications may have or need different security requirements.



## 2. Computer Network Architecture
- Define computer network architecture in terms of layers and protocols

    Computer network architecture in terms of layers means that the organization of the network can be seen in different layers, each of these layers providing a specific service. This allows for better management of the network, as it decreases complexity and allows for modular design and implementation. Since the standards for each layer can be developed independently, therefore, the changes made in the standards of one of them do not influence the processes that are being developed in the other layers.

    On the other hand, the protocols define the communication rules between the different components of the network. Where each layer of the network architecture has its own set of protocols.


- Why are layers and protocols important?

    Layers and protocols are important as they allow us to have abstraction. Because the layers provide a way to abstract complexity and through this we can make applications and protocols interact with the network without needing to understand the details of the underlying infrastructure. Also, it allows us to break down the problem, as each layer focuses on solving a specific part of the problem, which makes the design easier to understand.

    Similarly, layering promotes modularity in network design. If a new service or functionality needs to be added, it can be implemented in a specific layer, without affecting the other layers.
    
    Protocols are important as they define the rules and formats for communication between different components of the network. So thanks to this, different devices can communicate with each other and this allows various services to work together without problems.


- What is encapsulation, multiplexing and demultiplexing?

    Encapsulation refers to the process of adding headers at each layer of the protocol stack, these headers contain control information specific to that layer. This allows the message to be properly handled and interpreted by the corresponding layer at the destination.

    Multiplexing is the process of combining multiple data streams into a single stream for transmission over a shared medium or link. This allows multiple applications or protocols to share the same network connection.

    Demultiplexing is the reverse process of multiplexing, since it takes care of extracting individual data streams from a multiplexed stream at the receiving end. This ensures that each data stream is successfully delivered to its recipient.


- Discuss the role of each layer in the OSI and Internet protocol stack.

    Physical Layer: It is responsible for the transmission of raw bits through a communication link.

    Data Link Layer: It is responsible for collecting a stream of bits into larger aggregates called frames.

    Network Layer: Deals with logical addressing and packet routing, by routing between nodes within a packet-switched network

    Transport Layer: It is responsible for communication between different hosts.

    Session Layer: Responsible for establishing, maintaining, and terminating connections between applications.

    Presentation Layer: It handles encryption, compression, and data conversion.

    Application Layer: It is responsible for providing services directly to end-user applications.


- Provide examples of protocols used at each layer of the TCP/IP protocol stack.

    Internet Layer: Internet Protocol (IP)

    Network interface layer : Ethernet, Wi-Fi

    Transport Layer: Transmission Control Protocol (TCP)

    Application layer: Hypertext Transfer Protocol (HTTP)



## 3. Performance
- Why is important to keep track of the performance of a network?
- What are the main metrics we use to measure network performance?
- Give some examples of the challenges of using different metrics in high speed networks


## Exercises
1. Calculate the total time required to transfer a 1000-KB file in the following cases, assuming an RTT of 50 ms, a packet size of 1 KB data, and an initial 2 × RTT of “handshaking” before data is sent:

    a. The bandwidth is 1.5 Mbps, and data packets can be sent continuously.

        Initial Handshaking = 2 * R.T.T. = 2 * 50 ms = 100 ms

        we can send continuously : 

        So, time to transmit is (T.T) = 1000KB / 1.5 Mbps = 5333.33 ms

        Total Time = T.T. + Initial Handshaking time =  5333.33 + 100 = 5433.33 ms 


    b. The bandwidth is 1.5 Mbps, but after we finish sending each data packet we must wait one RTT before sending the next.

        Initial Handshaking = 2 * R.T.T. = 2*50 ms = 100 ms

        time to send 1 packet (T.T) = 1KB / 1.5 Mbps = 16 / 3 ms

        Inter packet gap = 1 R.T.T. = 50 ms

        Total Time  = Initial Handshaking time + 1000 packets * T.T + 999 * R.T.T.(waiting time)

                    =  100 + 1000(16/3) + 999(50)

                    =  55383.33 ms = 55.38 sec.

    
    c. The bandwidth is “infinite,” meaning that we take transmit time to be zero, and up to 20 packets can be sent per RTT.

        Initial Handshaking = 2 * R.T.T. = 2*50 ms = 100 ms

        packet size is 1 KB, so 1000 packets will be transmitted, only 20 per R.T.T.

        So, it takes 1000 / 20 = 50 R.T.T. 

        but in last R.T.T , transmission time is '0' => 49 R.T.T. = 2450 ms

        Total Time = Initial Handshaking time + packets T.T.

        Total Time = 100 + 2450 = 2550 ms

    
    d. The bandwidth is infinite, and during the first RTT we cansend one packet ($2^{1−1}$), during the second RTT we can send two packets ($2^{2−1}$), during the third we can send four ($2^{3−1}$), and so on

        Initial Handshaking = 2 * R.T.T. = 2*50 ms = 100 ms

        1000 packets to be transmitted ,

        In 1st R.T.T   = 1 packet

        In 2nd R.T.T. = 2 packet

        In 3rd R.T.T. = 4 packets  & so on 

        like this we will take 10 R.T.T. 

        But again in last R.T.T time taken will be '0' , so will not consider this => 9 R.T.T = 450 ms

        Total Time = Initial Handshaking time + packets T.T.

        Total Time = 100 + 450 = 550 ms
    

2. For each of the following operations on a remote file server, discuss whether they are more likely to be delay sensitive or bandwidth sensitive:

    a. Open a file.: Delay-sensitive, the messages exchanged are short

    b. Read the contents of a file: This is more likely to be bandwidth sensitive, since there could be a large amount of data that needs to be sent.
    
    c. List the contents of a directory: This is most likely delay sensitive, since a directory listing is relatively short and won't require more than a few packets of data to be sent.
    
    d. Display the attributes of a file: Delay-sensitive; a file’s attributes are typically much smaller than the file itself
    

3. Suppose a host has a 1-MB file that is to be sent to another host. The file takes 1 second of CPU time to compress 50% or 2 seconds to compress 60%.

    a. Calculate the bandwidth at which each compression option takes the same total compression + transmission time.
    
    total time = Compression time + compressed size/bandwidth
    bandwidth = compression size reduction/compression time
    bandwidth = 0.5 MB/1 sec = 0.5 MB/sec for the first case,
    bandwidth = 0.6 MB/2 sec = 0.3 MB/sec for the second case

    b. Explain why latency does not affect your answer

     Latency doesn’t affect because it would affect the compressed and uncompressed transmission equally


4. Discuss the relative performance needs of the following applications in terms of average bandwidth, peak bandwidth, latency, jitter, and loss tolerance:
    
    a. File server: It needs lots of peak bandwidth, latency is relevant only if it dominates bandwidth, jitter and average bandwidth are inconsequentialand no lost data is acceptable.
    
    b. Print server: Commonly a print server needs less bandwidth,  latency, jitter, and loss tolerance than a file server.
    
    c. Digital library: Depends on user activity, the average Bandwidth performance will be moderate to High as well as latency and jitter, while the loss tolerance will be low
    
    d. Routine monitoring of remote weather instruments: In this case we don’t care about latency or jitter. If data were continually generated, rather than bursty, we might be concerned mostly with average bandwidth rather than peak, and if the data really were routine we might just accept a certain fraction of loss.
    
    e. Voice: The average bandwidth and bounds on latency and jitter performance will be moderate. Some lost data might be acceptable
    
    f. Video monitoring of a waiting room: The avergae bandwidth will be moderate to High, the peak bandwidth high during live streaming, latency will be low to Moderate as well as the jitter and the loss Tolerance
    
    g. Television broadcasting: It requires high bandwidth. Latency, however, could be hours. Jitter would be limited only by our capacity to absorb the arrivaltime variations by buffering and some loss would be acceptable.


```python

```
