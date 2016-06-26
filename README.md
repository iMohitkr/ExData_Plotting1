## Introduction

* <b>Dataset</b>: <a href="https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip">Electric power consumption</a> [20Mb]

* <b>Description</b>: Measurements of electric power consumption in
one household with a one-minute sampling rate over a period of almost
4 years. Different electrical quantities and some sub-metering values
are available.


The following descriptions of the 9 variables in the dataset are taken
from
the <a href="https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption">UCI
web site</a>:

<ol>
<li><b>Date</b>: Date in format dd/mm/yyyy </li>
<li><b>Time</b>: time in format hh:mm:ss </li>
<li><b>Global_active_power</b>: household global minute-averaged active power (in kilowatt) </li>
<li><b>Global_reactive_power</b>: household global minute-averaged reactive power (in kilowatt) </li>
<li><b>Voltage</b>: minute-averaged voltage (in volt) </li>
<li><b>Global_intensity</b>: household global minute-averaged current intensity (in ampere) </li>
<li><b>Sub_metering_1</b>: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered). </li>
<li><b>Sub_metering_2</b>: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light. </li>
<li><b>Sub_metering_3</b>: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.</li>
</ol>


## Reproducing the results 

###Pre-Requisites

* <code> Rcurl</code> package

Just download the files into your home directory and run the R files.

*Note these codes assumes that the zip file is named* <b>hpc.zip</b> *so make sure you have renamed it if you have downoaded the dataset.*



## Making Plots



The four plots that you will be able to construct are shown below. 


### Plot 1

<code> source("plot1.R")</code>


![plot of chunk plot1](plot1.png) 


### Plot 2
<code> source("plot2.R")</code>

![plot of chunk plot2](plot2.png) 


### Plot 3
<code> source("plot3.R")</code>

![plot of chunk plot3](plot3.png) 


### Plot 4
<code> source("plot4.R")</code>

![plot of chunk plot4](plot4.png) 

