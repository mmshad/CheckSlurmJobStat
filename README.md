## CheckSlurmJobStat

Use this script to show the number of SLURM jobs running in a specific file system. The first input to the program is the path to file system and the second input is the total number of top results to show (default is top 10 results). You may need to slightly modify the scripts if `scontrol` output is different (in terms of the number of lines, placement, ...).

Usage examples,

```bash
sh checkfsjobs.sh /n/holylfs02
sh checkfsjobs.sh /n/holylfs
sh checkfsjobs.sh /n/boslfs/
sh checkfsjobs.sh /n/
sh checkfsjobs.sh /n/ 5   # Show top 5 results
sh checkfsjobs.sh         # Will check all filesystems
```
