# Eletrostatics

This repository contains a notebook that can be used to plot the theoretical eletric equipotential lines from point-like charges.
It is possible to use functions to generate charge structures as desired.

This notebook can be used to see if real measurements fit in the theoretical equipotential lines, *or just to enjoy the plotted images.*

##

**Python** is needed to run the notebook. *Enter this [link](https://www.python.org/downloads/) if python is not installed yet.*

<pre>
Python dependencies:
  
Essential : jupyter matplotlib numpy
Optional  : pandas
</pre>

<details>
  <summary><b>About Optional</b></summary>

  > In this notebook, the library ```pandas``` is used to read csv files, it's useful if it's desired to plot measured points on top of the theoretical equipotential lines.
  > 
  > *If this feature is not desired, then all all lines related to the ```GetData()``` function should be commented.
  > Then, to generate the charges, it's possible to use a selected value for the charge or input an artificial point with a chosen eletric potential that was "measured" in that point.*

</details>

## Installation:

1. **Installing dependencies:**
   
  ```bash
  pip install jupyter matplotlib numpy
  ```

2. **Clone this repository:**
   
  ```bash
  git clone https://github.com/sunbaee/Eletrostatics.git
  ```

3. **Entering jupyter:**
   
  ```bash
  jupyter notebook
  ```

Then, in jupyter notebook, you can access the ```Eletrostatics``` folder and use the notebook as pleased.

## Plot Previews:

#### *1. Equipotential lines of two charged particles in the positions:*

![two points](https://github.com/user-attachments/assets/beabab95-a64c-49c8-8991-7709679352bb)

##

#### *2. Equipotential lines of two charged bar-like objects:*

![image](https://github.com/user-attachments/assets/16706040-df4a-484e-a3e6-22ca5a2ecbe7)

##

#### *3. Equipotential lines of two charged bar-like objects with a metal cilinder in the center:*

![image](https://github.com/user-attachments/assets/0c388ad5-fd0f-428b-85bf-d2c2089a7eac)

##
