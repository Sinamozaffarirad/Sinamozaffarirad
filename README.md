# Hi, I'm Sina Mozaffari Rad

M.Sc. student in Computer Engineering (Computer Systems Architecture) at the University of Tehran. I did my
B.Sc. in Computer Engineering at the University of Kashan.

During my master's I want to work on hardware for AI: accelerator architectures, the on-chip networks that
move data between their processing elements, and the hardware/software co-design that decides what runs where.

## Current work

| Project | What it is |
|---------|------------|
| [Approximate MAC units for DNN accelerators](https://github.com/GitCodingMates/approx-mac-dnn) | Cheaper multipliers for int8 DNN accelerators, from Python models to verified and synthesized Verilog. Truncation cuts MAC area by 39 % for under 0.5 % MNIST accuracy loss.  |

The projects below are from my bachelor's, in computer architecture, NoC modelling, embedded systems, data
mining, signal processing and AI. 

## Hardware, embedded and co-design

| Project | What it is |
|---------|------------|
| [Application mapping: shared bus vs 4×4 mesh NoC](https://github.com/Sinamozaffarirad/application-mapping-petri-nets) | Timed Petri net models (MATLAB) of one application mapped onto 16 PEs. With contention modelled, my NoC mapping was slower than the bus (37 vs 35), which showed me how much mapping matters. |
| [FFT8: static vs dynamic dataflow scheduling](https://github.com/Sinamozaffarirad/fft8-hardware-software-codesign) | An 8-point FFT as four dataflow actors in C++, run with a static schedule, a FIFO-driven schedule and one thread per actor. |
| [Indoor air quality monitor](https://github.com/Sinamozaffarirad/IoT-Air-Quality-Monitoring) | ESP8266 with five sensors on one I²C bus, cross-sensor temperature compensation, change-based MQTT, Node-RED and a Streamlit dashboard. |
| [ATmega32 laser engraver](https://github.com/Sinamozaffarirad/atmega32-laser-engraver) | Bare-metal C on an AVR: Bresenham lines and midpoint circles driven as stepper-motor steps, keypad + GLCD interface, Proteus simulation. |
| [Traffic light controller (VHDL)](https://github.com/Sinamozaffarirad/synchronous-traffic-controller-vhdl) | Clocked FSM with a latched pedestrian request, verified in ModelSim by a self-checking testbench. |

## Data mining and machine learning

| Project | What it is |
|---------|------------|
| [Decision-support system for a physical retail store](https://github.com/Sinamozaffarirad/dunnhumby-market-data-mining) | B.Sc. final project, team of three. Django + SQL Server over 2.6M Dunnhumby transactions: association rules, repurchase prediction (ROC-AUC 0.873), revenue forecasting, churn prediction (ROC-AUC 0.882), RFM, a hybrid recommender and a BI dashboard with significance tests. |
| [Neural network exercises (Soft Computing)](https://github.com/Sinamozaffarirad/soft-computing-neural-networks) | Adaline and perceptron on Iris, and a two-hidden-layer network that solves XOR, with my own training loops in PyTorch. |

## Signal processing, vision and NLP

| Project | What it is |
|---------|------------|
| [Persian speech recognition with MFCC + DTW](https://github.com/Sinamozaffarirad/Persian-Speech-Recognition-DTW) | Team project: single-word recognition and keyword spotting in continuous Persian speech (F1 0.78), with DTW written from scratch. |
| [Paper ballot vote counter](https://github.com/Sinamozaffarirad/Ballot-Vote-Counter-OpenCV) | OpenCV pipeline that reads, validates and counts ballot photos, with skew correction and duplicate detection. |
| [NLP course assignments](https://github.com/Sinamozaffarirad/NLP-Course-Assignments) | N-gram language models, Naive Bayes and Skip-gram written from scratch, partly on Persian text. |
| [Digital image processing in MATLAB](https://github.com/Sinamozaffarirad/Digital-Image-Processing-MATLAB) | Exercises from two image processing textbooks: filtering, restoration, Fourier, morphology. |

## AI: search and constraint satisfaction

| Project | What it is |
|---------|------------|
| [Sudoku as a CSP](https://github.com/Sinamozaffarirad/sudoku-csp-solver) | Backtracking, MRV, degree heuristic and AC-3. MRV + degree visits 8× fewer states on a hard puzzle, but is slower in time, and the README explains why. |
| [8-puzzle solver](https://github.com/Sinamozaffarirad/8-puzzle-solver) | BFS, IDS and A* on a 31-move board (the hardest case), with a solvability check. |
| [Flow puzzle solver](https://github.com/Sinamozaffarirad/flow-puzzle-solver) | A* path per colour plus backtracking over the colour order. |
| [Tic-Tac-Toe with minimax](https://github.com/Sinamozaffarirad/tic-tac-toe-minimax) | Minimax with alpha-beta pruning; never loses against any of the 782 possible human strategies. |

## Tools I've used

**Hardware / embedded:** Verilog, VHDL, ModelSim, Yosys, C, AVR (CodeVisionAVR), ESP8266 (Arduino), Proteus, LogicWorks, MQTT, Node-RED
**Software:** C++, Python (NumPy, PyTorch, Django, XGBoost, OpenCV, librosa, scikit-learn, pandas), MATLAB, SQL Server
