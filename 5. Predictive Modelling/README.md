# Comp-activ CPU usr prediction
![cpu](https://github.com/Saiganesh3838/Mini-Data-analytics-and-ML-projects/assets/157223211/dc86ab17-fa87-47ab-a10c-4209ac5d2acb)


## Context
The comp-activ database comprises activity measures of computer systems. Data was gathered from a Sun Sparcstation 20/712 with 128 Mbytes of memory, operating in a multi-user university department. Users engaged in diverse tasks, such as internet access, file editing, and CPU-intensive programs.

Being an aspiring data scientist, you aim to establish a linear equation for predicting 'usr' (the percentage of time CPUs operate in user mode). Your goal is to analyze various system attributes to understand their influence on the system's 'usr' mode.

## Data Description

| Column Name | Description |
| --- | --- |
| lread | Reads (transfers per second ) between system memory and user memory |
| lwrite | writes (transfers per second) between system memory and user memory |
| scall | Number of system calls of all types per second |
| sread | Number of system read calls per second |
| swrite | Number of system write calls per second |
| fork | Number of system fork calls per second |
| exec | Number of system exec calls per second |
| rchar | Number of characters transferred per second by system read calls
| wchar | Number of characters transfreed per second by system write calls |
| pgout | Number of page out requests per second |
| ppgout | Number of pages, paged out per second |
| pgfree | Number of pages per second placed on the free list |
| pgscan | Number of pages checked if they can be freed per second |
| atch | Number of page attaches (satisfying a page fault by reclaiming a page in memory) per second |
| pgin | Number of page-in requests per second |
| ppgin | Number of pages paged in per second |
| pflt | Number of page faults caused by protection errors (copy-on-writes) |
| vflt | Number of page faults caused by address translation |
| runqsz | Process run queue size (The number of kernel threads in memory that are waiting for a CPU to run |
| freemem | Number of memory pages available to user processes |
| freeswap | Number of disk blocks available for page swapping |
| usr | Portion of time (%) that cpus run in user mode |

# Project- 2

## Objective
In your role as a statistician at the Republic of Indonesia Ministry of Health, you have been entrusted with a dataset containing information from a Contraceptive Prevalence Survey. This dataset encompasses data from 1473 married females who were either not pregnant or were uncertain of their pregnancy status during the survey.

Your task involves predicting whether these women opt for a contraceptive method of choice. This prediction will be based on a comprehensive analysis of their demographic and socio-economic attributes.

## Description
1. Wife's age (numerical)
2. Wife's education (categorical) 1=uneducated, 2, 3, 4=tertiary
3. Husband's education (categorical) 1=uneducated, 2, 3, 4=tertiary
4. Number of children ever born (numerical)
5. Wife's religion (binary) Non-Scientology, Scientology
6. Wife's now working? (binary) Yes, No
7. Husband's occupation (categorical) 1, 2, 3, 4(random)
8. Standard-of-living index (categorical) 1=verlow, 2, 3, 4=high
9. Media exposure (binary) Good, Not good
10. Contraceptive method used (class attribute) No,Yes
