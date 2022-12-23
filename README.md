# Reinforcement Learning based Multimodal Summarization (RLMS)
### Abstract
##### In this paper, we propose a reinforcement learning based multimodal summarization (RLMS) approach comprising of the agent and environment modules for summarizing the multimodal input (MI) data. The MI data consists of both text and image data. In the agent module, we introduce the image and textual features extraction approaches, and a fine tune transformer to generate the textual summary from the MI data. Similarly, the environment module comprises of the text context similarity (TCS) approach and the image selector (IS) approach. The TCS approach rewards the textual summary generated by the agent module. The IS approach uses the image similarity score to select an appropriate image from a set of images presented in the MI data. Finally, the RLMS combines the textual summary from the TCS approach with the image from the IS approach to generate the multimodal output (MO) summary. Experimental results show that the RLMS obtains 91% cosine similarity and 85% ROUGE-L scores when compared with the existing summarization approaches. Furthermore, we analyze the reinforcement learning reduces the training time required for generating the MO summary from the MI data.


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

##  Step-3: To test the RLMS approach

#### We use the Multimodal news data available at the news articles in this news website to test the RLMS approach

[https://www.voanews.com/](https://www.voanews.com/)
#### We can use the URL of any news article available at above website as shown in the following figure:
### News article (test_link) 
```python
https://www.voanews.com/a/n-korea-fires-2-ballistic-missiles-in-resumption-of-testing-/6881249.html
```
### Output:  Following is the Multimodal Summarized Output obtained for the ![Test news URL](https://www.voanews.com/a/n-korea-fires-2-ballistic-missiles-in-resumption-of-testing-/6881249.html)

![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%202022-12-20%2019.30.52.png)





