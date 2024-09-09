- OpenOnDemand

- the pipe symbol | indicates "or"
- the ampersand & indicates "and"
- software stack
	- lmod command to manage software
	- module list to see mods loaded 
	- module avail to see all mods available 
	- 

- resource management 
	- using slurm, submit your proejct to slurm to get the proper resoruces 
	- be mindful of how much RAM youll need because if you go over your job will be killed 
	- if need to go over 8 hours for a job, recommended to change to a batch job 
		- #! /bin/bash
	- short QOS jobs
		- boost your priority for a single, short job (shorter than 4 hours)
		- only one QOS job at a time 
- Where to store on unity 
	- PI work directory- 1 TB
	- /project 
	- /scratch/workspace- temporary (120 days) high performance 
	- $HOME- keep empty because fns on unity need that space to run
	- NO BACKUPS on UNITY (why we use github)


- SSH- secure shell
	- access/open through terminal 
	- ssh -i <path to private key> username@hostname
	- can be generated in unity: "add key" -> "generate"
		- ssh should be in ~/.ssh folder
- Transfer ssh data
	- command lines like rsync and scp
	- open on demand for interface and smaller data (<5G)
	- Globus for large files

													