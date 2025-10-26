# Bank Queue Discrete Event Simulation

A discrete event simulation system modeling a bank queue with multiple tellers and priority-based customer service.

## 🎓 Academic Project
Completed as part of Algorithms & Data Structures at University of Wollongong  
**Grade Achieved:** High Distinction (HD)

## 📋 Overview
This project implements a discrete event simulation to model and analyze bank queue behavior with:
- Multiple bank tellers (configurable 1-4)
- Priority-based customer service
- Custom heap data structure implementations
- Comprehensive performance statistics

## 🔑 Key Features
- **Priority Queue System** - Max heap implementation for customer ordering
- **Event-Driven Architecture** - Min heap for chronological event processing
- **Custom Data Structures** - Heap implementations built from scratch
- **Performance Analytics** - Queue statistics, wait times, teller utilization

## 🛠️ Technical Implementation

### Data Structures
- **Max Heap** - Priority queue for customers (priority + arrival time ordering)
- **Min Heap** - Event queue for chronological event processing
- **Custom Classes** - Customer, BankTeller, Event, Statistics

### Algorithms
- Heap sift-up and sift-down operations
- Discrete event simulation loop
- Priority-based scheduling
- Real-time statistics tracking

## 📊 Statistics Tracked
- Average waiting time
- Average service time
- Maximum queue length
- Average queue length
- Teller utilization rates
- Customers served per teller

## 🚀 Usage
```bash
python priority-queue-simulation.py
```

When prompted, enter a data file name (or press Enter to use default `sample.txt`)

### Input Format
```
arrival_time service_time priority
1.5 3.2 1
2.0 2.5 2
0 0  # Terminator
```

## 📈 Example Output
```
RESULTS FOR SIMULATION WITH 2 TELLERS
----------------------------------------
Total customers served: 100.00
Average waiting time: 2.45
Maximum queue length: 8.00
Teller 1: 52 customers, 15.3% idle
Teller 2: 48 customers, 18.7% idle
```

## 🎯 Learning Outcomes
- Implemented heap data structures from scratch
- Designed discrete event simulation systems
- Applied priority scheduling algorithms
- Analyzed queueing theory principles

## 📝 Technical Notes
- Uses custom heap implementations instead of Python's `heapq` library
- Employs object-oriented design principles
- Handles edge cases with proper error handling

## 🔧 Technologies
- **Language:** Python 3.x
- **Paradigm:** Object-Oriented Programming
- **Core Concepts:** Data Structures, Algorithms, Simulation

## 📄 License
MIT License - Academic project, free to use for educational purposes

---

*Developed as part of computer science coursework at the University of Wollongong*
```

### 2. **Add These Files:**

**Create a sample data file (`sample.txt`):**
```
1.0 2.5 1
1.5 3.0 2
2.0 1.5 1
2.5 2.0 3
0 0
```

**Create `.gitignore`:**
```
## Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python

## IDE
.vscode/
.idea/
*.swp

## Data files (if you want to exclude large test files)
*.txt
!sample.txt
```

**Create `requirements.txt`:**
```
## No external dependencies required - uses only Python standard library
```

**Create `LICENSE`:**
Use MIT License (standard for academic projects)

### 3. **Repository Topics/Tags:**
```
python
data-structures
algorithms
discrete-event-simulation
heap
priority-queue
simulation
queueing-theory
object-oriented-programming
computer-science
academic-project

## ⚠️ Academic Integrity Notice
This project is shared for portfolio purposes only. If you are a student taking a similar course:
- Do not copy this code for your assignments
- Use it only as a learning reference
- Understand your institution's academic integrity policies
