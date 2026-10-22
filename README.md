# Experimental-verification-of-various-Fiber-losses--Propagation-Loss-Bend-Loss
# Propagation and Bending Losses in Plastic Fiber

## AIM
To measure propagation loss & bending losses for two different wavelengths in plastic Fiber provided with the kit.

---

## EQUIPMENTS REQUIRED
- Link-B Kit with power supply  
- Patch chords  
- 20MHz Dual Channel Oscilloscope  
- 1 MHz Function Generator  
- 1 Meter Fiber Cable  

---

## THEORY
Optical Fibers are available in different varieties of materials. These materials are usually selected by taking into account their absorption characteristics for different wavelengths of light.  

Since the signal in Optical Fiber is transmitted in the form of light (different in nature from electrons), one has to consider the interaction of matter with radiation to study the losses in fiber.  

- **Propagation Loss:**  
  - As light propagates from one end of Fiber to another, part of it is absorbed in the material (absorption loss).  
  - Some light is reflected back or scattered due to impurity particles, contributing to signal loss.  
  - Plastic Fibers typically have higher loss (~180 dB/Km).  

- **Bending Loss:**  
  - Losses occur when the angle of incidence condition is violated, causing refraction.  
  - Smaller radius of curvature → higher loss.  
  - Other losses occur due to coupling at LED and photo detector ends.  

---

## PROCEDURE
## PROCEDURE – GOOGLE COLAB

1\. Open Google Colab and create a new notebook for the experimental verification of propagation and bending losses in plastic optical fiber.

2\. Import the required Python libraries, namely NumPy, Pandas, Matplotlib, and Math, for numerical calculations, data tabulation, and graph plotting.

3\. Enter the measured output voltage values for 1-meter and 3-meter fiber lengths at a wavelength of 660 nm.

4\. Calculate the propagation attenuation for the 660 nm wavelength using the entered voltage readings and fiber lengths.

5\. Convert the calculated attenuation into decibels per kilometer and display the propagation loss.

6\. Repeat the same procedure for the 950 nm wavelength using the corresponding measured voltage readings.

7\. Create a tabular representation of the propagation loss values for both wavelengths and plot a graph to compare their attenuation characteristics.

8\. Enter the received signal voltage readings corresponding to different fiber loop diameters for the bending loss experiment.

9\. Arrange the loop diameter and received signal voltage readings in a table using the Pandas library.

10\. Calculate the relative bending loss for each loop diameter and display the calculated values along with the corresponding voltage readings.

11\. Plot a graph of received signal amplitude versus loop diameter, with loop diameter on the X-axis and received signal amplitude on the Y-axis.

12\. Plot a graph of bending loss versus loop diameter and observe the variation in bending loss as the loop diameter decreases.

13\. Compare the propagation losses at both wavelengths, analyze the bending loss characteristics, and save the Google Colab notebook containing the Python code, observation tables, calculated results, and graphs for the laboratory record.

**Formula:**  
<img width="758" height="50" alt="image" src="https://github.com/user-attachments/assets/3ec6183f-3031-4862-bb34-9f59c7e29fa3" />

Where:  
- \(a\) = attenuation (nepers/meter)  
- \(L1\) = fiber length for V1  
- \(L2\) = fiber length for V2  

This \(a\) is for **660nm wavelength**.  

---

### For 950nm Wavelength
1. Set switch **SW9 → TX2 position**.  
2. Set Jumper **JP7 → +12V position**.  
3. Remove fiber from SFH756V (660nm) & SFH350V.  
4. Insert 1m fiber between **SFH450V (950nm)** & **SFH350V**.  
5. Observe detected signal at ANALOG OUT.  
6. Measure peak value = **V1**.  
7. Replace 1m fiber with 3m fiber. Measure peak value = **V2**.  

**Formula:**  
<img width="758" height="50" alt="image" src="https://github.com/user-attachments/assets/56fbe9d6-9bff-460b-b04b-d2a73d0c3cd1" />


This \(a\) is for **950nm wavelength**.  
8. Compare attenuation values for 660nm and 950nm.  

---

## MEASUREMENT OF BENDING LOSSES
1. Remove fiber from SFH450V (950nm) & SFH350V.  
2. Insert 1m fiber between **SFH756V (660nm)** & **SFH350V**.  
3. Bend fiber in a loop and measure amplitude of received signal.  
4. Reduce loop diameter gradually to ~2 cm (not less than 1 cm).  
5. Record output voltage readings.  
6. Plot graph: **Received signal amplitude vs. Loop diameter**.  

---

## TABULATION

### Propagation Loss
<img width="1599" height="786" alt="WhatsApp Image 2026-10-22 at 2 24 22 PM" src="https://github.com/user-attachments/assets/f3de9dc8-15af-4b49-8da8-975a126f4d9f" />

### Bending Loss
<img width="1600" height="1204" alt="2O" src="https://github.com/user-attachments/assets/96083a35-1b6d-4ac6-adc7-69bbd4acf2ab" />

---
## OUTPUT
<img width="742" height="448" alt="image" src="https://github.com/user-attachments/assets/c3a51483-4150-4065-9d9f-c97a44a6c999" />
<img width="1042" height="646" alt="image" src="https://github.com/user-attachments/assets/ea5083ec-9f19-4826-8ef9-efcf1e81b514" />

## RESULT
- Propagation loss and bending losses for **660nm** and **950nm** wavelengths were measured.  
- Attenuation values compared and bending loss characteristics plotted.  
