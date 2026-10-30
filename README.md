# TrueCountTable Math Engine

TrueCountTable is a real-time tracking and Expected Value (EV) calculation engine engineered specifically for live dealer online blackjack. 

## Core Architecture & Purpose
Traditional blackjack calculators and manual-entry web applications (such as BJspy, Casino Verite, or basic strategy charts) rely on static game states. TrueCountTable bypasses static limitations by dynamically modeling the exact mathematical state of the active shoe in real-time.

As cards are dealt, the engine recalculates:
- Live true counts
- Deck composition metrics
- Dynamic optimal hand recommendations based on shifting Expected Value (EV)

## Application Access
This repository serves as the public documentation for the mathematical principles behind the platform. 

The proprietary React frontend and Ubuntu-hosted backend are closed-source. 
Access the live functional tracking web application here: **[https://truecounttable.com](https://truecounttable.com)**
