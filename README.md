# Outlier-Detection-and-Removal
## types of Outlier handling techniques
### z score technique 
credits:bit.ly/393HjIP (what is Outlierand  more)

credits:bit.ly/3KTs9Dp (normal distribution data)

credits:bit.ly/3KVyDll (skwed data)



this technique helps you to find if there is any Outlier or not  with the formula of ![image](https://user-images.githubusercontent.com/68773015/167293260-fcda5741-82a0-49b2-911b-10040211c7b3.png)

***this is only used if the data is in normal distribution ***

### iqr 
The interquartile range is calculated in much the same way as the range. All you do to find it is subtract the first quartile from the third quartile: IQR = Q3 – Q1. 


***this is only used if the data is in skewed data distribution ***

![skewed distribution](https://user-images.githubusercontent.com/68773015/167361842-fc6be400-501c-44ee-9568-08e72deba909.png)


after finding the Outlier the approaches are capping or Trimming

### Capping
the capping will keep two caps in min and max values it will not extend beyond that if it extends it will replace the value with the maximum or minimum values 
### Trimming
in Trimming it will remove the Outlier by taking the endpoints 
