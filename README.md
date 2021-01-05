# Steganography

Steganography is the process of hiding a secret message within a larger one in such a way that someone can not know the presence or contents of the hidden message.

The purpose of Steganography is to maintain secret communication between two parties. Unlike cryptography, which conceals the contents of a secret message, steganography conceals the very fact that a message is communicated. 
 
Although steganography differs from cryptography, there are many analogies between the two, and some authors classify steganography as a form of cryptography since hidden communication is a type of secret message.

The secret can be in the form of a text or in the form of an image(i.e Hiding Text inside an Image or hiding Image inside an Image)

## Projects Links 

[Text Steganography](https://nbviewer.jupyter.org/github/Rahul1582/Image-Steganography/blob/master/Text%20Steganography.ipynb): Hiding Text Inside an Image.

[Image Steganography](https://nbviewer.jupyter.org/github/Rahul1582/Steganography/blob/master/Image%20Steganography.ipynb): Hiding an Image inside an Image.


## Technologies Used
```
1. Open CV

2. Least Significant Bit Steganography

3. Python Imaging Library
```

## Advantage Over Cryptography

The advantage of steganography over cryptography alone is that the intended secret message does not attract attention to itself as an object of scrutiny. 

Plainly visible encrypted messages, no matter how unbreakable they are, arouse interest and may in themselves be incriminating in countries in which encryption is illegal.

## To Run

Run the respective ipynb file and in the place of image choose the image you want to choose..

### Incase of Text Steganography

Then run the encode_data function to encode the desired data.

After encoding the data run the decode_data function to decode the encoded data.

### Incase of Image Steganography

Run the merge2img2 function by selecting the images.

And then run the unmerge2 function to get the initial image after merging.




## Results



<img src ="images/encode_data.JPG"  width=900 height=300>  
<br><br>

<img src ="images/decode_data.JPG"  width=900 height=330>
<br><br>

### These were the Images before and after encoding the data in Text Steganography:--
<br><br>

| Original Image | Image After Encoding |
| :---: | :---: |
| <img src ="images/originalimage.JPG"  width=400 height=300>  | <img src ="images/finalimage.JPG"  width=400 height=300> |

<br>

### These were the images before and after encoding images in Image Steganography..
<br><br>
Image 1 is merged on Image 2..

| Cover Image | Image to be Merged |
| :---: | :---: |
| <img src ="images/orig.PNG"  width=400 height=300/> |  <img src='images/orig2.PNG' width=400 height=300/> |

<br>

| Merged Image | Unmerged Image |
| :---: | :---: |
| <img src ="images/final_merge.PNG"  width=400 height=300/> |  <img src='images/final.PNG' width=400 height=300/> |


## Author 
```
Rahul Kumar Patro
```

