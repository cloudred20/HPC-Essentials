## HPC-Essentials
This repository provides concise, practical notes and examples for navigating High-Performance Computing (HPC) environments. It includes shell scripts for essential day-to-day command-line tasks along with guidance on Unix fundamentals, SLURM job submission, software module management, secure file transfers, and general HPC best practices.

**Useful Commands**
1. Convert Windows line endings to Unix format to ensure scripts run correctly on HPC systems.
```
dos2unix scriptname.sh
```
2. Validate the integrity of downloaded files by checking their MD5 checksums against a reference.
```
md5sum -c <reference_checksum_file>
```
