# Interference-Coherence

Column: Aryacci
Course: Optics
Created: June 7, 2020 11:26 AM
Level: 1
Next_Rep: January 11, 2022 10:14 AM
Overdue: 273
Scheduled_Rep: October 11, 2021
Start-Date: October 10, 2021

> Ch9, *Interference, Optics, **[Hecht](https://drive.google.com/file/d/1gnNwR-ajGAoc2GOi7mIUvNqedXZ3632p/view?usp=sharing)**, 2017*
> 

> *Ch7, pg286 Elements of the theory of interference, Principles of EM THEORY OF PROPAGATION, **[Born & Wolf](https://drive.google.com/file/d/1vrofost5QOAbesI6d3D5-Torn1CW0lFA/view?usp=sharing)**, 1999*
> 

> Preface + *Ch1, **Wolf**, Intro to coherence, Cambridge press, 2007*
> 

> Coherence properties of Optical fields, Mandel, Wolf, APS, 1965
> 

---

> **[Ref2](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099.md)**                                  Interference
> 
- What is interference ?
    
    Interaction of two or more light waves yielding a resultant irradiance (intensity) which deviates from the sum of corresponding irradiances (intensities) #Hecht  
    
- What is monochromatic ? Do monochromatic light exists in nature ?
    
    Light with constant amplitude and phase. No its an idealisation as from atomistic theory, the amplitude and phase undergo irregular fluctuations much to rapid for the eye  or any other detector to follow 
    
    Quasi-monochromatic:  imitates monochromatic light most closely. Defined by the effective bandwidth $\Delta\omega$ is smaller than its mean frequency
    
                                                                $\frac{\Delta\omega}{\omega}$ << 1,
    
    for such light amplitude $a_i \neq const$, phase $\phi \neq const$ 
    
    vibration of quasi-mon light a a pt  in space is given by 
    
                                                         U(t) = a(t)cos[$\phi(t) = \bar{\omega}t$ ]
    
    generally both *a(t) & $\phi(t)$  fluctuate randomly ⇒ they will vary very slowly under any time interval $\Delta$t for,*
    
                                                          $\Delta t << \frac{2\pi}{\Delta\omega}$ **  
    
- What is **complete, partial coherence** and **incoherent** ? What is their relation with interference ?
    
    When beam are completely and partially correlated then they are called **partial coherence** and **complete coherence (**usually beams originating from the same source generally have correlated fluctuations ) 
    
    Beams of two different sources generally do not have any correlation called mutually **incoherent** or **uncorrelated** 
    
    **incoherent** beams do not interfere under normal experimental conditions and **their intensity is just sum of the individual intensities**
    
- Generally how many methods are there for obtaining  multiple beams from single beam of light ?
    1. **Division of wavefront:** using [side by side apertures](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099.md)  → useful only for small sources
    2. **Division of amplitude:** by partially transmitting surfaces → can be used for extended sources
- Why side by side apertures for generating multiple beams why not both apertures at an angle ?
- Define **intensity** ? Why we need to do average to calculate intensity why we don't calculate **instantaneous intensity** ?
    
    Intensity: time average of the amount of energy that crosses a unit area perpendicular to the direction of the energy flow in unit time
    
    **For plane wave:** I = $\frac{c}{4\pi}\sqrt{\frac{\epsilon}{\mu}}<E^2>$
    
    The fluctuation of em eaves are very fast 1 cycle in 10-15s for vis hence there is not detector which works in this range they can record data at a specified no of time Giga/s. In that time 10^6 cycles would have passed.
    
    THerfore we take time average >> period of wave
    
- Write a general form for the electric field of monochromatic light ? What is the constraint for homogeneous plane wave ? Do only amplitude of the wave only matters for the intensity calculation for the monochromatic wave ?
    
    ![Screenshot from 2021-10-11 09-57-34.png](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_from_2021-10-11_09-57-34.png)
    
    Although the instantaneous intensity do contain terms containing angular frequency but we do not calculate the instantaneous but average intensity which makes the terms containing angular frequency to 0 considering t→ $\infty$
    
- What is the experimental condition for which we calculate the superposition of two monochromatic waves ? Did we require EM theory or vibrations are transverse for interference ? Any connection of this to **Fresnel-Arago** ?
    
    ![Screenshot from 2021-10-11 10-09-16.png](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_from_2021-10-11_10-09-16.png)
    
    No, we didn't required EM-theory or transverse vibration
    
    Fresnel-Arago observed that perpendicularly polarised wave do not interfere so if we prepare a wave in x-z (a_2 = 0) and y-z (b_1 = 0) then only z component of wave should interfere (J_12 = $a_3b_3cos\delta$ but they didn't found any intensity so they concluded no z component $a_3 = b_3 = 0$,  i.e em waves are transverse
    
- onditions of interference? To get clearer patterns? Phase difference? Can white light interfere?
    
    ![Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_2020-06-09_at_6.34.27_PM.png](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_2020-06-09_at_6.34.27_PM.png)
    

---

> **Ref [3](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099.md) + [4](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099.md)**                                            Coherence
> 
- What is coherence and optical coherence theory ?  Is interference in any way related to coherence ?
    
    Every optical field found in nature has certain fluctuations. Optical coherence is the manifestation of the correlation between the fluctuation of optical field at different time and space. **Optical coherence theory** deals with statistical description of these fluctuation.
    
    **Interference** is the simplest phenomena which reveals correlation between light beams. IT quantifies  coherence between light vibrations at two points in space and at two instants of time  
    
    Phase remaining constant with time
    
    ![Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_2020-06-09_at_6.37.59_PM.png](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_2020-06-09_at_6.37.59_PM.png)
    
    ![Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_2020-06-09_at_6.37.45_PM.png](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_2020-06-09_at_6.37.45_PM.png)
    
- What is the source of these fluctuations ? Where these fluctuation manifests ? Can we measure the field ?
    
    **For thermal light :**fluctuations are due to the spontaneous emission of radiation from atoms which generate the field.
    
    **For laser light:** due to the uncontrollable causes like mechanical vibrations of the mirrors at the end of cavity, temp. fluctuations & again from spontaneous emission
    
    For a well established laser these fluctuation largely manifests in **phase fluctuations** rather than **amplitude fluctuations** and also in the **chaotic behaviour** of the laser output **⇒** may be detected over longer time
    
- What is **2nd order theory of optical coherence**? What types of fields this correlation theory was enough and why ? Higher order correlation
    
    gives a unified framework for polarisation and coherence. For optical fields produced by thermal sources (incandescent lamps and gas discharge) 2nd order correlation was adequate for the description of 2nd as well as higher order effects.
    
    Since a thermal light wave has the statistical character of a gaussian random process and such a process is completely characterised by 2nd order correlation
    
    - What misconceptions that
- What misconceptions that optical coherence solved ?
    1. Belief that no interference interference can take place between completely independent light beams
    2. photon counting measurements with a photodetector can give no information about the spectrum of light
- Considering quasi-monochromatic light when can we consider the amplitude a(t) and phase $\phi$(t) to be nearly a constant ? Prove it
    
    they vary very slowly over any time interval $\Delta$t which is short compared with the reciprocal bandwidth of light
    
    i.e for time intervals $\Delta t << \frac{2\pi}{\Delta\omega}$  
    
- What  is **steady state field** ? Is it related to **statistical stationarity** ?
    
    The **statistical** behavior of the fluctuations should remain constant with time **⇒ statistical stationarity**
    
    ![Screenshot from 2021-10-13 15-32-18.png](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_from_2021-10-13_15-32-18.png)
    
- Two quasi-monochromatic fields superposing at a region, FInd the instantaneous intensities ? [Can instantaneous intensities be measured ?](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099.md) What will be the interference term considering beams with time-independent equal intensities at the point? Ergodicity ? dO there is no interference in quasi-mono light ?
    
    No
    
    ![Screenshot from 2021-10-13 14-41-30.png](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_from_2021-10-13_14-41-30.png)
    
    ![Screenshot from 2021-10-13 14-52-13.png](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099/Screenshot_from_2021-10-13_14-52-13.png)
    
    So we will have interference term =\ 0 except for certain points where $\delta$ takes such value which make cosine term = 0
    
    So it Interfernce term $\neq 0$  when $\phi_1(t) - \phi_2(t) = \beta$  = phase undergo random fluctuations 
    
- If interference can take place between quasi-mono light then what is the criteria for interefence between two fields ? [What is statistical similarity ?](Interference-Coherence%205f8d46d79ad84d1cb4f9214939f67099.md)
    
    have to be statistically similar at the point of interest (essence of coherence)
    
    $\phi_2(t) - \phi_1(t)$ = cont  is an example of statistical similarity
    
- What is a manifestation of temporal coherence ? How to understand it ? What is **coherence time and length ?** values for laser and lamp
    
    Appearance of fringes in the MIchelson- interferometer. INterference fringes will be observed only when 
    
    $\Delta t \leq \frac{2\pi}{\Delta\omega}$ 
    
    It is the time delay by which individual intensity patterns get out of step eventually cancelling out ⇒ **coherence time** 
    
    path delay corresponding to the time delay is **coherence length**
    
    for thermal $\Delta\omega = 10^8$ (thermal sources) and $10^4$ (laser) 
    
    $\Delta l$ = 19m and 190 km
    
- Derive the coherence area and volume obtained in Young's experiment ?
