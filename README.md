# Markov Chain Generator

A transition matrix can be calculated based on a training sequence (ex. <a href='https://github.com/Gagniuc/Discrete-Probability-Detector'>1</a>, <a href='https://github.com/Gagniuc/Discrete-Probability-Detector-JS'>2</a>, <a href='https://github.com/Gagniuc/Discrete-Probability-Detector-in-VB6'>3</a>). A Markov Chain Generator (MCG) is a prediction machine that uses a transition matrix to generate sequences that are similar to the training sequence. Thus, the output of a MCG mimics the training sequence that led to the values from the transition matrix and the process itself represents a prediction. Moreover, the MCG can also be used to verify the correct operation of the <a href='https://github.com/Gagniuc/Discrete-Probability-Detector-JS'>DPD algorithm</a>. Once the DPD algorithm produces a transition matrix (called here the “original” transition matrix) using a training sequence, that transition matrix can be used by the MCG to predict a similar sequence. In turn, the sequence produced by the MCG can be used by the DPD algorithm to produce a new transition matrix. If the original transition matrix and the transition matrix of the predicted sequence contain close transition probability values, then the DPD algorithm and the MCG machine work as expected.

# Live demo

https://gagniuc.github.io/Markov-Chain-Generator/

# Screenshot

![screenshot](https://github.com/Gagniuc/Markov-Chain-Generator/blob/main/mcg.png?raw=true)

# References

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>

- <i>Paul A. Gagniuc. Markov chains: from theory to implementation and experimentation. Hoboken, NJ,  John Wiley & Sons, USA, 2017, ISBN: 978-1-119-38755-8.</i>
