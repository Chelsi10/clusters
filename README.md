# clusters
splitting of coordinate file of chemical cluster into sub-files in order to calculate the energy of intermolecular interaction between molecules/atoms
# STEPS TO BE FOLLOWED
1. Create a file entry.txt in the following format (say for water dimer)
   (a) First line corresponding to number of fragments i.e. 2.
   (b) Second and third line corresponding to number of atoms in each fragment i.e 3 and 3 respectively.
   (c) Fourth line corresponding to the name of coordinate file.
2. Run file_3 to split the corrdinates.
3. Run energy_calc by using the correct set of coordinates obtained. Thus, energies are obtained. 
4. The energies should be saved in a file 'energy.dat'.
5. Run file_4(energy) to get the many-body contribution.
   
