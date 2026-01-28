# Dining Philosophers Discrete Event Simulation

## Quick Setup

Run this single command to set up and start:

```bash
python3 -m venv venv && source venv/bin/activate && pip install -r requirements.txt && jupyter-lab
```

## Manual Setup

If you prefer step-by-step:

1. Create virtual environment:
```bash
python3 -m venv venv
```

2. Activate virtual environment:
```bash
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Start Jupyter Notebook:
```bash
jupyter-lab
```

## Project Structure

- `dining_philosophers.ipynb` - Main simulation notebook with Tasks 1-3 implemented
- `requirements.txt` - Python dependencies

## Implemented Tasks

- Task 1: Basic Simulation (5 philosophers, 100 time units)
- Task 2: Deadlock Detection
- Task 3: Deadlock Prevention (priority ordering + timeout strategies)

## Deactivate Environment

When done:
```bash
deactivate
```
