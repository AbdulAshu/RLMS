# Reinforcement Learning based Miltimodal Summarization 


###  System archiecture of RLMS
![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/mainarc-crop.jpg)

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



![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%20(333).png)

###  To test the rlms approach
[We use the Multimodal news data available at the news articles in this news website:](https://www.voanews.com/)

### We publish our own package at PyPI (Colab)
```python
!pip install MO-RLMS
```

### To run our our RLMS with an example in colab
```python
from MO_RLMS import get_summary_multioutput
get_summary_multioutput()
```
### We publish our own package at PyPI (Local)
```python
!pip install MI-RLMS-MO
```
### To run our our RLMS with an example in local
```python
from MI_RLMS_MO import get_summary_multioutput
get_summary_multioutput()

```


###  Install package in colab

![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%202022-12-20%2019.22.47.png)

###  Working mechanism of RLMS in colab

![alt text](https://github.com/PhaniSiginamsetty/RLMS/blob/main/img/Screenshot%202022-12-20%2019.30.52.png)

### News article (test_link) 
```python
https://www.voanews.com/a/russia-shells-kherson-part-of-broader-attack-on-southern-ukraine-/6881528.html
```


