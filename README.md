# Microstrip Patch Antenna 
Objective: 
To design and simulate a linearly polarised rectangular/square microstrip patch antenna on a given FR-4 epoxy substrate of thickness 1.6 mm and 
dielectric constant 4.4 at a frequency of 2.4 GHz.<br>
Theory: 
Microstrip patch antennas are a type of antenna where a metal patch mounted at a ground level with a di-electric material in-between. 
These types of antennas can be printed on PCB and the designs are very flexible. <br>

A design of rectangular microstrip patch antenna with microstrip transmission line feeding technique has been designed and simulated in the HFSS software. 
At the frequency of 2.4 GHz we are getting very good return loss of -25dB. It has a low gain of 1.48 dB at the 2.4GHz frequency. At the resonant frequency, 
the VSWR is nearly 1 which means we have nearly zero reflected power at the input node as the reflection coefficient is zero. Half power beam-width of this 
antenna is 79 degrees.

# Microstrip Low Pass filter
Objective:
To design, simulate and measure a stepped-impedance low-pass filter having a maximally flat response and cut-off frequency of 2.5 GHz with an attenuation of more than 20 dB at 4 GHz. 
The line impedance of filter is 50 Ω, highest line impedance is 120 Ω, and the lowest is 20 Ω.<br>
Theory:
Filter is a two-port device which passes microwave of certain frequencies I while rejecting or absorbing other frequencies.
Low pass filter is a two-port device which will let pass the frequencies below the cut-off frequencies and attenuates microwave of frequencies higher than the cut-off frequency.
We have to implement this Low Pass filter using the microstrip transmission line using alternating sections of very high and very low characteristic impedance lines where the series 
inductors of a low-pass prototype can be replaced with high-impedance line sections ( Z_o= Z_H), and the shunt capacitors can be replaced with low-impedance line sections ( Z_o= Z_L). <br>
<br>
The conclusion about this simulation work is that we are able to get a good trade-off between the steepness of Forward transmission curve and the complexity of the 
proposed LPF by keeping the n (no. of the elements) at 5. If we somehow increase the n (no. of elements) to a greater value then we will be able to get the more 
steepness in the curve of forward transmission or the frequency response of the LPF will be rectangular function but our device complexity will be much greater 
and the compactness of the LPF will severely hampered.
# Microstrip-power-divider
Objective: 
To design, simulate and measure an equal-split (3-dB) Wilkinson power divider for mobile communication operating at 915 MHz.<br>
Theory:
Power divider is passive microwave component used for power division. In power division, an input signal is divided into two (or more) output signals of lesser power. The divider may have three ports, four ports, or more, and may be (ideally) lossless. Power dividers usually provide in-phase output signals with an equal power division ratio (3 dB), but unequal power division ratios are also possible.<br>
The reflection and transmission coefficients of the proposed equal split power divider are studied. There is almost equal power division at the all output ports and good isolation between the output ports is obtained at the required frequency. By changing the gap width of quarter wave sections, isolation between output ports can be achieved. Wilkinson power dividers are very robust devices, and different designs can achieve similar performance, particularly when constructed using simple microstrip fabrication techniques and operating at reasonable frequencies. 
