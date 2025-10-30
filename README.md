# Colosseum Hackathon Submission

This repository contains the three main components of the Colosseum project as submodules to maintain the complete commit history from the hackathon period.

## Components

The project is divided into three main components:

- **Backend**: [embedded-backend](backend/) - Contains the backend services
- **Frontend**: [embedded-frontend](frontend/) - Contains the frontend application  
- **Unity**: [embedded-Unity](unity/) - Contains the Unity game client

## Purpose

This monorepo structure was created for hackathon submission purposes while preserving the original repository structure and complete commit history that shows the development progress during the hackathon.

The original repositories maintain their complete history of commits made during the hackathon period, demonstrating the iterative development process.

## Setup

To clone this repository with all submodules:

```bash
git clone --recursive https://github.com/PsyLabsWeb3/embedded-colosseum.git
```

Or if you've already cloned it:

```bash
git submodule update --init --recursive
```