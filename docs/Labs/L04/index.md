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

I used a 40% infill and I scaled the thickness of the model by 200%, this was because the model appeared too small and narrow to have efficient infill. Building on that reason was why I chose to use 40% infill as well.


## Preprocessor



## Communicate

