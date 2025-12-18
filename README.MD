# Wie berechnet man die Erderwärmung?

## Teil 1: Theorie 

### Schritt 1
Zuerst wird die Sonnenstrahlung pro berechnet.
- $h$ ist die Höhe der Sonne (Horizontsystem)
- $I_0: Solarkonstante \approx 1361 \frac{W}{m^2}$
- $I_{in} = E_0 \cdot \sin(h)$
Da eine tiefer stehende Sonne weniger strahlt pro Quadratmeter, mussen wir es mit dem Sinus der Höhe multiplizieren.
So würde eine Sonne die genau im Zenit steht (90°) die gesamte Solarkonstant an Energie pro Quadratmeter strahlen.

### Schritt 2
Nicht nur die Sonne strahlt, die Erde straht auch zurück.
Dies kann mit dem Stefan-Boltzmann Gesezt getan werden.
- $\sigma$ ist die Stefan-Boltzmann Konstante (ca. 5,67E−8)
- $\epsilon$ ist die Emissivität der Oberfläche (ca. 0,915 fürs Meer und 0,98 fürs Land)
- $T$ ist die Temperatur der Oberfläche in Kelvin
- $I_{out} = \sigma \epsilon T^4$

### Schritt 3
Die Treibhausgase strahlen auch.
Dies kann ca. 20-30%

### Schritt 4
- $I_{in}$ ist die einkommende Strahlung, sprich die Sonnenstrahlung und Treibhausstrahlung.
- $f_{thg}$ ist der Faktor der ausgehenden Strahlung die von Treibhausgasen in der Atomspäre gefangen wird
- $I_{out}$ ist die ausgehende Strahlung, die von der Erdoberfläche abgestrahlt wurde.
- $a$ ist der Albedo der Oberfläche, also wie viel des einkommenden Strahlung reflektiert wird
- $C_s$ ist die Energie die notwndig ist um die Temperatur um ein Kelvin zu erhöhen in $\frac{\frac{J}{m^2}}{K}$
- $\frac{\Delta T}{\Delta t} = \frac{I}{C_s}$
- $\Delta T = \frac{((1-a) I_{in} + f_{thg} I_{out} - I_{out}) \Delta t}{C_s}$

## Teil 2: Simulation

TODO

## Quellen
[1] URL: https://ibphysicsguide.weebly.com/85-greenhouse-effect.html

