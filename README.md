# Replication Package for "Modeling the evolution of topics in source code histories"

Stephen W. Thomas, Bram Adams, Ahmed E. Hassan, and Dorothea Blostein  
[Mining Software Repositories Conference - MSR 2011]()

Abstract: Studying the evolution of topics (collections of co-occurring words) in a software project is an emerging technique to automatically shed light on how the project is changing over time: which topics are becoming more actively developed, which ones are dying down, or which topics are lately more error-prone and hence require more testing. Existing techniques for modeling the evolution of topics in software projects suffer from issues of data duplication, i.e., when the repository contains multiple copies of the same document, as is the case in source code histories. To address this issue, we propose the Diff model, which applies a topic model only to the changes of the documents in each version instead of to the whole document at each version. A comparative study with a state-of-the-art topic evolution model shows that the Diff model can detect more distinct topics as well as more sensitive and accurate topic evolutions, which are both useful for analyzing source code histories.

## Bibtex

```bibtex
@inproceedings{Thomas11,
 author = {Thomas, Stephen W. and Adams, Bram and Hassan, Ahmed E. and Blostein, Dorothea},
 title = {Modeling the Evolution of Topics in Source Code Histories},
 booktitle = {Proceedings of the 8th Working Conference on Mining Software Repositories},
 series = {MSR '11},
 year = {2011},
 isbn = {978-1-4503-0574-7},
 location = {Waikiki, Honolulu, HI, USA},
 pages = {173--182},
 numpages = {10},
 url = {http://doi.acm.org/10.1145/1985441.1985467},
 doi = {10.1145/1985441.1985467},
 acmid = {1985467},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {lda, software evolution, topic models},
} 
```

## Data and Scripts

Here we supply the data and results of our studies thus far. 

- [JHotDraw data](https://github.com/SAILResearch/replication-evolution_topics_code/releases/download/v1.0/jhotdraw.tar.bz2) (203MB). 
- [PostgreSQL data](https://github.com/SAILResearch/replication-evolution_topics_code/releases/download/v1.0/psql.tar.bz2) (619MB). 
- [Simulated project data 1](https://github.com/SAILResearch/replication-evolution_topics_code/releases/download/v1.0/sim1.tar.bz2) (11MB), [data 2](https://github.com/SAILResearch/replication-evolution_topics_code/releases/download/v1.0/sim2.tar.bz2) (12MB), and [data 3](https://github.com/SAILResearch/replication-evolution_topics_code/releases/download/v1.0/sim3.tar.bz2) (12MB). 

A comparative view on topics' evolution for all systems is available [here](resources/topics.pdf). 

## Tools

The preprocessing tool (lscp) can also be found on [GitHub](https://github.com/doofuslarge/lscp). 
We hope to have the Diff tool online soon. 
