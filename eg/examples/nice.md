# nice

set process priority to -15 (high) 

    nice -n -15 bash urgentjob.sh


set process priority to 15 (low)

    nice -n 15 bash lowpriorityjob.sh



# Basic Usage

set priority to a process at launching

    nice -n <priority> <command>
    

niceness values range from -20 (highest priority) to 19 (lowest priority)


