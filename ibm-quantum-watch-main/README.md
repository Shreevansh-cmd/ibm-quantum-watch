IBM Quantum Jobs Dashboard

Built by EntangleCoders for AQVH Hackathon 2025

A custom-built dashboard that monitors IBM Quantum jobs and backend status in real time.
This project integrates with the IBM Quantum API (via a FastAPI + Qiskit backend) and visualizes results in a modern React dashboard.

Features

Dashboard Overview – Monitor quantum jobs (queued, running, completed).

Backend Status – See available IBM simulators and real quantum devices with qubits and status.

Secure API Integration – Authentication handled server-side with .env.

Modern UI – Built with React, TailwindCSS, and shadcn/ui.

Tech Stack

Frontend: React, TypeScript, TailwindCSS, Vite, shadcn/ui

Backend: FastAPI (Python), Qiskit IBM Runtime

API: IBM Quantum Cloud API

Getting Started
1. Clone the Repository
git clone https://github.com/your-username/ibm-quantum-dashboard.git
cd ibm-quantum-dashboard

2. Backend Setup
cd backend
pip install -r requirements.txt


Create a .env file:

IBM_QUANTUM_TOKEN=your_api_key_here
IBM_QUANTUM_INSTANCE=ibm-q/open/main


Run backend:

uvicorn main:app --reload

3. Frontend Setup
cd frontend
npm install
npm run dev


Access app at → http://localhost:5173

Demo Flow

Build or submit a quantum circuit in IBM Quantum Composer or Quantum Lab.

A new Job ID will be generated.

Refresh this dashboard and the job appears with status updates (Queued → Running → Completed).

Hackathon Pitch

“Our project provides a simple and user-friendly dashboard for monitoring IBM Quantum jobs and backend availability. Instead of relying on IBM’s default interface, we built a custom tool that connects securely to the IBM Quantum API and presents data in a clean, modern UI. This makes quantum computing workflows more accessible for students, developers, and researchers.”

Team: EntangleCoders