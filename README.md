# Pulse-Code-Modulation
Pulse code Modulation the involves Sampling,Quantization, and Reconstruction.

---------------------------------------------------------------------------------------------------

Pulse code modulation techinique basically involves Sampling , Quantization , Reconstruction.

SAMPLING : 
The analog signal is sampled by multiplying it with an impulse train generates all the sample values.

QUANTIZATION :
The sample values being only discrete in Time must also be made discrete in Amplitude also by the process of Quantization.

                                                   ACCORDING TO THE RULE OF QUANTIZATION 
                                                   
                                                   X[N] = rk  if tk < X[n] < tk+1
                                                   
                                                   X[n] Sampled value
                                                   rk - reconstruction level
                                                   tk - quantization levels
                                                   
                                                   
 RECONSTRUCTION : 
 Using a low pass butter worth filter of sufficient bandwidth and order = 2.
