<p align="center">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Yara-R/Les-Observablees-IquHACK2024">

  <a href="https://github.com/Yara-R/Les-Observablees-IquHACK2024/commits/main/">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Yara-R/Les-Observablees-IquHACK2024">
  </a>

   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">

</p>

# Les Observables - <a href="https://github.com/iQuHACK/2024_Classiq/tree/main">iQuHACK2024</a>

This repository contains the code and documentation for the project developed by Les Observablées during the MIT Quantum Hackathon (<a href="https://www.iquise.mit.edu/iQuHACK/2024-02-02">IQuHACK</a>). 

Our project focuses on addressing the Classiq challenge and leverages quantum computing techniques to find the most accurate approximation of tanh(x) in the domain of 
```latex
f(x) =|0, 1> -> |0, 1>
```

Please read Classiq’s Generalized Arithmetic Challenge.pdf to better understand the challenge.

### Main Results:

## Honourable Mention for the most creative algorithm
![alt text](https://github.com/Yara-R/Les-Observables-IquHACK2024/blob/main/Honourable%20Mention.jpg)
![alt text](https://github.com/Yara-R/Les-Observables-IquHACK2024/blob/main/Winner%20accouncement.png)

## Algorithm approximation results (precision = 6)
Using 2-segment linear approximation and only one control bit, the approximation points plotted against $tanh(x)$
![alt text](https://github.com/Yara-R/Les-Observables-IquHACK2024/blob/main/Pieces_wise_percision_6.png)

## Theoretical approximation
![alt text](https://github.com/Yara-R/Les-Observables-IquHACK2024/blob/main/theoritical%20approximation.png)

<a href= "https://www.desmos.com/calculator/twgnswn4hd" >Here</a> you can see all the curves we tried throughout the hackathon

### Team Members:

<a href="https://www.linkedin.com/in/aakash-warke-5128a916b/">Aakash Warke</a>

<a href="https://www.linkedin.com/in/chu-hsuan-abraham-lin-69474019a/">Chu-Hsuan (Abraham) Lin</a>

<a href="https://www.linkedin.com/in/erica-sturm-398569113/">Erica Sturm</a>

<a href="https://www.linkedin.com/in/freesia-gaul-896287237/">Freesia Gaul</a>

<a href="https://www.linkedin.com/in/yara-rodrigues-inácio-b14203236/">Yara Rodrigues</a>



## Installation

To install you will need a classiq account.

You will run:

```bash
!pip install -U classiq

import classiq
classiq.authenticate()

from classiq import *
```
Click on the hyperlink to validate your access


