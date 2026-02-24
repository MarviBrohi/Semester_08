# Introduction to Parallel and Distributed Computing
# Computing:
Any activity that uses computers to manage, process, and share information.
Real-Life-Example:
. Managing: Organizing your photos in folders
. Processing: Editing a video
. Communicating: Sending an email

# Trends of Computing
. A group of computers working together that looks like One computer to the user.
. Several independent computers, each with its own memory, communicating by passing messages.
. Analogy: Think of a restaurant chain like Domino's. You order online, and the system finds the nearest store to make your pizza. You don't know or care which store made it - it just works!
Operating System Concept: The processors communicate with  one another through various communication lines,such as high-speed buses or telephone lines.
Each processor has its own local memory.

# Computers in a Distributed System
Workstations: End-users use these for daily work(Computer labs).
Server Systems: Provide resources and services(College server storing student records).
Personal Assistance Devices: Handheld computers connected wirelessly(smartphoe accessing college wifi).
# Examples of Distributed System
Internet: Millions of computers connected worldwide.
ATM Machines
intranets: Company's internal network with shared printers and files
# Common Properties of Distributed Computing
Fault Tolerance: System keeps working even if some computers fail.
. if one ATM dtops working, other ATms still work.
Each Node Plays Partial Role: Each computer knows only single part of the system.
. In railway reservation, one server handles North India, another handles South India
Resource sharing: Users can share computing power and storage.
. Lab students sharing a powerful printer.
load Sharing: Work is spread across all computers.
. During exam results, traffic is spread accross multiple servers.
Easy to Expand: Adding new computers taking little time.
. Adding more servers during admission season.
Performance: Work gets done faster with many computers.
. Downloading a movie from multiple sources simultaneously.
# Why do we neew Distributed Computing:
1.nature of Application: Some problems are naturally spread out.
Example: Banking system with branches everywhere
Example: Social media where users are worldwide
2.Performance:
Computing Intensive: Tasks that need lots of calculation.Example: calculating Pi value to billions of digits.
Data Intensive: Tasks dealing with huge files.Example:Facebook processing millions of photos.
# 3.Robustness (Reliability):
No Single Point of Failure (SPOF): If one computer fails, the system still works
Task Reassignment: Other computers can take over the failed computer's work
Real Example: If one Google server fails, you still can search because other servers take over.
# Distributed Applications
Two Main Types:
1. Client-Server (Traditional):
Server manages resources centrally
Clients request services
Example: College website - central server, many students access it
2. Peer-to-Peer (Modern):
All computers are equal
More "truly" distributed
Example: Torrent downloads - you download from many users simultaneously.
# Cluster Computing:
A group of SAME-TYPE of computers in ONE ROOM, connected with FAST cables, working as ONE SYSTEM.
. Like 20 identical chefs working in one kitchen, all wearning same uniform, using same ingredients, following same head chef.
# Key Components of Cloud Computing:
Multiple Standalone Computers: Regular computers, each can work alone.
Operating System: usually same OS on all(all linux or all windows).
High-Performance Interconnects: Very fast cables connecting them.
Middleware: Software that makes them work together.
Parallel Programming Environments: Tools to writr programs that use all computers.
Applications: The actual work being done.
# Cluster Characteristics:
Network: Faster than regular LAN(Local Area Network)
Communication: Very fast, low delay(low latency)
Coupling: Loosely coupled(not as tight as multi-core processors)
Types of Clusters
1. High Availability (Failover) Clusters
Purpose: Keep services running even if some computers fail
Real Example:
Airline reservation system
If one server fails, another takes over immediately
Passengers keep booking tickets without noticing any problem
2. Load Balancing Clusters
Purpose: Spread work evenly across all computers
Real Example:
Flipkart during Big Billion Day sale
Millions of users are distributed across many servers
No single server gets overloaded
3. Parallel/Distributed Processing Clusters
Purpose: Solve big problems by dividing work
Real Example:
Weather forecasting
Each computer calculates weather for one region
All results combined for full forecast
