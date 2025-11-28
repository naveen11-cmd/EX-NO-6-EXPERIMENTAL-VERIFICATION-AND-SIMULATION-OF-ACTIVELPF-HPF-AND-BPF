# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
# 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP

**DATE:24/9/25          
---
## AIM           
**DATE:**          
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter
---
** 6 A :- LOW PASS FILTER**

## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 16 21 45_668de863](https://github.com/user-attachments/assets/edadd5cd-c556-4395-b197-d5ff5ce7831c)

## SIMULATION CIRCUIT DIAGRAM

<img width="1280" height="721" alt="image" src="https://github.com/user-attachments/assets/0bfa6471-7132-4111-8c02-3a35691047af" />


## MODEL GRAPH
<img width="913" height="559" alt="image" src="https://github.com/user-attachments/assets/c8d28c41-6f3e-44a6-a9da-2b798cf07346" />

---
## DESIGN

![WhatsApp Image 2025-11-28 at 16 24 05_f1ac161e](https://github.com/user-attachments/assets/b6b8ae5f-70e9-4bc8-9117-8372d85f3b83)

## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.

## TABULATION

![WhatsApp Image 2025-11-28 at 17 25 28_117ffd52](https://github.com/user-attachments/assets/6518bb8e-bc1b-46c5-ace8-66dc1d42e7b8)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 16 31 17_dad105db](https://github.com/user-attachments/assets/17f46e75-9409-425a-a777-7d6b8defeffc)

---
## SIMULATION OUTPUT
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/23c00988-0f6a-478e-ab43-67d307fab35d" />

 ## 6 B HIGH PASS FILTER
---
## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-28 at 16 22 36_d0c4b930](https://github.com/user-attachments/assets/a9d67c06-83ef-454e-bee4-f87d57b8576b)

## SIMULATION CIRCUIT DIAGRAM
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/836e5826-7d3e-4fd5-ad22-8667996d4552" />

## MODEL GRAPH
<img width="1005" height="382" alt="image" src="https://github.com/user-attachments/assets/22925efc-4abc-4fad-90d5-94f3348c3c0b" />

---

## DESIGN

![WhatsApp Image 2025-11-28 at 16 24 05_e2a71e89](https://github.com/user-attachments/assets/5035faf6-bcce-4b64-a36e-0d0c42ecaf9b)
![WhatsApp Image 2025-11-28 at 16 25 21_77dd6931](https://github.com/user-attachments/assets/198c522e-b7b4-4945-9802-2203e7436dcd)

## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.

## TABULATION

![WhatsApp Image 2025-11-28 at 17 25 41_6c133f71](https://github.com/user-attachments/assets/120b0925-c518-4ec9-8945-1ff0dea337ef)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 16 32 08_479f9ad8](https://github.com/user-attachments/assets/7eb05c52-6986-47ad-bde9-123556253190)

---
## SIMULATION OUTPUT
<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/fbb9444b-a700-41ea-8532-f02f190e319a" />

 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-28 at 17 29 26_fa2d0e1c](https://github.com/user-attachments/assets/c187a1c4-06af-4520-804c-facb7f4fe3a8)


## SIMULATION CIRCUIT DIAGRAM
<img width="795" height="415" alt="image" src="https://github.com/user-attachments/assets/53654429-e046-455a-99f5-e121b25eb9df" />


## MODEL GRAPH

<img width="1055" height="537" alt="image" src="https://github.com/user-attachments/assets/f5eec55a-c00c-4eaf-a680-81ba95f66490" />


---

## DESIGN

DESIGN: BAND PASS FILTER

<img width="647" height="890" alt="image" src="https://github.com/user-attachments/assets/dd9e4d6c-a830-45d2-ae7d-2773d4c43bef" />


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-28 at 17 26 02_d0310199](https://github.com/user-attachments/assets/be794475-2f2b-4250-9d09-0cc1ef1b233c)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 16 33 07_de92d443](https://github.com/user-attachments/assets/0917a8a9-4eff-4476-ace4-588386ceb4e8)


---

## SIMULATION OUTPUT
<img width="980" height="429" alt="image" src="https://github.com/user-attachments/assets/bab6b3cd-a13c-4e57-b001-0e9ff55010b6" />


##RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---
![WhatsApp Image 2025-11-28 at 17 23 05_484abeca](https://github.com/user-attachments/assets/648c2392-080e-4177-8e9f-6a669d60823f)


   
