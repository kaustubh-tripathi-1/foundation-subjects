# Network Architectures/Structures

## CLIENT SERVER ARCHITECTURE

> Client-server architecture is a computing model where clients request services from a central server. The server processes these requests and sends back the results, enabling efficient resource sharing and management across a network. This architecture is fundamental to many applications, including web browsing, email, and online banking.

**Key Components and Concepts:**

-   Clients:  
    These are devices or applications (like web browsers, email clients, or mobile apps) that initiate requests to access resources or services.
-   Servers:  
    These are powerful machines that host and manage resources, process client requests, and send back responses.
-   Networking:  
    Client and server communicate over a network using protocols like HTTP, FTP, or SMTP.
-   Request-Response:  
    The core of the interaction is a request from the client and a corresponding response from the server.

**How it Works:**

1. A client (e.g., your web browser) requests a webpage from a server (e.g., a web server).
2. The server processes the request, fetching the necessary data (HTML, CSS, JavaScript, images, etc.).
3. The server sends the data back to the client.
4. The client (your browser) then renders the webpage for you to view.

**Types of Client-Server Architectures:**

-   2-tier:  
    Simplest form with direct communication between client and server.
-   3-tier:  
    Adds an application server layer between the client and the database server, improving scalability and maintainability.
-   N-tier:  
    Further divides the application into multiple layers for complex systems.

**Advantages:**

-   Centralized Management: Server manages resources, simplifying administration.
-   Scalability: Easily add more clients or servers as needed.
-   Security: Centralized control allows for better security measures.
-   Resource Sharing: Enables efficient sharing of resources (data, processing power, etc.).

**Disadvantages:**

-   Single Point of Failure: If the server goes down, all clients are affected.
-   Network Dependency: Performance relies on network connectivity.
-   Complexity: Can be complex to design and manage, especially in larger systems.

**Examples:**

-   Websites: Your web browser (client) requests webpages from web servers.
-   Email: Your email client sends and receives emails through mail servers.
-   Online Banking: Your banking app (client) interacts with banking servers.
-   Online Games: Your game client communicates with game servers to manage game state and player actions.

---

## PEER TO PEER ARCHITECTURE (P2P)

> Peer-to-peer (P2P) architecture is a decentralized network model where each participant, or peer, acts as both a client and a server, sharing resources directly with each other without the need for a central server. This distributed approach offers advantages in terms of scalability, resilience, and fault tolerance compared to traditional client-server models.

**Key characteristics of P2P architecture:**

-   **Decentralization:** No central server controls the network; all peers have equal responsibilities and capabilities.
-   **Resource Sharing:** Peers can share files, data, bandwidth, and computing power directly with each other.
-   **Client/Server Role:** Each peer can both request and provide services to other peers.
-   **Scalability:** P2P networks can easily scale as more peers join, as they contribute resources to the network.
-   **Resilience:** If one peer goes offline, the network can continue to function as other peers can still connect.

**Examples of P2P applications:**

-   **File Sharing:** Platforms like BitTorrent allow users to download files from multiple sources (other users) simultaneously.
-   **Instant Messaging:** Some messaging apps use P2P for direct communication between users.
-   Cryptocurrencies: Blockchain networks like Bitcoin use P2P for transaction validation and distribution.
-   **WebRTC:** This technology enables direct, peer-to-peer communication for real-time applications like video conferencing.
-   **Distributed Computing:** Projects like SETI@home utilize P2P to distribute computational tasks across many computers.

**Types of P2P networks:**

-   **Structured P2P:** These networks have a defined structure for locating resources, like Distributed Hash Tables (DHTs).
-   **Unstructured P2P:** In these networks, peers can connect to any other peer, and resource discovery relies on flooding the network.
-   **Hybrid P2P:** These networks combine P2P with a central server or directory for tasks like bootstrapping or resource discovery.
