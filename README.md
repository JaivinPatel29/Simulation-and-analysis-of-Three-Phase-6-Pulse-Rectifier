# Simulation-and-analysis-of-Three-Phase-6-Pulse-Rectifier
In this project as the name suggests, a Three-Phase 6 pulse rectifier has been simulated on simulink.
The simulink file in (.slx) format has been attached for anyone who wants to simulate the model.
The per phase source voltage is kept 254V at 50Hz so as to obtain 440V line voltage which can be observed at the output display block.
A doide block containing series R-C Snubber circuit has been used. Default values are used for snubber resistance and capacitance.
The outuput of the recitifier is fed to a resistor branch of 100 ohms.
Scopes have been kept to obtain and analyze the input/output voltage waveforms as well as the input current waveforms. 
Harmonic ripples were observed in each phase of the input current. It is suggested to add an inductor of appropriate value in series with the input to damp out the ripple.
The output waveform is observed to be pulsating DC. It is suggested to use a fliter circuit to convert the pulsating DC into smooth DC before feeding the output to the load.
