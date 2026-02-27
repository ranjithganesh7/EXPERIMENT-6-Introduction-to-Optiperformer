# Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Aim
To analyze and evaluate the performance of an optical communication system by studying the relationship between fiber length, received power, Q factor and Bit Error Rate(BER) and to observe changes in the eye diagram with increasing fiber length using optiperformer.

---

## Theory

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Observation

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation:

<img width="1600" height="1365" alt="image" src="https://github.com/user-attachments/assets/8163c95c-7bf6-41b3-a052-5568ea782a61" />

---
## Graph:

<img width="1920" height="1080" alt="Screenshot 2026-01-24 121921" src="https://github.com/user-attachments/assets/b8f2be23-2385-459e-92b3-6bf4e6ef08f1" />

---
## Description:

   This OptiPerformer simulation displays the performance of a 90 km fiber link operating at a bit rate of 2.5 Gbps and a frequency of 193.1 THz. The results show a high-quality signal with a Max Q Factor of 44.545 and a wide-open eye diagram, which indicates minimal noise and jitter. At this specific distance, the optical power of -21.079 dBm is sufficient to maintain a zero Bit Error Rate (BER), ensuring successful data recovery without errors.

---
## Result:
   Thus the experiment executed and obtained the output successfully. 
