# era5_superres
Experiments with super resolution on a dataset based on ERA-5 total precipitation data, with each image being a monthly average reanalysis from 1959 to 2022 in the region of continental europe. lat (-20,40) long (20, 80).

The super resolution model is a CNN model based on ESPCN (Efficient Sub-Pixel CNN), proposed by [Shi, 2016](https://arxiv.org/abs/1609.05158)

## original images 
![orig](https://github.com/fmerizzi/era5_superres/blob/main/images/full_low.png)

## results

original image 


![h](https://github.com/fmerizzi/era5_superres/blob/main/images/higres.png)


low res image 


![b](https://github.com/fmerizzi/era5_superres/blob/main/images/lowres.png)


prediction image  


![c](https://github.com/fmerizzi/era5_superres/blob/main/images/prediction.png)


upcubic image


![d](https://github.com/fmerizzi/era5_superres/blob/main/images/upcubic.png)


### PSNR 

psnr for preditction-> 37.79356977061858




psnr for bicubic-> 39.83953856869394

### MSE 

mse for preditction-> 9.029675925925925




mse for bicubic-> 4.9872453703703705
