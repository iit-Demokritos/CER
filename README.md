# <img align="left" src="figures/cer_logo.png" width="40"> &nbsp; Complex Event Recognition Group 

## About the Group
We have been developing formal computational methods which take as input streams of low-level
events, e.g. sensor-based events, such as a change in temperature, and combine them to infer
complex high-level events of interest, such as the start of a fire incident or a fault in the
cooling system of a vehicle. Our methods support real-time event recognition over high-velocity
data streams, online structure learning for accurate event recognition over noisy relational
streams, as well as complex event forecasting for proactive decision-making.
**An overview of our research activities may be found in this [paper](https://sigmodrecord.org/publications/sigmodRecord/1806/pdfs/09_Centers_Alevizos.pdf)
and this [presentation](http://cer.iit.demokritos.gr/blog/talks/cer/), while latest news, running projects and other information can be found in our [webpage](https://cer.iit.demokritos.gr/).**

## Some Applications
Some applications in which we have applied our methods:

 - **[Maritime Situational Awareness](http://cer.iit.demokritos.gr/blog/applications/maritime_surveillance/)**: Analyze vessel position streams to detect in real-time dangerous, suspicious and illegal activities.
 - **[Fleet Management](http://cer.iit.demokritos.gr/blog/applications/fleet_management/)**: Analyze vehicle position streams for real-time fleet management.
 - **[Activity Recognition](http://cer.iit.demokritos.gr/blog/applications/activity_recognition/)**:  Analyze camera feeds for real-time assisted daily living.
 - **[Forecasting in cancer cell simulations](http://cer.iit.demokritos.gr/blog/applications/life_sciences/)**: Forecast the outcome of cancer cell simulations, in order to optimise the use of resources on which they run.

## Software repositories
 
| Project                                                          | Description                                                                                                                                                                            | Language      | Licence  |
|------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|----------|
| [RTEC](https://github.com/aartikis/RTEC)                         | Event Calculus for Run-Time reasoning. RTEC is an Event Calculus dialect optimised for data stream reasoning.                                                                                                                                                | Prolog        | LGPL-3.0 |
| [Incremental RTEC](https://github.com/eftsilio/Incremental_RTEC) | Incremental Run-Time Event Calculus i.e., a version of RTEC for incremental reasoning.                                                                                                 | Prolog        |          |
| [oPIEC](https://github.com/Periklismant/oPIEC)                   | Online Probabilistic Interval-based Event Calculus. oPIEC is an implementation of the Event Calculus handling the uncertainty of data streams.                                         | Prolog, Python | LGPL-3.0 |
| [OLED](https://github.com/nkatzz/ORL)                            | Online Learning of Event Definitions. OLED is an online Inductive Logic Programming (ILP) system for learning logical theories from data streams.                                      | Scala         | GPL-3.0  |
| [Wayeb](https://github.com/ElAlev/Wayeb)                         | Wayeb is a Complex Event Processing and Forecasting (CEP/F) engine written in Scala. It is based on symbolic automata and Markov models.                                               | Scala         | See repo |
| [ETSC](https://github.com/xarakas/ETSC)                          | An Early Time-Series Classification Suite For Benchmarking. A collection of available ETSC algorithms and real-world datasets that can be used for evaluation and comparison purposes. | Python,<br> C++  |          |

