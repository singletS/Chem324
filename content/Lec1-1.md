---
title: |
    | Lecture 1.1, Chem-324, Fall2019
    | ***    
    | Birth of QM and discovery of energy quantization
author: 'Davit Potoyan'
institute: 'Iowa State University, Ames IA 50011'
---


## Outline for Lecture 1.1: 

- **Energies of atoms and molecules are _quantized_ existing in the form of discrete chunks called quanta.**<br>

- **Quantization of energy is a fundamental aspect of our physical reality and cannot be derived but can be observed in all quantum experiments. Is fully explained by the theory of quantum mechanics.** <br>
  
- **Key historical developments leading to the birth of QM are _black body radiation_, _double slit experiment_, _photoelectric effect_.**<br>



## Quantum vs Classical view on Energy levels.

- **In Classical mechanics (CM)**: Energy can take any value! Think of climbing a continuous ramp.
- **In Quantum mechanics (QM)**: Energy can only take certain discrete values! Think of a staircase ($1 E$, $2 E$, $3 E$... are okay, but $2.5 E$, $0. E$ or $1.99 E$ are not allowed). Energy is quantized!
![](./images/lec1_ladder.jpg)


## Electromagnetic spectrum, emitting objects and associated Temperatures.

![](./images/lec1_EMspec.jpg)

---

- **High-frequency waves carry much higher energy.** This means X-ray or Gamma-rays can only be generated by heating “stuff” up at very high temperatures. This happens naturally at the core of the sun!
- **Low-frequency waves carry less energy.** Can be generated in a “microwave” or by broadcasting antennas. 
- **The visible light.** occupies a narrow frequency region  in between. 



## Relationship between frequency, wavelength and speed of light. 

![Definitions of wavelength $\lambda$ and frequency $\nu$.](./images/lec1_wavelen_freq_c.jpg)

---

Wavelength **$\lambda$** and frequency **$\nu$** of light are inversely proportional with constant of proportionality being the speed of light **c**:
<div style="background-color: #fefbd8">
 $$\lambda \nu = c$$
</div>

- Think of wavelength as distance between wave peaks 
  (nanometers, nm)

- Think of frequency as a 
  distance traveled in 1 second (hz). 

- Speed of light in vacuum, c is a constant (3 10^8 m/s).  Thus knowing the wavelength allows you to compute the frequency and vice versa.  



## What is the relationship between frequency of radiation $\nu$ and energy $E$?  

![EM spectrum and excitable energy states corresponding to each frequency region](./images/lec1_EMspec2.png)

---

This is not such a trivial question. In fact, this very question arose in connection with black body radiation; an experiment that forever changed the course of history by giving birth to quantum mechanics! 



## What do we mean by black body and black body radiation: a visual guide. 

![Black body radiation guide from PhD comics](./images/Black_body_rad.jpg){width=50%}

## Thermodynamically speaking.

_A black body is an idealized system which is in equilibrium, maintained at some constant Temperature T which both absorbs and emits every wavelength of electromagnetic radiation_

 Equilibrium condition in thermodynamics means that the system emits as much energy as it absorbs. In other words outflux = influx. The reason its called black body is that it absorbs every wavelength that hits the surface, therefore, appearing as 100% perfect black object. If an object has a color, it is because it is reflecting certain wavelengths of light which then gets detected by our eye retina. The distribution of wavelengths, which is emitted by a blackbody, is determined only by its temperature. 


## Applications of black Body radiation

The black body is used as a standard with which the absorption of real bodies is compared. To a good approximation, stars radiate like blackbody radiators. Thus we can use blackbody radiation as a model to infer the temperature of the stars from their colors!

![](./images/lec1_planets.jpg)

- [The Fingerprint of Stars](https://www.youtube.com/watch?v=uG4xe9cNpP0) 

- [Visible Light Waves](https://www.youtube.com/watch?v=PMtC34pzKGc)  


## What are the essential features of black body radiation?

![](./images/lec1_bb.png){width=110%}

As temperature T goes up we notice three things:

- Radiation intensity goes up, implying higher radiation energy.
- Distribution of wavelengths shifts left to lower values (left panel) or we can say the distribution of frequency shifts right (right panel)
- Color of the object changes from red to yellow to blue. 


## What is classical mechanics & thermodynamics perspective on black body radiation?

- What is “temperature”? A measure for kinetic energy per particle associated with translational, rotational, vibrational degrees of freedom. 
- What is light? Think of an oscillating spring with frequency $\nu$
- Thermodynamics: Heat can only flow from high to low temperature. In equilibrium, each degree of freedom in our case each spring/oscillator gets the same thermal energy $k_B T$.



## Implications of classical mechanics and thermodynamics.

![](./images/lec1_UVcat.jpg){width=50%}

Classical mechanics leads to the Rayleigh-Jeans law which works only in low frequency region. 

---

The classical reasoning  about black body radiation is following:

- Number of waves fitting inside an idealized cubic black body is $N_{\nu }=\nu^3$.  For small frequency region  $d\nu$ there would be $dN=3\nu^2 d\nu$ waves. This is simple geometric argument: One can fit more of high fequency (short wavelength) waves in the box than small frequency ones. 

 - From the equipartition principle of thermodynamics each oscillator has $k_BT$ of energy. Thus the intensity of radiation, according to classical mechanics, is **$$I \sim k_B T \nu^2$$**. Intensity increases to infinity at high $\nu$ (or low $\lambda$). This is known as the ultraviolet catastrophe!



## Max Planck finds the right explanation for black body radiation 

In 1900 Planck found that the theoretical curve can very closely match the experimental curve if one postulates that only the discrete (quantized) values for electromagnetic oscillators are possible. The iconic formula resulting from this postulate which now bears his name is $E= nh\nu$ where n=0,1,2,3 are quantum numbers of energy levels.


- This means atoms and molecules absorb and emit radiation in discrete quantities, multiples of $h\nu$, which are called quanta! $E_1, E_2,E_3 …$

- When light is emitted or absorbed, the atom or molecule jumps from one state to another and the energy difference $h\nu = E_n - E_m$ is either coming from light or is used to generate light.

## Planck equation and Planck’s constant

<div style="background-color: #fefbd8"> 

$$E= h\nu$$

</div>
- Unit of planck constant, $h = 6.63 10^{–34} J s$

- Unit of frequency $\nu$, $s^{-1}$.
  
Often also written as $E = nh\nu$ (n = 0,1,2,…) to specify that for energy adds up with number of photos n. We thus learn that discretized energy levels accessible by photons are the only allowable energy levels that atoms/molecules can have. All energies are quantized!

Note how small $h$ is in the macroscopic units (such as J s). This is why quantization of energy is hardly noticeable and classical mechanics works so well at the macro scale.
In the limit $h \rightarrow 0$, $E$ becomes continuous, and an arbitrary real value of E is allowed. This is the classical limit.

## How Plank's quantization postulate explains black body radiation

According to classical mechanics, on average each degree of freedom of an oscillator gets $kT$ of thermal energy. 

$$\langle E \rangle=kT$$ 

In Quantum Mechanics, however, because energy levels are quantized on average each degree of freedom of oscillator ends up getting: 

$$\langle E \rangle=k_B T\Big[ \frac{h\nu/kT}{e^{h\nu/kT}-1} \Big ]$$ 

These expression are obtained by taking averages over energy values of oscillators weighted by Boltzman distribution which governs the thermal equilibrium: 

- For classical case average is over continuum of energies $$\langle E \rangle = \int  p(x) E(x) dx$$ with $E(x)=kx^2/2$ and $P(E)\sim e^{-E(x)/kT}$ 
- For quantum case average is a sum over discrete values $$\langle E \rangle = \sum_n p_n E_n$$ with $E_n=nh\nu$ for quantum oscillators $P(E_n)\sim e^{-E_n/k_B T}$.   

---

- At very low frequencies, we recover the classical result! This explains why classical mechanics was at least partially successful. Thermal energy $k_BT$ populates lots of quantum levels with low enough frequencies.

$$h\nu \ll k_BT,\,\,\,\, e^{h\nu/k_BT}\approx 1+\frac{h\nu}{k_BT}$$  $$\langle E \rangle=k_B T\Big[ \frac{h\nu/k_BT}{e^{h\nu/k_BT}-1} \Big ] \rightarrow k_BT$$

- At high frequencies we see that the exponents kills the energy expression.  Thermal energy kT can no longer afford to occupy quantum levels with high frequencies, thus average oscillator energy goes down with increasing frequency:

$$h\nu \gg k_BT,\,\,\,\, e^{h\nu/k_BT}\approx \infty$$  $$\langle E \rangle=k_B T\Big[ \frac{h\nu/k_BT}{e^{h\nu/k_BT}-1} \Big ] \rightarrow 0$$



## Quantization of atomic spectra.

![](./images/lec1_AtomicSpectrum.png){width=80%}

---

- Measurements of atomic emission/absorption spectra were another key experimental evidence showing that energy levels of individual atoms are quantized.

- Notice the existence of discrete frequencies in the spectrum consistent with Planck’s assumption. 

- Different colors originate from different frequencies being emitted or absorbed by matter.



## Empirical expressions for predicting spectral lines.

- Spectral lines were rationalized by Rydberg who derived an empirical formula showing that differences in spectral lines of the Hydrogen atom are dictated by integer numbers. Integer numbers indeed will go on to play a special role in quantum theory. 

- Blackbody radiation and atomic spectra showed very clearly that atoms exist in states that occupy discrete energy levels.
- Atoms and molecules exchange energy with the environment by jumping from one state $E_m$ to another $E_n$. The energy difference between these levels  $E_m-E_n=h\nu$ is either supplied by light (absorption) or used to generate light (emission).

## Summary


- Energies of stable atoms, molecules, electromagnetic radiation are discrete (quantized) and are not continuous. Energies of macroscopic bodies are quantized as well, but we do not see it since energy levels are so closely spaced that they appear as continuous for all practical purposes. 
- Classical mechanics works for macroscopic bodies but fails to describe the dynamics of microscopic particles. 
- Some macroscopic phenomena, such as the red color of hot metals, heat capacity of solids at a low temperature, and colors of matter are all due to quantum effects.
- Quantized nature of energy is learned in experiments and cannot be derived. We must simply accept it and move on to construct quantum theory consistent with the observations. 


