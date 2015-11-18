# PtProofs
Latex macro to help with the assignments for the Programming theory course at UU. I can not guarantee correctness. Use at your own discretion. 

## Usage Example
```
\documentclass{article} 
\usepackage{./ptproof} %assuming ptproof.sty is in the same directory
\usepackage{amsmath}
\usepackage{amssymb}
  
\begin{document} 
    
Example 3.3 from the compendium:
\begin{align*}  %use align* instead of align or eveery line wil have its own numerical tag.
&\lnot T        %The & in the beggin is super important. Formating will be broken otherwise.
\Rnl{1.6} 
\lnot(e \vee \lnot e) 
\Rnl{1.4}
\lnot e \wedge \lnot \lnot e 
\Rnl{1.5} 
\lnot e \wedge e
\Rnl{1.1}
e \wedge \lnot e
\Rnl{1.7}
F \qquad \square
\end{align*}

\end{document}

```

Resulting output:


![alt tag](https://github.com/TheGrandmother/PtProofs/blob/master/example.png)



