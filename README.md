## What is it? 
LabView_DSPConceptsBuilder is a collection of LabVIEW programs I wrote back in 2004 to illustrate basic concepts of Digital Signal Processing. There are around 35 programs as follows:

#### Time domain

1_0_Function Generator.vi
1_1_Time_phase_shift.vi
1_2_Periodicity of discrete sinusoids.vi
1_3_real exponential sequence.vi
1_4_Complex Exponential sequences.vi
2_1_Moving Average system.vi
2_2_Accumulator system.vi
2_3_Causal delay system.vi
2_4_Linear system property.vi
3_0_Linear convolution.vi
3_1_conv bet two impulse.vi
3_2_Circular convolution.vi
4_0_Signal operation in Time domain.vi

#### Sampling & Aliasing concepts

1_1_Periodic Sampling-Baseband signal.vi
2_0_Periodic Sampling-Bandpass signal.vi

#### Fourier Transform

3_1_Approx. of a real signal in terms of another real signal.vi
3_2_Fourier series rep of Periodic waveforms.vi
3_3_Fourier Transform of Periodic Gate.vi

#### FFT and Power spectrum concepts

1_0_FFT_conventional representation.vi
1_1_FFT and components.vi
1_2_Duality principle.vi
1_3_Centering of spec by mul wid neg_one power n.vi
2_1_Frequency Spectrum of two sine.vi
3_1_DFT resolution.vi
4_1_power spectrum of signals.vi
4_2_spectral Leakage.vi
5_0_inverse FFT of one sided vs two sided spectrum.vi
7_0_Parseval's Relation for DFT.vi
DFT based implementation of linear convolution.vi
Divided FFT.vi
limitations of FT.vi

#### Windowing and spectral leakage

Spectral Leakage & window effect.vi
Window Comparison.vi
Window Plots.vi
windowed and unwindowed signal.vi
windows.vi

In addition the the above virtual instruments, there are around 26 virtual instruments in the "usr_lib" directory which are internally used by the above VIs.

#### Note on usage:
When you try to open some of the virtual instruments for the first time, they will not be able to find the "usr_lib" directory, as the virtual instruments stores the absolute path address to the libraries. Please point to the appropriate vi in the "usr_lib" directory. Also, please feel free to modify and use the code as you like.


### Screen shots:

![LinearSystemProperty](http://farm9.staticflickr.com/8208/8204504359_a94163b227_o.png)

![Time_Phase-shift_Relation]( http://farm9.staticflickr.com/8346/8204504197_749a6e1245_o.png)

![ApproxRealSingalWithAnotherSignal](http://farm9.staticflickr.com/8207/8204504273_89d1b57e56_o.png)

![PeriodicSamplingAndAliasingSingleTone](http://farm9.staticflickr.com/8202/8205595574_ed5f099114_o.png)

![FFTrepresentation](http://farm9.staticflickr.com/8069/8205595664_0d021e7776_o.png)

![DFTresolutionZeroPadding](http://farm9.staticflickr.com/8346/8205595736_2d8898959e_o.png)

### License:
MIT License. Please see the LICENSE file for details.