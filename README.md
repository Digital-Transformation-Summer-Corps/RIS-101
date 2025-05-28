# RIS-101
Contains the documentation for the RIS 101 seminar

## Research Infrastructure Services Basics

Washington University Information Technology’s Research Infrastructure Services’ mission is to facilitate discovery of knowledge and enhance educational opportunities by providing secure, sustainable, scalable, and integrated research technology services in a collaborative and diverse environment.

### What is HPC?

- Computing that uses supercomputers and computer clusters to solve advanced computation problems.
- A supercomputer is a computer with more resources than what your average desktop or laptop computer has, often by orders of magnitude.
- Computer clusters are large amounts of computers networked together to be able to compute on tasks.

#### Average Computer Specs
- 1 TB Storage Space
- 1 CPU
- 8-16 GB RAM/Memory
- 1 GPU

#### RIS Storage Platform
- 30+ PB of Storage

#### RIS Compute Platform
- 10,000+ CPUs
- 120+ GPUs
- Up to 1TB RAM/Memory

![image](https://github.com/user-attachments/assets/8755f166-dd1a-4a47-bc26-030ea29b139a)

### Storage Platform
- Connections
  - SMB
  - Globus
  - Compute Platforms
- HIPAA Compliant
- Faculty Get 5TB Free

### Compute Platform
- Comand Line Interface (CLI) [C1,C2]
- LSF Scheduler [C1]
- Slurm Scheduler [C2]
- Containers (Docker [C1,C2], Apptainer [C2])
- Open On Demand (OOD) [C1]

### Storge and Compute Info
- Storage Allocation: /storage2/fs1/dt-summer-corp/Active/
- Compute Allocation:
  - Compute Group: compute-dt-summer-corp
  - Compute Queues: general, general-interactive, artsci, artsci-interactive
- GitHub: https://github.com/Digital-Transformation-Summer-Corps

### Further Information
- http://ris.wustl.edu
- http://docs.ris.wustl.edu
- https://hub.docker.com/
- https://becker.wustl.edu/services/research-computing/

## Troubleshooting

### Outline
- What is Troubleshooting?
- What is Google-fu?
- Topic Related Resources
- Example of Troubleshooting
  - ‘Disk quota exceeded’ example

### What is Troubleshooting?
- According to the dictionary
  - Solve serious problems for a company or other organization
  - Trace and correct faults in a mechanical or electronic system
- According to Wikipedia
  - Troubleshooting is a form of problem solving, often applied to repair failed products or processes on a machine or a system. It is a logical, systematic search for the source of a problem in order to solve it, and make the product or process operational again.

### Why is Troubleshooting Important?
- Will encounter errors while working on analysis (with or without using HPC)
- Better understanding of how to approach problems (even those beyond using HPC)
- Useful beyond research and analysis

### What is Google-Fu?
- A moniker that refers to the ability to use Google or other search methods to aid in troubleshooting or more generally, just finding information
- Very helpful in troubleshooting
- Most IT professionals use it daily or more often

### Tricks for Better Searches
- Use quotes to get an “exact” match
- Search a specific site with site:
- Exclude a term from search results with –
- Search for a particular filetype with filetype:
- Use wildcard (*) to make searches
- Combine searches with OR, AND logic

<img width="575" alt="Screenshot 2025-05-28 at 10 41 03 AM" src="https://github.com/user-attachments/assets/91576bdd-d972-41b4-8141-a85031d74c02" />

### Topic Related Resources
- Many fields and topics have online resources available to get questions and answers addressed.
- A Google search may often bring up these resources.
- Some examples include
  - Stack Exchange(https://stackexchange.com/)
  - Biostars(https://www.biostars.org/)

### Example of Troubleshooting

#### Step 1: Look into RIS docs website
<img width="567" alt="Screenshot 2025-05-28 at 11 23 37 AM" src="https://github.com/user-attachments/assets/e8149d8b-e276-4eb6-8080-23adcfbce7fa" />
<img width="437" alt="Screenshot 2025-05-28 at 11 23 47 AM" src="https://github.com/user-attachments/assets/89ab94e9-d1a6-4aa6-90c0-947d20c7dcbb" />

#### Step 2: Use what we've found so far.
<img width="752" alt="Screenshot 2025-05-28 at 11 24 32 AM" src="https://github.com/user-attachments/assets/bd69d9fa-2726-4784-bcb9-b62aabe42382" />

#### Step 3: Didn't find the issue, so we keep looking.
<img width="1060" alt="Screenshot 2025-05-28 at 11 25 16 AM" src="https://github.com/user-attachments/assets/e0ff26be-4b51-4a62-9bf6-6f2f7e5424d2" />

#### Step 4: Try what we've found again.
<img width="749" alt="Screenshot 2025-05-28 at 11 25 56 AM" src="https://github.com/user-attachments/assets/78dabda9-67bb-4236-a8a1-020925ab57f3" />

#### Step 5: Back to the drawing board.
<img width="421" alt="Screenshot 2025-05-28 at 11 26 35 AM" src="https://github.com/user-attachments/assets/97360568-524c-48b4-854c-d809f24864c7" />
<img width="440" alt="Screenshot 2025-05-28 at 11 26 41 AM" src="https://github.com/user-attachments/assets/d2ad8990-7727-4d82-b5b0-d363a984b00a" />
