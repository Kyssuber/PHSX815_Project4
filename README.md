# PHSX815_Project4

In essence, this repository contains two programs from which the remainder is generated: DiceRollGalaxy.py and GalaxyAnalysis.py. Random.py contains the random class used to create categorical distributions given the probabilities of each die face.

Use: DiceRollGalaxy.py --> in a command line, input "python DieRollCat.py -seed number -Nroll number -Nexp number -outputH0 filename -outputH1 filename"
Default probabilities for a fair die; default Nexp = 3, Nroll = 5; default output file False.

GalaxyAnalysis.py --> in a command line, input "python DiceAnalysisCat.py -input0 filename_H0_data -input1 filename_H1_data"
Output will be critical_lambda, beta, incidence of (6,7,8) distribution plot for both hypotheses, and LLR distribution plot for both hypotheses.
