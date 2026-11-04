# Hi, I'm Sina Mozaffari Rad

M.Sc. student in Computer Engineering (Computer Systems Architecture) at the University of Tehran, since
October 2026. I did my B.Sc. in Computer Engineering at the University of Kashan (2021–2026).

I'm most interested in the layer where hardware and software meet: computer architecture, on-chip
communication, hardware/software co-design and embedded systems.

The projects below are from my bachelor's. Most started as course work, but I tried to take each one a step
further than the assignment: measuring results, comparing alternatives, and writing down what didn't work.

## Hardware, embedded and co-design

| Project | What it is |
|---------|------------|
| [Application mapping: shared bus vs 4×4 mesh NoC](https://github.com/Sinamozaffarirad/application-mapping-petri-nets) | Timed Petri net models (MATLAB) of one application mapped onto 16 PEs. With contention modelled, my NoC mapping was slower than the bus (37 vs 35), which showed me how much mapping matters. |
| [FFT8: static vs dynamic dataflow scheduling](https://github.com/Sinamozaffarirad/fft8-hardware-software-codesign) | An 8-point FFT as four dataflow actors in C++, run with a static schedule, a FIFO-driven schedule and one thread per actor. |
| [Indoor air quality monitor](https://github.com/Sinamozaffarirad/IoT-Air-Quality-Monitoring) | ESP8266 with five sensors on one I²C bus, cross-sensor temperature compensation, change-based MQTT, Node-RED and a Streamlit dashboard. |
| [ATmega32 laser engraver](https://github.com/Sinamozaffarirad/atmega32-laser-engraver) | Bare-metal C on an AVR: Bresenham lines and midpoint circles driven as stepper-motor steps, keypad + GLCD interface, Proteus simulation. |
| [Traffic light controller (VHDL)](https://github.com/Sinamozaffarirad/synchronous-traffic-controller-vhdl) | FSM with a pedestrian request in VHDL and LogicWorks, kept with a list of its known bugs and how to fix them. |

## Signal processing, vision and NLP

| Project | What it is |
|---------|------------|
| [Persian speech recognition with MFCC + DTW](https://github.com/Sinamozaffarirad/Persian-Speech-Recognition-DTW) | Team project: single-word recognition and keyword spotting in continuous Persian speech (F1 0.78), with DTW written from scratch. |
| [Paper ballot vote counter](https://github.com/Sinamozaffarirad/Ballot-Vote-Counter-OpenCV) | OpenCV pipeline that reads, validates and counts ballot photos, with skew correction and duplicate detection. |
| [NLP course assignments](https://github.com/Sinamozaffarirad/NLP-Course-Assignments) | N-gram language models, Naive Bayes and Skip-gram written from scratch, partly on Persian text. |
| [Digital image processing in MATLAB](https://github.com/Sinamozaffarirad/Digital-Image-Processing-MATLAB) | Exercises from two image processing textbooks: filtering, restoration, Fourier, morphology. |

## Tools I've used

**Hardware / embedded:** C, VHDL, AVR (CodeVisionAVR), ESP8266 (Arduino), Proteus, LogicWorks, MQTT, Node-RED
**Software:** C++, Python (NumPy, OpenCV, librosa, scikit-learn, pandas), MATLAB
