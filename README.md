# Treasure-Hunt-Game-DSA
The Treasure Hunt Game is a DSA-based project where players navigate through connected locations represented as a graph. Using hints and limited moves, they search for hidden treasure. The game also displays the shortest path to treasure locations, testing logical thinking and graph traversal concepts.
**Backend Setup (C++ Server)**
Open Dev-C++.
Load the backend source file main.cpp.
In the menu bar, click Tools → Compiler Options.
Navigate to the Linker tab.
In the text field, add the following linker flag:

**-lws2_32**


Click OK to save the changes.
Compile and run the project by pressing** F9.**
A terminal window will appear showing API states and server logs, indicating that the backend server has started successfully.
The terminal will display a message confirming that the server is running on:

**localhost:8080**

**Frontend Setup (Browser)**

After the backend server is running, open the provided HTML frontend file in a web browser.
The frontend will attempt to connect to the backend server at localhost:8080.
If the connection is successful, the game interface will load and backend connectivity will be confirmed.

Project Overview

Treasure Hunt Game is a client-server-based game where the backend is implemented in C++ and serves game state APIs, while the frontend is built using HTML/JavaScript and runs in the browser. The backend and frontend communicate through a local server to enable real-time game interaction.
