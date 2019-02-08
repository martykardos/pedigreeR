# pedigreeR
Forward-time, genomic simulations of evolution in finite populations. 
pedigreeR is an R package and can be installed using install.packages().
pedigreeR includes functions simPed() for simulating neutral evolution in pedigrees; and simPedSelec() for simulating 
evolution of a quantitative trait under truncation selection; pedSimHardSelec() for for simulating phenotypic evolution and population dynamics in density regulated populations; and pedSimHardSelecStep(), which is identical to pedSimHardSelec(), but with multiple populations connected via a stepping stone model of migration. 

The simulations can handle any number of chromosomes, any population sizes, imported recombination rate information, imported genotypes of population founders, and any number of SNP-like loci. The size of the simulated population, the number of loci, and the duration of the simulations are limited only by available computer memory an time. 
