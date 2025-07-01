# Module 1: Communication in a Connected World

## 1.1 Data Transmission

### Types of Personal Data
- Volunteered Data: This is created and explicitly shared by individuals, such as social network profiles. (E.g. video files, pictures, texts, or audio files.)
- Inferred Data: This is data such as credit score, based on the analysis of volunteered or observed data.
- Observed Data: This is captured by recording the actions of individuals, such as location data when using phones. (E.g. Your phone keeps track of your location and the data is being transmitted and stored to your carrier.)

### 1.2 The Bit
- A bit is stored and transmitted as one of two possible discrete states ("0", "1").
With ASCII, each character is represented by 8 bits, as follows:
- Capital letter: A = 01000001
- Number: 9 = 00111001
- Special character: # = 00100011

### 1.3 Media
- Examples of media are copper wire, fiber-optic cable, and electromagnetic wavelength.
- Electrical Signals - Transmission is achieved by representing data as electrical pulses on copper wire
- Optical Signals - Transmission is achieved by converting the electrical signals into light pulses.
- Wireless Signals - Transmission is achieved by using infrared, microwave, or radio waves through air.  


# Module 2: Network Components, Types, and Connections


## 2.0 What will I learn in this module?
- Module Objective: Explain network types, components, and connections.  

| Topic Title              | Topic Objective                                      |
|--------------------------|------------------------------------------------------|
| Clients and Servers      | Explain the roles of clients and servers in a network |
| Network Components       | Explain the roles of network infrastructure devices  |
| ISP Connectivity Options | Describe ISP connectivity options.                   |

## 2.1 Clients and Servers

### 2.1.0 Clients and Server Roles
- All computers connected to a network that participate directly in network communication are classified as hosts.
- Hosts can send and receive message on the network.
- Servers are hosts that have software installed which enable them to provide information (e.g. email, web pages) to other hosts on the network.
- Each service requires a separate server software:
  - Email: The email server runs email server software. CLients use mail client software, such as Microsoft Outlook, to access email on the server.
  - Web: The web server runs web server software. Clients use browser software, such as Windows Internet Explorer, to access web pages on the server.
  - File: The file server stores corporate and user files in a central location. The client devices access these files with client software such as the Windows File Explorer.

### 2.1.1 Peer-to-Peer Networks
- Client and server software usually run on separate computers.
- When a singular computer as the server and client on the network, it is called **peer-to-peer (P2P) network**.
- Example: 
    The simplest P2P network consists of two directly connected computers using either a wired or wireless connection. Both computers are then able to use this simple network to exchange data and services with each other, acting as either a client or a server as necessary.
- Advantages:
  - Easy to set up
  - Less complex
  - Lower cost because network devices and dedicated servers may not be required
  - Can be used for simple tasks such as transferring files and sharing printers
- Disadvantages:
  - No centralized administration
  - Not as secure
  - Not scalable
  - All devices may act as both clients and servers which can slow their performance.

### 2.1.2 Peer-to-Peer Applications
- A P2P application allows a device to act as both a client and a server within the same communication.
- Example:
    Every client is a server and every server is a client. (Person A send a message to Person B. Person B receives the message. Person B sends a message back. Person A receives the message...)
- Both clients can simultaneously send and receive messages.

### 2.1.3 Multiple Roles in the Network
- A computer with a server software can provide services simultaneously to on or many clients.
- A single computer can run multiple types of server software.
- Example:
  - Server (Runs email server, web server, file server), Connected with 4 computers (runs Web Browser and Email Client/File Access Client)

## 2.2 Network Components

### 2.2.2 Network Infrastructure
- The network infrastructure contains three categories of hardware components:
  - End devices (Desktop computer, laptop, IP phone, printer)
  - Intermediate devices (Wireless router, LAN Switch, firewall appliance)
  - Network media (Wireless Media, LAN media, WAN media)
- Devices and media are the physical elements/hardware of the network.
- Hardware involves the physical/visible components of the network platform such as a laptop/switch/router.
- In the case of wireless media, components are not visible, hence messages are transmitted through the air using invisible radio frequencies or infrared waves.

### 2.2.3 End Devices
- Examples of end devices include: computers, network printers, telephones and teleconferencing equipment, security cameras, mobile devices.
- An end device is either the source or destination of a message transmitted over the network.

## 2.3 ISP Connectivity Options

### 2.3.1 ISP Services
- An Internet Service Provider (ISP) provide the link between the home network and the internet.
- An ISP can be the local cable provider, a landline telephone service provider, the cellular network that provides your smartphone service, or an independent provider who leases bandwidth on the physical network infrastructure of another company.
- The primary medium that connects the internet backbone is the fiber-optic cable.
  - This cable is often installed underground to connect cities within continents.
  - Fiber-optic cables also run under the sea to connect continents, countries, and cities.

### 2.3.2 ISP Connections
- The interconnection of ISPs that forms the backbone of the internet is a complex web of fiber-optic cables with expensive networking switches and routers that direct the flow of information between source and destination hosts.

### 2.3.3 Cable and DSL Connections
- Cable: 
  - Typically offered by cable television service providers.
  - The internet data signal is carried on the same coaxial cable that delivers cable television.
  - Provides a high bandwidth, always on, connection to the internet.
  - Special cable modem separates the internet data signal carried on the cable and provides an Ethernet connection to a host computer or LAN.
- DSL - Digital Subscriber Line:
  - Provides a high bandwidth, always on, connection to the Internet.
  - Requires a special high-speed modem that separates the DSL signal from the telephone signal and provides an Ethernet connection to a host computer or LAN.
  - DSL runs over a telephone line, with the line split into three channels.
    - First channel is used for voice telephone calls. (Allows an individual to receive phone calls without disconnecting from the internet.)
    - Second channel is a faster download channel, used to receive information from the internet.
    - Third channel is used for sending and uploading information. (Slightly slower than the download channel.)
  - Quality and speed of the DSL connection depends on the quality of the phone line and the distance from the central office of your phone company. (The farther you are from the central office, the slower the connection.)

### 2.3.4 Additional Connectivity Options
Other ISP connection options for home users include the following:
- Cellular: 
  - Uses a cell phone network to connect.
  - Performance will be limited by the capabilities of the phone and the cell tower to which it is connected.
  - Downside is the carrier usually meters the bandwidth usage of the connection and may charge extra for bandwidth that exceeds the contract data plan.
- Satellite:
  - Good option for homes/officers which do not have access to DSL or cable.
  - Satellite dishes require a good line of sight to the satellite and may be difficult in heavily wooded areas or places with other overhead obstructions.
  - Speeds will vary depending on the contract, though they are generally good.
- Dial-Up Telephone:
  - An inexpensive option that uses any phone line and a modem.
  - To connect to the ISP, a user calls the ISP access phone number.
  - The low bandwidth provided by a dial-up modem connection is usually not sufficient for large data transfer, though it is useful for mobile access while traveling.

# Module 3: Wireless and Mobile Networks

