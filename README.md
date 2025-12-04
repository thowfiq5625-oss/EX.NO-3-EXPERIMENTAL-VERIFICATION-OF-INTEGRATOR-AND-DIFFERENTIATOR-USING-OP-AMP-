3. ##**EX.NO:
** 3  EXPERIMENTAL VERIFICATION OF INTEGRATOR AND DIFFERENTIATOR USING OP-AMP 
            
**DATE:**  
             3A INTEGRATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
INTEGRATOR
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as,
Vo = - (1/Rf C1 ) ∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.
CIRCUIT DIAGRAM
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 21 39 19_4f1423e3](https://github.com/user-attachments/assets/05728b8e-406b-4d14-ad7c-49e6c1e0c853)



## MODEL GRAPH
<img width="556" height="380" alt="image" src="https://github.com/user-attachments/assets/caa7461c-69f7-4636-8e31-eea6db6efbb5" />

<img width="847" height="553" alt="image" src="https://github.com/user-attachments/assets/d8d3e586-8e58-47ba-baae-2794c7955d51" />

---

## DESIGN

![WhatsApp Image 2025-12-04 at 11 02 07_73d7f8c9](https://github.com/user-attachments/assets/a0b4e07f-fd45-4829-b877-f897875d9659)
	

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


## TABULATION
![WhatsApp Image 2025-11-30 at 21 39 20_6374cb21](https://github.com/user-attachments/assets/61dc6118-3f2c-4155-9782-31122c1f3a4b)


---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 16 56 24_64e9fd99](https://github.com/user-attachments/assets/1c813445-59a4-4d99-ab7d-c569f95a7955)P

---
**DATE:**  
             3 B DIFFERENTIATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,
Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1.	Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 µF, calculate the value of Rf.
2.	Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.

The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 21 46 58_2e20ac21](https://github.com/user-attachments/assets/52903815-3e9f-41ea-bf30-b6f61e2bf1a0)



## MODEL GRAPH

(i)	 SINE WAVE INPUT

<img width="687" height="479" alt="image" src="https://github.com/user-attachments/assets/c89226c0-c2bb-4544-b355-27fc0d923f1a" />
---

AND

(ii) SQUARE WAVE INPUT

<img width="758" height="447" alt="image" src="https://github.com/user-attachments/assets/cda33b00-c40c-490f-a9bd-e06107119c25" />


---

## DESIGN
![WhatsApp Image 2025-12-04 at 11 02 07_73d7f8c9](https://github.com/user-attachments/assets/fb8a0e34-d4f8-444c-8fea-ad5d018f8749)



## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

 ## TABULATION
![WhatsApp Image 2025-11-30 at 21 46 59_4780e6c2](https://github.com/user-attachments/assets/30c6403a-905e-488a-bd30-ba1278335dee)


## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 21 44 36_fc99fb73](https://github.com/user-attachments/assets/f3d82358-3e91-4b13-a8f5-ec7e70ab834f)

---

RESULT:
Thus an Integrator and Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.
---



