# A4 – Benchmark

## Parameter
I chose the Overhang test to complete for this assignment. According to the Prusa website, the print can have up to a 75 degree over hang angle without supports. I believe that shortly after 75 degrees the print will experience a failure. It won't be right on 75 degrees because there was mostly likely a safety factor involved in the 75 degree estimate.

## Document Design
<img width="500" height="650" alt="L4sketch1" src="https://github.com/user-attachments/assets/aa70a3c5-8918-41f6-9a0d-8eed63989767" />

For this test, I wanted to make a progressive banking going up to 80 degrees. I made 10 degree marks every .3 inches, and then I made extra marks at 45 degrees and 75 degrees. 75 degrees was a mark for the max allowed angle that Prusa slicer can conventionally do without supports.

<img width="500" height="600" alt="L4sketch2" src="https://github.com/user-attachments/assets/6db56f50-0c63-4fa0-86f3-c1900d09ece7" />

Then I made this model .1 inches wide to reduce the amount of the material needed and also to reduce the print time. I also extended the leg on the bottom to half the length of the arc. This way the model would stay upright during the print and won't fail due to balance issues.

<img width="650" height="450" alt="L4Measurements" src="https://github.com/user-attachments/assets/d139131b-05ae-4125-8127-f8a47249e278" />

Then I needed a way to know at what angle the print fails. To accomplish this I added the measured angle at each marker that was created when I made the banking.

<img width="500" height="470" alt="L4slice1" src="https://github.com/user-attachments/assets/37e7b201-7b64-4aa0-ab09-e628f69305c3" />
<img width="500" height="470" alt="L4slice2" src="https://github.com/user-attachments/assets/7ed04244-8df7-4613-b46e-deb941efebe1" />

I used a 40% infill and I scaled the thickness of the model by 200%

## Preprocessor
I chose to scale the model thickness 200% because the model appeared too small and narrow to have efficient infill and to add extra stability during the print process. Building on that reason was why I chose to use 40% infill as well. I was initially planning on creating a banking like that in the first cad sketch, however I knew the way the printer built the structure, it wouldn't be tested for overhang the way that I intended. This is why I chose to make it an arch instead with a support on the bottom to keep it upright during the print. The idea of the test is to see what angle the print truly fails without supports, aside from the designed leg at the bottom to ensure the model kept balance I did not use any supports for this print. During this process I struggled to get the width of the arch correct due to the banking, because of this it was a challenge to create the angle measurement markers in the correct places. The true angle that each marker represents is slightly higher than where the markers indicate.


## Print Artifact

<img width="500" height="600" alt="L4sideview2" src="https://github.com/user-attachments/assets/4b537aed-0ebe-4848-bebf-dd3ee9d621e3" />
<img width="500" height="600" alt="L4sideview1" src="https://github.com/user-attachments/assets/d1891366-ea56-4bf5-ac3a-a4c28b3c883e" />

This model tested the max angle the Prusa One can print before it fails without supports. Here we can see that right after the 75 degree marker, the angle starts to dip and the print starts to deform because this is when the angle gets too steep for the print without supports.

[print video](https://github.com/nnicho12/Noah-Nicholson-Portfolio-Lab/raw/main/docs/Labs/L04/L4printvideo.mp4)

