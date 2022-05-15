# Image-steganography--LSB-DCT
# About
Hides text inside image in plain sight using LSB and DCT algorithms
LSB is implemented in matlab & DCT is in python
comparison.py compares between two images' MSE & PSNR and put the output in excel file

# Protection
LSB takes a key as input and mix it with the message so when a wrong key is passed the output is garbage 

# Usage 
LSB 
    
    run encodelsb.m enter image, key, message and output image 
    (don't use compressed image formats as input eg. jpg, jpeg etc...) 
    
    run decodelsb.m enter stego image and key
    
    use the apps for better interaction
    

DCT 
    
    run mathproject.py enter image, message and output image
    
    enter stego image 
                         

# Created by THE SYNDICATE math team EECE 25
