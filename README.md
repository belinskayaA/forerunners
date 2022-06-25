The repository contains script examples completed during the work in the Centre for Bioelectric Interfaces of HSE University as Researcher. 

The scripts are mainly related to the work on the [Real-time encephalography Project](https://bioelectric.hse.ru/en/real_time_encephalography). 



**Stack:** `Python`

**IDE:** `Jupyter Notebook`


[Forerunners](!!!) 

Here we consider EEG as a sequence of discrete patterns and use Markov Models (MM) to explore transitions between them. In this study, using MM we followed the NFB induced changes in the transitory dynamics of EEG.

We replaced EEG with a sequence of discrete states determined based on the clustering of the 3D vectors - estimates of the instantaneous power of 𝛂, 𝛃 and, 𝜽 rhythms. After that, for each training segment, we calculated a transition probability matrix and used linear regression to see how the probability of each transition changes as a function of the training segment.
