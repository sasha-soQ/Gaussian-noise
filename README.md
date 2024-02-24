# Median filter for Gaussian noise
This study aims to compare the effectiveness of a 2-pass 3x3 Median filter and a 1-pass 5x5 Median filter on Gaussian noise.
### Image Processing

*original img*  
<img src=https://github.com/sasha-soQ/Gaussian-noise/assets/109583554/b04a291e-05d6-4adb-9c51-27b25bee50db width=40% />

### 1. Define the Gaussian noise function and apply it to the image  

*Gaussian noise & img with noise*  

<figure class="a">
<img src=https://github.com/sasha-soQ/Gaussian-noise/assets/109583554/bb6ff7af-9807-4381-a3ea-99de01c03b5a width=40% />  <img src=https://github.com/sasha-soQ/Gaussian-noise/assets/109583554/631aa700-15a7-4e02-bd6a-09336e18d985 width=40% />  
</figure>  

### 2. Do zero padding 
### 3. Apply 2-pass 3x3 median filter / 1-pass 5x5 median filter

*imgs applied with 3x3 median filter & 1-pass 5x5 median filter*

<figure class="a">
<img src=https://github.com/sasha-soQ/Gaussian-noise/assets/109583554/821d2d80-8a09-43cf-b49d-e0f82391d7dd width=40% /><img src=https://github.com/sasha-soQ/Gaussian-noise/assets/109583554/0adc8c70-1e29-456c-8a6a-412458a05540 width=40% />
</figure>

### 4. Crop the excess zero padding
### 5. Define PSNR function and compare both images

2-pass 3x3 median filter - PSNR: 14.910927601055716

1-pass 5x5 median filter - PSNR: 18.254453808778262

<figure class="a">
<img src=https://github.com/sasha-soQ/Gaussian-noise/assets/109583554/d609b847-95de-46e8-a09b-cb27d4d8867b width=40% /><img src=https://github.com/sasha-soQ/Gaussian-noise/assets/109583554/f4e2ef66-2b92-4ef4-895e-b5abfc773793 width=40% />
</figure>
