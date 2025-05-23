Xylem Innovation Challenge 2025 - Project Ideas

Drone-Based Wildlife Rescue and Monitoring System for the Sundarbans
(Dual Challenge: Water-Related Disaster Management + Climate Resilience & Biodiversity Protection)
Objective:
Use AI-enabled drones with edge computing (RISC-V + FPGA) for real-time wildlife detection, tracking, and rescue coordination in disaster-impacted regions of the Sundarbans.

Key Features:
AI-Driven Wildlife Detection:


Onboard camera + thermal + IR sensors.


FPGA accelerates CNN models (e.g., YOLO, MobileNet) for detecting injured, stranded, or panicked animals in dense foliage.


Real-Time Tracking & Mapping:


RISC-V handles GPS tagging, path prediction, and sends location updates to forest division or rescue teams.


Edge processing minimizes data transmission, crucial in low-connectivity areas.


Disaster-Aware Navigation:


GIS and real-time weather data integration for dynamic drone pathing and safe operation.


Avoids flood zones, strong wind zones, etc.


Rescue Assistance:


Optional micro-drone swarm coordination to herd or guide animals.


Can drop lightweight emergency supplies (food, water, first-aid) to stranded wildlife.


Power & Communication:


Solar-recharging drone stations in key areas.


LPWAN/satellite communication for updates.



Impact:
Protect endangered species like the Bengal tiger, fishing cats, and estuarine crocodiles.


Minimize wildlife casualties during floods, cyclones, or tidal surges.


Create a model for drone-aided biodiversity protection in coastal forests worldwide.



Enhancement Suggestions:
Add a wildlife distress audio classifier (edge ML model) to pick up animal cries during disasters.


Include thermal image anomaly detection for spotting animals in night or fog conditions.


Develop a web-based dashboard for live monitoring and drone coordination by forest officials.

🗓️ Project Timeline (May 21 – June 21)
⏳ Total Duration: 5 Weeks

✅ Week 1: May 21 – May 27
Goal: Finalize project design, assign roles, start prototyping
All:


Final project brainstorming & feature freeze.


Finalize system architecture diagram.


Set up shared Git, Notion/Google Drive, and task board.


Nayem (AI/ML):


Collect relevant animal imagery/thermal datasets.


Design detection pipeline (e.g., YOLOv5, MobileNet).


Begin training prototype model.


Rizwana (FPGA/RISC-V):


Research and select FPGA board (e.g., TinyML-compatible).


Set up a development environment.


Prepare test setup for inferencing.


Lian (Drone):


Finalize drone specs (flight time, payload, camera/sensors).


Order required components.


Jubaer (Docs):


Start project proposal doc & script rough video outline.



✅ Week 2: May 28 – June 3
Goal: Begin integration of AI + FPGA + drone hardware
Nayem:


Finish initial training.


Export quantized model (e.g., ONNX, TFLite).


Begin tests on thermal and visible camera input.


Rizwana:


Implement basic inference model on FPGA (e.g., dummy image classifier).


Work on I/O interface for drone-mounted camera feed.


Lian:


Assemble drone frame.


Integrate camera module + GPS + IR/thermal sensors.


Test flight controls.


Jubaer:


Design slide layout, animation plan.


Begin writing script for video narration and proposal.



✅ Week 3: June 4 – June 10
Goal: Full edge pipeline integration & field test
All:


Conduct dry run of end-to-end workflow: drone → camera → FPGA → inference → location output.


Nayem + Rizwana:


Optimize model for edge: pruning/quantization.


Validate model on FPGA with live data.


Lian:


Conduct test flight with camera + GPS logging.


Coordinate with Nayem to test in semi-natural environment (e.g., park/forest).


Jubaer:


Capture test footage.


Draft video demo clips.


Finish proposal draft.



✅ Week 4: June 11 – June 17
Goal: Finalize deliverables, polish everything
Nayem:


Refine AI models based on test results.


Add robustness (night vision, foggy detection if possible).


Rizwana:


Optimize power efficiency.


Prepare FPGA documentation and benchmarking.


Lian:


Create drone wiring diagrams and bill of materials (BoM).


Record flight demos.


Jubaer:


Finalize slide deck and script.


Begin editing final video (~3-5 mins).


Prepare visuals for poster/summary.



✅ Week 5: June 18 – June 21
Goal: Submit final project with all documentation and media
All:


Final review session with mock pitch.


Double-check all technical documentation.


Jubaer:


Submit video, slide deck, poster, technical write-up.


Ensure all submission requirements are met (format, naming, etc.).



🎯 Tools to Use:
Task Management: Trello, Notion, or GitHub Projects


Version Control: Git/GitHub for AI/FPGA code


Collab Tools: Google Drive, Slides, Meet


Video Editing: DaVinci Resolve, CapCut, or Adobe Premiere


Presentation Format: PDF + MP4 + Docs (as per Xylem guidelines)



