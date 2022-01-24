# Appendices for my master thesis

## Title = Computational Approaches to Universal Influenza Vaccines: In search of conserved T-cell epitopes

- src/ = contains a jupyter notebook containing code for all experiments.
- data/ = contains sequences/tree data used for experiments
- results/ = contains results for the experiments

To try the codes, you must download the necessary packages mentioned in the complete_pipeline.ipynb

External tools to download:
- MMseqs2 https://github.com/soedinglab/MMseqs2
- MAFFT https://mafft.cbrc.jp/alignment/software/ 
- FastTree https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0009490
- Population Coverage http://tools.iedb.org/population/
- NetMHCpan https://services.healthtech.dtu.dk/service.php?NetMHCpan-4.1

Unfortunately, neoIM (immunogenicity tool) is yet unpublished, and was ran privately by the person in charge of the development of the tool.
You would just have to use the results file instead (results/neoIM_results/*).

Also, the codes were written in linux environment.
If you have a Windows, try installing Windows Subsystems for Linux 2 (WSL2).




