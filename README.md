# SA-Gogen

Based on https://github.com/coccyx/gogen

Gogen is an open source data generator for generating demo and test data.  Gogen can be used for any type of data, 
and it has first class support for time series data.  Primarily, it's been used and tested to generate log and metric data 
for testing time series systems.  It's very performant and can be used for functional and performance testing as well 
as generating compelling data sets to be used for demo purposes.

#
# UNIX ONLY

At default all inputs are enabled

## Inputs: 
* weblog
    * index = web
* businessevent
    * index = business
### nixOS
* nixOS/bandwidth
    * index = os
* nixOS/cpu
    * index = os
* nixOS/df
    * index = os
* nixOS/iostat
    * index = os
* nixOS/vmstat
    * index = os



Lookups can be edit over splunk lookup editor or over gui

# Settings
every input can be edit over the configs folder through a yaml file

# Examples
Every example files are not enabled and configured!