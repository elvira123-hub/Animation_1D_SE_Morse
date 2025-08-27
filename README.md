# Animation_1D_SE_Morse
:relaxed: Play with eigenvalues and eigenvectors in few second :tada:. Morse potential is one the realistic model which help to describe better diatomic interaction. This code help to know the highest value of the vibrational quantum numbers

## 1 - Packages 

First, import all the packages that you will need.

- [numpy](www.numpy.org) is the fundamental package for scientific computing with Python.
- [matplotlib](http://matplotlib.org) is a famous library to plot graphs in Python.







<details>
  <summary><font size="3" color="darkgreen"><b>Click for hints</b></font></summary>
       
   * `numpy` has a function called [`np.exp()`](https://numpy.org/doc/stable/reference/generated/numpy.exp.html), which offers a convinient way to calculate the exponential ( $e^{z}$) of all elements in the input array (`z`).
 
<details>
          <summary><font size="2" color="darkblue"><b> Click for more hints</b></font></summary>
        
  - You can translate $e^{-z}$ into code as `np.exp(-z)` 
    
  - You can translate $1/e^{-z}$ into code as `1/np.exp(-z)` 
    
    If you're still stuck, you can check the hints presented below to figure out how to calculate `the Morse potential` 
    
    <details>
          <summary><font size="2" color="darkblue"><b>Hint to calculate Morse potential</b></font></summary>
        <code> V(z)=De[1-np.exp({-alpha(z-ze)}]^{2}</code>
    </details>


</details>
