DSP-PROJECT

Vowel Onset Point Detection Using Spectral Evidence

Platform : MATLAB

Vowel Onset Point is the point at which onset of vowel takes place
in speech signals.In speech signals ,vowels posses more spectral 
energy as compared to consonants . This property is exploited in 
detecting onset point in a speech signal.

The speech signal is processed in a block of 20ms with a shift of 10ms.
For each block of 20ms , 256 point DFT is computed and ten largest peaks 
from first 128 points are selected.The sum of these amplitudes is plotted 
as a function of time which represents the energy of spectral peaks.The 
onset of vowel is observed as significant change in sum of ten peaks in 
the DFT spectrum.Further, enhancing is performed by convolving it with 
FOGD operator and the obtained output is the VOP evidence Plot using 
Spectral Peaks. 
