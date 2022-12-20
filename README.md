# Reinforcement Learning based Miltimodal Summarization (RLMS)


###  System archiecture of RLMS
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/mainarc-crop.jpg)

###  We show the execution of RLMS in two medthods:
### Method 1 : Using GoogleColab

### Open google colab

[GoogleColab](https://colab.research.google.com/)

###  Under the section Runtime --> Change runtime --> GPU

![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%20(329).png)
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%20(330).png)
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%20(331).png)


###  Check the gpu version
```python
!nvidia-smi
```


### We create two packages for RLMS in the PyPI Repo named: MO-RLMS for GoogleColab and MI-RLMS-MO for local Jupyter Notebook
### Step-1 : To install MO-RLMS in GoogleColab type the following command: 
```python
!pip install MO-RLMS
```
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%202022-12-20%2019.22.47.png)

### Step-2 : Type the following command to test the RLMS in GoogleColab 
```python
from MO_RLMS import get_summary_multioutput
get_summary_multioutput()
```
### Jump to Step-3 to test the RLMS


### Method 2 : Using Local Jupyter Notebook

### Step-1 : Use the following command to install the MI-RLMS-MO package on your local system in Local Jupyter Notebook 
```python
!pip install MI-RLMS-MO
```
### Step-2 : To test RLMS type the following command
```python
from MI_RLMS_MO import get_summary_multioutput
get_summary_multioutput()
```

###  Step-3: To test the RLMS approach

#### We use the Multimodal news data available at the news articles in this news website to test the RLMS approach

[https://www.voanews.com/](https://www.voanews.com/)
#### We can use the URL of any news article available at above website as shown in the following figure:
### News article (test_link) 
```python
https://www.voanews.com/a/russia-shells-kherson-part-of-broader-attack-on-southern-ukraine-/6881528.html
```
### Output:  Following is the Multimodal Summarized Output obtained for the ![Test news URL](https://www.voanews.com/a/n-korea-fires-2-ballistic-missiles-in-resumption-of-testing-/6881249.html)

![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%202022-12-20%2019.30.52.png)





