# optoPAD-software
Bonsai workflow used for control and data acquisition of the optoPAD (Moreira et al., 2019). Requires the visual programming language Bonsai (https://bonsai-rx.org/). This repository contains the following workflow/protocols:
- `optoPAD_Fig4B_Reversal`: script for the dynamic virtual taste reality experiment (see Fig. 4A-B).
- `optoPAD_general`: script used for most experiments in the manuscript (Moreira et al., 2019). Contains parameters to change delay, sustain, probability and color of the stimulation. See Moreira et al., 2019 for more details.
- `optoPAD_openloop`: script for triggering light activation in open loop, meaning in a predefined pattern, not contingent on the behavior of the
animal.
- `optoPAD_StimEndActBout`: script that allows the user to stimulate after the end of an activity bout. Requires Bonsai version 2.4.
- `optoPAD_stimulicounter`: script for limiting the number of stimulations given.
