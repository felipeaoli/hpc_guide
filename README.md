
# HPC for the practical person
`felipeaoli@gmail.com`

This tiny tutorial is for users getting started to cluster computer 
### Content {#content}
1. [Slurm](#slurm)
2. [GRIDUNESP](#gridunesp)
3. [NERSC](#nersc)




----
## Slurm {#slurm}
Slurm is a popular job manager system. Below, I list some of basic commands to use in your terminal<sup>1</sup> 


1) Submit your job:
```
sbatch <my_submition_file.some_extension>
```

2) Check your job status:
```
squeue -u <my_username>
```

or, literally, 
```
squeue -u $USER
```
where the system understand  `$USER` as your username.

3) cancel your job 

```batch
scancel -j <my_jobid> 
```

<sup>(1)</sup>In linux, press `ctrl+alt+t`
### [back](#content)

----
## Using GRIDUNESP {#gridunesp}
GRIDUNESP is the UNESP HPC system.

check:

1. environments 
2. modules , avail, load, 
3. renomear uma biblioteca 
4. NUNCA MEXER NO .bashrc
5.   .bashrc_profile 
6. likelihood cobaya 

1) Acessing it
```
ssh <my_username>@access2.grid.unesp.br
```

note: <spam style="color:red">**avoid**</spam> to login in <spam style="color:red">__access__</spam>.grid.unesp.br


2) Basic Structure: 

$HOME

$STORE

Running jobs in GRIDUNESP:

1) 

2)


### [back](#content)
---
## Using NERSC {#nersc}
Accessing CORI/NERSC through ssh. Be aware that it is a 2 factor authentication. 

```
ssh <my_username>@cori.nersc.gov
```


### [back](#content)

