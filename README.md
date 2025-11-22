# FairView Recruitment AI

**FairView** is an AI-driven recruitment evaluation platform designed to promote fairness, transparency, and efficiency in the hiring process. By leveraging advanced NLP techniques and AI models, FairView evaluates both candidates and interviewers to reduce bias and improve decision-making quality.

---
## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [System Architecture](#system-architecture)  
- [Installation](#installation)  
- [Usage](#usage)  
- [AI Engine](#ai-engine)  
- [Evaluation Metrics](#evaluation-metrics)  
- [Future Enhancements](#future-enhancements)  
- [Project Timeline & Budget](#project-timeline--budget)  
- [Dataset Details](#dataset-details)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Overview

FairView integrates real-time video interviewing with AI-powered evaluation using Retrieval-Augmented Generation (RAG) and Model Context Protocol (MCP). The system scores candidates on content relevance, sentiment, and coherence while simultaneously assessing interviewer fairness and bias.

---

## Features

- Role-based user management (Candidates, Interviewers, Admin)  
- Real-time video conferencing with integrated live code editor  
- AI-powered evaluation engine for bias-aware scoring  
- Detailed candidate and interviewer performance reports  
- Scalable web platform using React.js, Node.js, and Python AI backend  
- Secure role-based access and data privacy controls  

---

## System Architecture

- **Frontend:** React.js UI for interviews, dashboards, and reports  
- **Backend:** Node.js and Express server managing user sessions and reports with MongoDB  
- **AI Engine:** Python Flask app using Hugging Face transformers for RAG, sentiment, and bias detection  
- **Communication:** RESTful APIs between frontend, backend, and AI engine  

![System Architecture](architecture.png)

---

## Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/fairview-recruitment-ai.git
