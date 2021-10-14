# Data analysis spike sorting - day3



Here the the schedulde of day 3 for the data analysis school in Lyon, October 2021
https://www.gdr-neuralnet.cnrs.fr/fr/node/63


## Instalation and download

Package to be installed **before the school**:
 * numpy/scipy/sklearn/matplotlib/
 * spikeinterface[full]
 * MEArec
 * jupyter
 * tridesclous
 * spykingcircus
 * herdingspikes
 * montainsort

Datasets to be downloaded **before the school**:
 * "cambridge_data.dat" for practice 2
 * "templates_Neuronexus-32_100.h5" for practice 3


9:30 - 12:45
14:00 - 18:00

## Morning 9:30 - 12:45



### Overview on spike sorting

Pierre Yger
1h20min


### Overview on spikeinterface + probeinterface


30 min
Presentation with slides

### Demo - SpikeInterface (+ ProbeInterface) (1.20 h ?)

Alessio Buccino
1h20min
Notebook


## Afternoon 14:00 - 18:00

### Spikeinterface-gui (30 min)

Samuel Garcia
30min
Demo


### Practice (3.5 hours)

Prepare slides explaining the different “exercises”

#### Practice 1 : make your probe

30 min
Give neuronexus / cambridge design pdf + connectors + intan (channel locations as a csv file)
Construct your own probe from locations + channel map with PI

### Practice 2 : spikeinterface pipeline on  a real dataset

1 hour

Empty notebook with section titles (they can use docs + tutorials on their own) (+ full)

Dataset 1: cambridge neurotech (https://zenodo.org/record/4657314 - cambridge.bin)
Read
Plot
Select group
Run sorter
Compare then
Report
GUI

### Practice 3 : spike sorting benchmark

50 min

Benchmark exercise: 

Benchmark 2-3 sorters (agreement matrix + performance metrics)
      (b)  Simulate VS SNR)

Dataset 2 : MEArec
They run several simulation with different characteristics (the script is given)
Run 1 or more sorters
Analyse and benchmark sorter himself

### Practice 4 : set up your own data into spikeinterface
50 min

Dataset 3 : there own datasets (+backup for people that don’t have)

