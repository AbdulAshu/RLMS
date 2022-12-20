# Reinforcement Learning based Miltimodal Summarization (RLMS)


###  System archiecture of RLMS
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/mainarc-crop.jpg)

###  We show the execution of RLMS in two medthods:
### Method 1 : Using GoogleColab

### Step 1 : Open google colab

[GoogleColab](https://colab.research.google.com/)

###  Under the section Runtime --> Change runtime --> GPU

![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%20(329).png)
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%20(330).png)
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%20(331).png)


###  Check the gpu version
```python
!nvidia-smi
```


### We create a package for RLMS named: MO-RLMS in the PyPI repo
### Step-2 : To install MO-RLMS in GoogleColab type the following command: 
```python
!pip install MO-RLMS
```
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%202022-12-20%2019.22.47.png)

### Step-3 : Type the following command to test the RLMS in GoogleColab 
```python
from MO_RLMS import get_summary_multioutput
get_summary_multioutput()
```
#### We use the Multimodal news data available at the news articles in this news website to test the RLMS approach

[https://www.voanews.com/](https://www.voanews.com/)
#### We can use the URL of any news article available at above website as shown in the following figure:

![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%202022-12-20%2019.30.52.png)

### Output:  ![Test news URL :](https://www.voanews.com/a/n-korea-fires-2-ballistic-missiles-in-resumption-of-testing-/6881249.html)

### Method 2 : Using Local Jupyter Notebook

### Step-4 : Follow the following command to test the RLMS in Local 
```python
!pip install MI-RLMS-MO
```
### To test RLMS in local
```python
from MI_RLMS_MO import get_summary_multioutput
get_summary_multioutput()

```
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%20(333).png)

###  To test the RLMS approach



### News article (test_link) 
```python
https://www.voanews.com/a/russia-shells-kherson-part-of-broader-attack-on-southern-ukraine-/6881528.html
```


