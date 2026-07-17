# Faraday rotation from ellipsometry data
This is a repository of scripts that parse ellipsometry data from .txt files, calculate Faraday rotation (FR) three different ways, and returns the values in a table and plot formatted for an excel file.
The calculation of Faraday rotation from the ellipsometric parameter psi is based on the theory outlined by Valeanu et al. in their 2016 paper [1]. 
All the samples measured were thin-films (micrometer scale) with a focus on thin-films of nanoparticles (NPs) deposited on a substrate. The experimental data includes measurements on SnO2 core Au shell NPs deposited on an Si substrate.

## Samples 
This script analyses data from the samples data folder. The calculated FR of different samples is plotted with error bars. The first plot visualizes the FR of all the measured thin-films, including polymer, blank Si, and 1SnxAu NPs with different loading ratios (represented by 'x'), being either etched (polymer removed) or loaded (polymer present). It is expected that the polymer and blank Si have no FR due to their lack of significant magneto-optical properties [Reference]. Moreover, FR rotation should increase with increasing volume of Au added (i.e., increasing 'x') due to ... [Reference]. Finally, loaded thin-films of NPs should exhibit greater FR than etched thin-films of NPs because of... [Reference].

## Angles 
This script analyses data from the angle data folder. The calculated Faraday rotation of a thin-film of 1Sn15Au nanoparticles for different angles of incidence of 532 nm light is plotted with error bars. 

## Si Control
This script is a modifed version of the samples script. It also analyses data from the samples data folder. The calculated FR of from the blank Si sample is substracted from the FR of the SnO2Au samples with different loading ratios. This adjustment of the FR output is done to control for the effect of Si on the FR and elucidate the effect of the NPs on the FR of the sample.

## References 
1. M. Valeanu, M. Sofronie, A. Galca, F. Tolea, M. Elisa,  bogdan alexandru Sava, L. Boroica, and V. Kuncser, “The relationship between magnetism and magneto-optical effects in rare earth doped aluminophosphate glasses,” Journal of Physics D: Applied Physics 49, 075001 (2016).

