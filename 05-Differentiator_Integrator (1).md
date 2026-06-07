## AIM

To design and set up an integrator and differentiator circuit using op-amp.

## APPARATUS REQUIRED

Power supply, CRO, function generator, bread board, op-amp, capacitor and resistors.

## THEORY

## INTEGRATOR

Refer to the figure 1. This circuit performs the integration of the input waveform. The
output voltage 𝑉𝑜 can be expressed as	𝑉𝑜= − 1/𝑅𝐶 ∫ 𝑉𝑖𝑑𝑡 + 𝑘 where k is the constant of
integration which depends upon the value of 𝑉𝑜 at t = 0. The peak of the output waveform 𝑉𝑇
is given by the expression 𝑉𝑇=  𝑉𝑇/4𝑅𝐶 , where T is the time period of the input square wave.
Integrators are commonly used in analog computers and wave shaping networks. 
## DIFFERENTIATOR

If the input resistor of the inverting amplifier is replaced by a capacitor, it forms an inverting differentiator. The output of the circuit is the derivative of the input. Gain of the differentiator increases with increase in frequency, which makes the circuit unstable. This is a
drawback of the circuit. The output voltage 𝑉𝑜= −𝑅𝐹 Ci 𝑑𝑉i/𝑑𝑡.

Differentiator functions as high pass filter. At high frequency it becomes unstable and breaks into oscillations. Input impedance decreases with increase in frequency which makes the circuit very susceptible to high frequency noise. Both stability and high frequency noise problems can be reduced significantly by additional circuit elements.

## DESIGN AND CIRCUIT DIAGRAMS

DESIGN OF INTEGRATOR

Let the input frequency be 1 kHz. The frequency at which the integrator gives unity gain
output is given by, f = 1 / 2pi R1C
Let C = 0.01μF. then R1 = 15.9 kΩ. Use 15 kΩ std.

<img width="715" height="310" alt="image" src="https://github.com/user-attachments/assets/90467524-2fb5-478e-b9a2-3d45de3e9af2" />

The resistor R2 in the integrator is provided to attenuate low frequency signals, particularly input dc offset voltage that may be present. Typically, the value of R2 is selected as 10 times R1 or more. Select the value of R2 as 470 k.

DESIGN OF DIFFERENTIATOR

We have, f = 1/ 2 pi RC

Let C = 0.01μF. then R = 15.9 kΩ. Use 15 kΩ std.

## PROCEDURE

INTEGRATOR

1.Set up the integrator circuit as shown in figure. Give a rectangular wave of ±5V (10V pp) and 1 kHz frequency at the input and observe the input and output simultaneously on CRO.
2.Vary the dc offset of the square wave input and observe the difference in the output waveform.
3.Repeat the experiment by feeding triangular wave and sine wave at the input and observe the output.

DIFFERENTIATOR

1.Set up the differentiator circuit as shown in figure. Give a rectangular wave of ±5V (10V pp) and 1 kHz frequency at the input and observe the input and output
simultaneously on CRO.

2.Repeat the experiment by feeding triangular wave and sine wave at the input and observe the output.

<img width="705" height="271" alt="image" src="https://github.com/user-attachments/assets/a058bca1-82b9-4f03-b1dc-6bc923093ae6" />

## RESULT
The design and set up an integrator and differentiator circuit using op-amp has been executed successfully and the output is drawn
