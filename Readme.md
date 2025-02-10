# Packet Tracer Web Server Network Simulation

## Overview

This project simulates a basic network environment with multiple web servers hosting different websites, accessible by client PCs within the network. The network utilizes a DNS server to resolve website names to server IP addresses, demonstrating fundamental client-server architecture and web hosting concepts within Cisco Packet Tracer.  The simulated websites also include a functional dark mode toggle for enhanced visual demonstration.

## Network Topology

The network topology is designed as a simple local area network (LAN) using a switch to connect all devices.  The following devices are used in this simulation:

*   **1 x Multilayer Switch:** Cisco 3650 Multilayer Switch -  Acts as the central connection point for all devices in the network.
*   **6 x Client PCs:**
    *   3 x Laptops (Representing client laptop devices)
    *   3 x PCs (Representing desktop client devices) - Used to access the simulated websites.
*   **5 x Web Servers:**
    *   Web-Server-1
    *   Web-Server-2
    *   Web-Server-3
    *   Web-Server-4
    *   Web-Server-5 - Each server is configured to host a distinct simulated website.
*   **1 x DNS Server:** DNS-Server - Responsible for translating website domain names into the IP addresses of the respective web servers.

All devices are connected to the 3650 Multilayer Switch using copper straight-through cables.

## Concepts Demonstrated

This project showcases the following networking and web concepts:

*   **Client-Server Model:** Demonstrates the interaction between client PCs requesting web pages and web servers providing them.
*   **HTTP Protocol:**  Utilizes HTTP for web communication between clients and servers.
*   **DNS (Domain Name System):**  Implements a basic internal DNS server to resolve website names to IP addresses, allowing clients to access websites using names instead of IP addresses.
*   **IP Addressing:**  Employs static IP addressing to configure devices within a private network range.
*   **Basic Web Server Configuration:**  Demonstrates the fundamental setup of web server services in Packet Tracer, including hosting web pages.
*   **Dark Mode Implementation:**  Illustrates a basic front-end implementation of a dark mode toggle within web pages using HTML, CSS, and JavaScript.

## Website Simulation

This project simulates five distinct websites, each hosted on a dedicated web server:

*   **Web-Server-1:**  Simulates **www.amazon.com**
*   **Web-Server-2:**  Simulates **www.swiggy.com**
*   **Web-Server-3:**  Simulates **www.zomato.com**
*   **Web-Server-4:**  Simulates **www.flipkart.com**
*   **Web-Server-5:**  Simulates **www.blinkit.com**

Each web server is configured with a basic `index.html` page styled to visually represent the respective website's branding and includes a functional dark mode toggle. The DNS server is configured with 'A' records to map these website names to the corresponding web server IP addresses.

## Accessing the Simulated Websites

To access the simulated websites from the client PCs within Packet Tracer:

1.  **Power on** all devices in the Packet Tracer topology.
2.  **Wait** for the network connections to establish (indicated by green link lights).
3.  **Click on a Client PC** (Laptop or PC).
4.  Go to the **"Desktop"** tab.
5.  Open the **"Web Browser"**.
6.  In the **"URL" address bar**, type in the desired website name (e.g., `www.amazon.com`, `www.flipkart.com`, `www.zomato.com`, `www.swiggy.com`, `www.blinkit.com`) and press **"Go"**.
7.  The simulated website's homepage should load in the web browser.
8.  You can toggle **Dark Mode** on each website using the checkbox provided on the page, typically located in the top right corner.

## GitHub Repository Contents

This repository contains the following files:

*   **`web_server_network.pkt`:**  The Cisco Packet Tracer file containing the network topology and device configurations for this project.
*   **`README.md`:**  This file, providing an overview of the project, setup instructions, and concepts demonstrated.

## Further Enhancements (Optional)

This project can be further expanded upon by:

*   Adding more complex HTML and CSS to the simulated websites to create more visually rich and feature-filled pages.
*   Implementing more advanced DNS configurations, such as subdomains or different record types.
*   Introducing a router to connect this LAN to a simulated "Internet" for external access (beyond the scope of this basic project).
*   Exploring other server services in Packet Tracer, such as FTP or Email servers, within the same network topology.

This project serves as a foundational example of a client-server web network built and simulated within Packet Tracer, suitable for educational purposes and demonstrating basic networking principles.



**Disclaimer:** This **Packet Tracer project file (.pkt)** is provided as an educational resource, for learning purposes only. It is not intended for commercial use. Simulations of websites within this file are for demonstration and are not affiliated with or endorsed by the respective entities.
