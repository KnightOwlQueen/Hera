Hera Alliance | Network Subscription Interface
A high-end, glassmorphism-inspired subscription and onboarding flow. This project demonstrates a seamless transition from a tiered pricing model to a live node-provisioning dashboard.

🌌 Project Overview
The Hera Alliance interface is built for "Sovereign Users" requiring high-level network access. The architecture focuses on UX fluidity, using URL parameters to pass state across a static environment without the need for a heavy backend database.

🔑 Core Features
Dynamic Pricing Tiers: Three distinct access levels (Core, Sovereign, Enterprise) with interactive initialization triggers.

Intelligent Cart System: Handles plan selection, quantity adjustments, and "Node Decommissioning" (item removal) with real-time subtotal updates.

Encrypted-Style Checkout: A dual-pane terminal for secure entry of contact and payment data.

Live Provisioning Dashboard: A success state that simulates real-time network integration through animated progress telemetry.

🛠️ Technical Stack
Frontend: HTML5, CSS3

Styling: Tailwind CSS (Utility-first framework)

Animations: AOS (Animate On Scroll)

Typography: Cinzel (Serif) & Inter (Sans-serif) via Google Fonts

State Management: JavaScript URLSearchParams API

📂 File Structure
Bash
├── index.html          # Landing page & Pricing Table
├── cart.html           # Item review & Quantity adjustment
├── checkout.html       # Secure payment & Node registry
├── success.html        # Live Node Dashboard & Confirmation
└── README.md           # Documentation

MIT License

Copyright (c) 2026 Hera Alliance

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.