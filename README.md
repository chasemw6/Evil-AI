# Evil-AI
Budget local AI phishing simulation lab — testing whether a quantized open-source LLM running on legacy hardware (GTX 1050 Ti) can assist in building and analyzing a controlled, isolated phishing simulation for cybersecurity coursework.


Budget Local AI Phishing Simulation Lab

This project investigates whether a quantized, locally-hosted AI model (via Hugging Face) can assist in constructing and analyzing a controlled, isolated phishing simulation running entirely on legacy consumer hardware (GTX 1050 Ti).

The goal is educational: to evaluate AI capabilities, hardware limitations, and the forensic evidence generated during a simulated phishing interaction — not to build or deploy a real phishing tool.

Scope & Safety
All testing occurs on an isolated network with no external exposure.
Only predetermined dummy credentials are used — no real accounts or data are targeted.
The "victim" machine is the author's own test computer, intentionally accessing a simulated landing page.
This repo documents a coursework project (IS4543) and is not intended for use against real users or systems.
Milestones
Hardware & Local AI Setup – Configure Linux + quantized LLM on the GTX 1050 Ti; document performance and limitations.
AI-Generated Landing Page – Test the model's ability to generate a simulated password-reset page; document corrections needed.
Controlled Simulation – Host and access the page across isolated machines; log workflow behavior.
Traffic & Log Analysis – Capture and analyze traffic (Wireshark/tcpdump) and compare with the AI's own interpretation.
Final Evaluation – Assess overall feasibility of using budget hardware + local AI for this type of security research.
