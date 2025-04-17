# Advanced-Ambulance-Route-Optimizer-Using-Dijkstra-s-Algorithm-with-Real-Time-Traffic
Advanced Ambulance Route Optimizer Using Dijkstra's Algorithm with Real-Time Traffic                                  

🚑 Advanced Ambulance Route Optimizer
Using Dijkstra's Algorithm with Real-Time Traffic Simulation

Demo Screenshot (Replace with actual screenshot)

📌 Overview
A web-based visualization tool that calculates the shortest path for ambulances using Dijkstra's algorithm, with dynamic traffic simulation to mimic real-world conditions.

Key Features
🗺️ Interactive graph visualization of hospitals and routes

⏱️ Real-time path calculation with time estimates

🚦 Traffic simulation with adjustable intensity

🏥 Hospital nodes highlighted for quick identification

🛠️ Technologies Used
Frontend: HTML5, CSS3, JavaScript (Vanilla JS)

Algorithms: Dijkstra's shortest path (Priority Queue implementation)

Visualization: SVG dynamic rendering

🚀 How to Run
Clone the repository:

bash
Copy
git clone https://github.com/your-username/ambulance-route-optimizer.git
Open the project:

Navigate to the project folder and open index.html in any modern browser (Chrome/Firefox/Edge).

🖥️ Usage Guide
Select Nodes:

Choose a start node (e.g., "A" for Ambulance) and destination node (e.g., "H1" for Hospital 1).

Find Shortest Path:

Click "Find Shortest Path" to highlight the optimal route in yellow.

Simulate Traffic:

Adjust the traffic slider (1-10) and click "Simulate Traffic" to dynamically update edge weights.

Recalculate the path to see traffic-adjusted results.

📊 Graph Structure
mermaid
Copy
graph LR
    A -->|4| B
    A -->|2| C
    B -->|5| H1
    B -->|1| C
    C -->|3| H2
    H1 -->|2| H2
📂 Project Structure
Copy
ambulance-route-optimizer/
├── index.html          # Main HTML file
├── README.md           # This documentation
└── (Optional: assets/  # For screenshots/fonts)
🤝 Contributing
Contributions are welcome! Open an issue or submit a PR for:

🐛 Bug fixes

🚀 Performance optimizations

🌟 New features (e.g., A* algorithm, live traffic API integration)

<img width="785" alt="Screenshot 2025-04-17 at 15 32 21" src="https://github.com/user-attachments/assets/ff4affb9-b6d7-4edc-94db-71835899b4b3" />

<img width="785" alt="Screenshot 2025-04-17 at 15 32 27" src="https://github.com/user-attachments/assets/9e2a62ff-ba95-4aa8-b511-f0dadc899e93" />
