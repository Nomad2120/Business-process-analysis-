# Business Process Analysis - Beeline Installment MVP

## Project Overview
This MVP prototype demonstrates the optimized **To-Be** process for online installment purchases on the Beeline Kazakhstan e-commerce platform (shop.beeline.kz). The prototype was developed as part of the Business Process Analysis course at Astana IT University.

## Team
- **Diana Kim** (ADA-2403M) - Improvement Plan & Report Lead
- **Zhanel Rymkhanova** (ADA-2403M) - BPMN Architect
- **Zhanibek Meiramkan** (ADA-2404M) - Quantitative Analyst & MVP Developer

## Features
| Feature | Description |
|---------|-------------|
| 🖥️ **Client View** | Replicates the shop.beeline.kz interface with auto-fill functionality |
| 🏦 **Bank Backshop Dashboard** | Real-time process visualization for bank operators |
| ⚡ **Parallel Processing** | Interactive demonstration of credit scoring and inventory check running simultaneously |
| 🔄 **View Toggle** | Switch between client and bank perspectives |
| 📋 **Process Log** | Timestamped events for audit trail |
| 📊 **KPI Metrics** | Display showing time savings and process improvements |

## Applied Process Redesign Heuristics
- **Automation** - Customer data auto-filled from Beeline subscriber database
- **Activity Elimination** - Single OTP instead of two separate confirmations
- **Parallelism** - Credit scoring and inventory check executed simultaneously

## Technology Stack
- **HTML5** - Document structure
- **CSS3** - Styling with Flexbox and Grid layouts
- **JavaScript (ES6+)** - Application logic

> No external frameworks or libraries required. The application is self-contained and can be opened directly in any modern web browser.

## Quick Start
1. Clone the repository:
```bash
   git clone https://github.com/[your-username]/Business-process-analysis-.git
```
2. Open `MVP_Combined_Client_Bank.html` in any modern web browser
3. Click "Start Demo" to begin the process simulation

## Project Structure
```
📁 Business-process-analysis-
├── 📄 MVP_Combined_Client_Bank.html    # Main MVP application (~1,600 lines)
├── 📄 README.md                         # This file
└── 📁 docs/                             # Documentation (optional)
    ├── 📄 BPMN_AsIs.pdf
    └── 📄 BPMN_ToBe.pdf
```

## Performance Improvements
| Metric | As-Is | To-Be | Improvement |
|--------|-------|-------|-------------|
| Total Process Time | ~8 min | ~5 min | **-37.5%** |
| OTP Confirmations | 2 | 1 | **-50%** |
| Manual Data Inputs | 4 | 0 | **-100%** |
| Parallel Time Saved | - | 2 sec | **New** |

## Course Information
- **Course:** Business Process Analysis
- **University:** Astana IT University
- **Trimester:** 2, 2025-2026
- **Instructor:** Nurkhat Ibadildin

## License
This project is developed for educational purposes as part of Team Project 2.
