# Wie berechnet man die Erderwärmung?

## Teil 1: Theorie 

### Schritt 1
Zuerst wird die Sonnenstrahlung berechnet.
Da eine tiefer stehende Sonne weniger strahlt pro Quadratmeter, mussen wir es mit dem Sinus der Höhe multiplizieren.
So würde eine Sonne die genau im Zenit steht (90°) die gesamte Solarkonstant an Energie pro Quadratmeter strahlen.
- $h$ ist die Höhe der Sonne (Horizontsystem)
- $I_0: Solarkonstante \approx 1361 \frac{W}{m^2}$
- $I_{in} = E_0 \cdot \sin(h)$

### Schritt 2
Nicht nur die Sonne strahlt, die Erde straht auch zurück.
Dies kann mit dem Stefan-Boltzmann Gesezt getan werden.
- $\sigma$ ist die Stefan-Boltzmann Konstante (ca. $5,67 \times 10^8$)
- $\epsilon$ ist die Emissivität der Oberfläche (ca. 0,915 fürs Meer und 0,98 fürs Land)
- $T$ ist die Temperatur der Oberfläche in Kelvin
- $I_{out} = \sigma \epsilon T^4$

### Schritt 3
Die Treibhausgase strahlen auch.
Eine ungefähre Berechnung basierend auf den Treibhausgasanteilen in der Luft ist nicht möglich.
Man müsste die Teilchen in der Luft simulieren.
Geschätz wird gerade das ca. 20-30% der ausgehenden infrarot Strahlung von Treibhausgase zurück gestrahlt werden. 

### Schritt 4
- $I_{in}$ ist die einkommende Strahlung, sprich die Sonnenstrahlung und Treibhausstrahlung.
- $f_{thg}$ ist der Faktor der ausgehenden Strahlung die von Treibhausgasen in der Atomspäre gefangen wird
- $I_{out}$ ist die ausgehende Strahlung, die von der Erdoberfläche abgestrahlt wurde.
- $a$ ist der Albedo der Oberfläche, also wie viel des einkommenden Strahlung reflektiert wird
    - Dieser Faktor ist unglaublich wichtig, aber nur sehr schwer zu schätzen.
    Der Erdboden hat ein Albedo von ca. 20%, Schnee und Eis hingegen von über 90%.
    Viel wichtiger sind aber die Wolken. Hier ist das Albedo aber sehr unterschiedlich: 
    30-40% bei dünnen Wolken und bis über 90% bei dichten Wolken.
- $C_s$ ist die Energie die notwndig ist um die Temperatur um ein Kelvin zu erhöhen in $\frac{\frac{J}{m^2}}{K}$
    - Dieser Faktor hängt von der Oberfläche ab.
- $\frac{\Delta T}{\Delta t} = \frac{I \cdot \Delta t}{C_s}$
- $\Delta T = \frac{((1-a) I_{in} + f_{thg} I_{out} - I_{out}) \Delta t}{C_s}$

## Teil 2: Simulation

Es geht in weiter in [simulation.ipynb](https://github.com/wolffemi/Erderwaermung/blob/main/simulation.ipynb)

## Quellen
- [1] URL: https://ibphysicsguide.weebly.com/85-greenhouse-effect.html
- [2] URL: https://universesandbox.fandom.com/wiki/Surface_Heat_Capacity
