
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="1189" height="704" alt="Screenshot 2025-11-11 190114" src="https://github.com/user-attachments/assets/08881b61-42f8-4e62-95b9-13ff3e4be597" />

## TABULATION  
![WhatsApp Image 2025-11-18 at 1 50 16 PM](https://github.com/user-attachments/assets/300ca47f-37ce-4c63-805a-7786b3cb43f8)


## MODEL GRAPH

![WhatsApp Image 2025-11-18 at 1 50 19 PM](https://github.com/user-attachments/assets/390c6095-7f7c-460f-bf11-d81107f46f9f)


## GRAPH
![WhatsApp Image 2025-11-18 at 1 50 15 PM](https://github.com/user-attachments/assets/24d87525-f949-4b28-8eac-2b19e0a3bf66)


## RESULT
Thus, the frequency response of the analog fiber optic link was successfully studied, and the bandwidth was determined to be 230 kHz.
