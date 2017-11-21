# baffluence
The name is a short for bash-affluence.
This script get the data from [affluences](https://www.affluences.com/) and print them to the terminal.

### dependencies
It requires:
* bash (tested with 4.4), 
* wget (tested with 1.19),
* awk  (tested with 4.1),
* (coreutils).

### usage
To execute the script give it execute access.  
`chmod +x baffluence`  
  
Then, ask a library like:  
`./baffluence bsg`  
  
It should return:  
```
95% 
prevision:  
20h00	 95%  
20h30	 85%  
21h00	 75%  
21h30	 50%  
61-Paris-Bibliothèque Sainte-Geneviève-BSG
```
This library is one of the first of the [list](baffluence/blob/master/affluence.full.txt) so it works fine.
If your research does not work, i recommend you to check the [list](baffluence/blob/master/affluence.full.txt) to get your number. 

### todo
Add a search option, or make the picker function more accurate.
