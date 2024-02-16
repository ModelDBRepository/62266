Readme.txt for the model code associated with the paper:

Safronov BV, Wolff M, Vogel W
Excitability of the Soma in Central Nervous System Neurons
Biophysical Journal Volume 78 June 2000 2998–3010

ABSTRACT

The ability of the soma of a spinal dorsal horn neuron, a spinal ventral 
horn neuron (presumably a motoneuron), and a hippocampal pyramidal neuron to 
generate action potentials was studied using patch-clamp recordings from rat spinal
cord slices, the “entire soma isolation” method, and computer simulations. By 
comparing original recordings from an isolated soma of a dorsal horn neuron with 
simulated responses, it was shown that computer models can be adequate for the study
of somatic excitability. The modeled somata of both spinal neurons were unable to 
generate action potentials, showing only passive and local responses to current 
injections. A four- to eightfold increase in the original density of Na1 channels
was necessary to make the modeled somata of both spinal neurons excitable. In 
contrast to spinal neurons, the modeled soma of the hippocampal pyramidal neuron 
generated spikes with an overshoot of 19 mV. It is concluded that the somata of 
spinal neurons cannot generate action potentials and seem to resist their
propagation from the axon to dendrites. In contrast, the soma of the hippocampal
pyramidal neuron is able to generate spikes. It cannot initiate action potentials
in the intact neurons, but it can support their back-propagation from the axon
initial segment to dendrites.

To run the model:

Simply auto-launch from ModelDB and press Init & Run to recreate the traces
from figure 6B.

Otherwise:

Download and expand the archive.

Compile the mod files through running mknrndll (WINDOWS), nrnivmodl(UNIX),
or drag and dropping the (b1) folder on the mknrndll icon (MAC).  Then
start by double clicking on a START-Motoneuron.hoc (WINDOWS) or type 
nrngui START-Motoneuron.hoc
under UNIX.  Then click Init & Run to generate the 6 traces from figure 6B.

These files were supplied by Boris Safronov.
