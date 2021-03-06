# Data analysis spike sorting - Day 3



Here is the schedulde for day 3 for the data analysis school in Lyon, October 2021
https://www.gdr-neuralnet.cnrs.fr/fr/node/63


## Instalation and download

Packages to be installed **before the school** (included in the provided environment file):
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


# Schedule

### Morning: 9:30 - 12:45
### Afternoon: 14:00 - 18:00

## Morning 9:30 - 12:45


* Overview on spike sorting -- Pierre Yger (1h20min)


* Overview on spikeinterface + probeinterface -- Alessio Buccino (30min)

* Demo - SpikeInterface (+ ProbeInterface) -- Alessio Buccino (1h20min)


## Afternoon 14:00 - 18:00

* Demo - Spikeinterface-gui -- Samuel Garcia (30 min)


### Practice (3.5 hours)

Prepare slides explaining the different “exercises”

#### Practice 1 : make your own probe with ProbeInterface (30 min)

The goal of this practice is to get familiar with ProbeInterface and to learn how to build a probe model from
design documents and datasheets of probes and connectors.

### Practice 2 : SpikeInterface pipeline on a real dataset (1h)

The goal of this practice session is to explore the SpikeInterface functionalities on a real datast.
It will include:
* reading data
* loading probes
* preprocessing
* spike sorting
* postprocessing
* exploration of results
* automatic curation
* export functions

### Practice 3 : spike sorting benchmark (50min)

In this practice you will use simulated recording with ground-truth to benchmark the performance of different algorithms.

### Practice 4 : use SpikeInterface on your own data (50min)

In this last part, you can try to apply what you learnt on your on data!

