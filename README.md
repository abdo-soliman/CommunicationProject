# **Communication Project**
A MATLAB simulink simulation for the following digital modulation teqhniques:
- ### BPSK
- ### QPSK
- ### FSK
- ### QAM-16
- ### QAM-64

# BPSK (Binary Phase-Shift Keying Modulation)
>Binary Phase Shift Keying (BPSK) is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

- ### The simulink diagram would be like the following
![BPSK Simulink Diagram](/BPSK/diagram.png)

- ### Set The RandomIntegerGenerator parameters would be as the following
![RandomIntegerGenerator Paramters](/BPSK/RandomIntergerParameters.png)

- ### If you run the simulation you would get the following diagrams (Before Noiseon left and After Noise right)
![Before Noise Diagram](/BPSK/BerforeNoise.png) ![After Noise Diagram](/BPSK/AfterNoise.png)

- ### To start bit error analysis run the matlab command in the command window
```sh
>> bertool
```

- ### Now to get the Theoritcal and monte carlo results choose the following settings respectivly
![bertool theoritical](/BPSK/TheoriticalParamters.png)
![bertool monte carlo](/BPSK/MonteCarloParamters.png)

**note**
In monte calro we have to choose the appropriate simulink file and set the variable name to the name of the ber block in the simulink diagram

- ### The result should be the following graph
![bertool result graph](/BPSK/SimulationCurve.png)

# FSK (Frequency Shift Keying)
>Frequency Shift Keying (FSK) is the digital modulation technique in which the frequency of the carrier signal varies according to the digital signal changes. FSK is a scheme of frequency modulation.

- ### The simulink diagram would be like the following
![FSK Simulink Diagram](/FSK/diagram.png)

- ### Set the FSK Modulator parameters to the following
![RandomIntegerGenerator Paramters](/FSK/ModulatorParameters.png)

- ### Set the RandomIntegerGenerator parameters to the following
![RandomIntegerGenerator Paramters](/FSK/RandomIntergerParameters.png)

- ### If you run the simulation you would get the following diagrams (Before Noiseon left and After Noise right)
![Before Noise Diagram](/FSK/BeforeNosie.png) ![After Noise Diagram](/FSK/AfterNosie.png)

- ### start bit error analysis like before

- ### Now to get the Theoritcal and monte carlo results choose the following settings respectivly
![bertool theoritical](/FSK/TheoriticalParamters.png)
![bertool monte carlo](/FSK/MonteCarloParamters.png)

- ### The result should be the following graph
![bertool result graph](/FSK/SimulationCurve.png)

# QPSK (Quadrature Phase Shift Keying)
>Quadrature Phase Shift Keying (QPSK) is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, or 270 degrees). QPSK allows the signal to carry twice as much information as ordinary PSK using the same bandwidth. QPSK is used for satellite transmission of MPEG2 video, cable modems, videoconferencing, cellular phone systems, and other forms of digital communication over an RF carrier.

- ### The simulink diagram would be like the following
![QPSK Simulink Diagram](/QPSK/diagram.png)

- ### Set the RandomIntegerGenerator parameters to the following
![RandomIntegerGenerator Paramters](/QPSK/RandomIntergerParameters.png)

- ### If you run the simulation you would get the following diagrams (Before Noiseon left and After Noise right)
![Before Noise Diagram](/QPSK/BeforeNosie.png) ![After Noise Diagram](/QPSK/AfterNosie.png)

- ### start bit error analysis like before

- ### Now to get the Theoritcal and monte carlo results choose the following settings respectivly
![bertool theoritical](/QPSK/TheoriticalParamters.png)
![bertool monte carlo](/QPSK/MonteCarloParamters.png)

- ### The result should be the following graph
![bertool result graph](/QPSK/SimulationCurve.png)

# QAM
>QAM (quadrature amplitude modulation) is a method of combining two amplitude-modulated (AM) signals into a single channel, thereby doubling the effective bandwidth.

## QAM16
- ### The simulink diagram would be like the following
![QAM16 Simulink Diagram](/QAM16/diagram.png)

- ### Set the QAM16 Modulator parameters to the following
![RandomIntegerGenerator Paramters](/QAM16/ModulatorParameters.png)

- ### Set the RandomIntegerGenerator parameters to the following
![RandomIntegerGenerator Paramters](/QAM16/RandomIntergerParameters.png)

- ### If you run the simulation you would get the following diagrams (Before Noiseon left and After Noise right)
![Before Noise Diagram](/QAM16/BeforeNosie.png) ![After Noise Diagram](/QAM16/AfterNosie.png)

- ### start bit error analysis like before

- ### Now to get the Theoritcal and monte carlo results choose the following settings respectivly
![bertool theoritical](/QAM16/TheoriticalParamters.png)
![bertool monte carlo](/QAM16/MonteCarloParamters.png)

- ### The result should be the following graph
![bertool result graph](/QAM16/SimulationCurve.png)

## QAM64
- ### The simulink diagram would be like the following
![QAM64 Simulink Diagram](/QAM64/diagram.png)

- ### Set the QAM64 Modulator parameters to the following
![RandomIntegerGenerator Paramters](/QAM64/ModulatorParameters.png)

- ### Set the RandomIntegerGenerator parameters to the following
![RandomIntegerGenerator Paramters](/QAM64/RandomIntergerParameters.png)

- ### If you run the simulation you would get the following diagrams (Before Noiseon left and After Noise right)
![Before Noise Diagram](/QAM64/BeforeNosie.png) ![After Noise Diagram](/QAM64/AfterNosie.png)

- ### start bit error analysis like before

- ### Now to get the Theoritcal and monte carlo results choose the following settings respectivly
![bertool theoritical](/QAM64/TheoriticalParamters.png)
![bertool monte carlo](/QAM64/MonteCarloParamters.png)

- ### The result should be the following graph
![bertool result graph](/QAM64/SimulationCurve.png)
