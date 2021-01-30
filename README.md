# Get-CPULoadGraph-in-console

Show the CPU load for each core on the machine similar to the graph in htop.  This works over SSH or PS remoting.  Color output is optional.  It accesses the performance counters via WMI on the local machine.  This approach uses sequencial string output.  To use as part of a more integrated htop like program, I would look into using cursor location positioning.  This would provide a more ncurses like experience.

![Output sample](https://github.com/donhess321/Get-CPULoadGraph-in-console/blob/main/console_sample.PNG)

This is a reposting from my Microsoft Technet Gallery.
