# L10 – RC2 Sliding Fit Design

## Research and Planning
<img width="1132" height="706" alt="Screenshot 2026-11-09 181430" src="https://github.com/user-attachments/assets/f512f20d-2b2e-4332-a082-fe2e079a436b" />

### Inner piece:
Width Tolerance: -0.0002 in , -0.00045 in  
Length Tolerance: -0.00025 in , -0.00050 in

### Outer Piece:
Width Tolerance: +0.0004 in , -0.0000 in  
Length Tolerance: +0.0004 in , -0.0000 in

I designed this fit to be used as a method of connecting joints. My thought process was to use this sliding fit similar to how wooden dowels work by connecting piece together through slide fits. For this, we have two beams that have a hollowed out end that can slide fit into a connecting join that will connect the two beams together. This can be used in artisan wooden working however the structural integrity of this fit may render it suboptimal to be used in large scale construction of buildings or machines.

## Cad Design

Outer Piece: [Outer Piece](L10outer.SLDPRT)

Inner Piece: [Inner Piece](L10inner.SLDPRT)

Assembly: [Assembly](L10Assm.SLDASM)

<img width="750" height="500" alt="Screenshot 2026-11-09 174214" src="https://github.com/user-attachments/assets/8f618dab-080f-4725-8a5e-d8572cf725fb" />

This is the design of the outer piece and the dimensions that will be used for this piece.

<img width="750" height="500" alt="Screenshot 2026-11-09 174328" src="https://github.com/user-attachments/assets/70c93ec0-baf3-4d56-8e20-281686ac5a8f" />

This is the fully extruded model of the outer piece, we can see the hollowed out end where the inner piece will slide into. The length of the none hollow piece is adjustable, the length is set for printing purposes but it can be any length depending on the needs of the application.

<img width="750" height="500" alt="Screenshot 2026-11-09 174346" src="https://github.com/user-attachments/assets/9b51ef51-200e-4d05-9954-9064a1a806d8" />

This is what the dimensions of the inner piece. It is made to fit within the outer pieces on ends.

<img width="750" height="500" alt="Screenshot 2026-11-09 174352" src="https://github.com/user-attachments/assets/1f58a241-de82-4a41-a6cd-516a66be6a0c" />

This is the extruded inner piece, its just a rectangle that is used to connect the two outer pieces in order to connect them, this can be done multiple times for instance if the outer pieces have the hollowed sections on each side to connect multiple in sequence.

<img width="900" height="500" alt="Screenshot 2026-11-09 175038" src="https://github.com/user-attachments/assets/24314a8e-ca3c-4781-8a86-8118c742e0ac" />

This is the completed assembly of the sliding fit demo. The gap in the middle is for viewing purposes only and can be completely covered by the slide fit to improve the structural properties of the assembly. 

## Preprocessing for 3D Printing

Machine Name: HallowedDodo

<img width="700" height="500" alt="Screenshot 2026-11-16 131131" src="https://github.com/user-attachments/assets/dc997757-21b2-4da0-a70c-e46ee7bda475" />

I chose to make my build orientation from the auto "1 click" feature because after asking staff present in the lab, I was told that this method was the most effective for orientation.

<img width="700" height="500" alt="Screenshot 2026-11-16 131847" src="https://github.com/user-attachments/assets/7f84561a-fb29-40b8-9838-33539756c286" />

The build was 705 layers and took 1 hour and 40 minutes to complete. The thickness chosen was .05 mm. I had it set to .1 mm but once a printer was selected, the thickness changed to .05 mm automatically so I chose to keep this thickness to avoid any unintended errors during the printing.

<img width="500" height="500" alt="Screenshot 2026-11-18 104603" src="https://github.com/user-attachments/assets/b0a4ad64-9d2c-469f-8e97-225fe6330205" />
<img width="1022" height="728" alt="Screenshot 2026-11-18 104454" src="https://github.com/user-attachments/assets/ae06e732-4f38-4863-a1e8-4e014ef8c01f" />


Volume: 20.57 mL (two projects) , allowable clearance for shrinkage was made too small because I set the RC2 tolerance to a value that was smaller than the minimum dimensional accuracy of the printer.

## Post-Processing

<img width="1008" height="772" alt="Screenshot 2026-11-22 134719" src="https://github.com/user-attachments/assets/8a558ecf-0609-4cfd-8b59-217f8d48add2" />

This is the printed design after the printing and washing. I chose to cure the prints with the supports still attached because I was told it would help to maintain structure while curing. However after curing, the supports were hard to sand once removed. This among other reasons lead to the slide fit not working.

<img width="1008" height="686" alt="Screenshot 2026-11-22 134733" src="https://github.com/user-attachments/assets/2e9ca6d1-276c-45c2-806a-e4b2629c4fff" />

This is what was the result from the fit not being made properly. You can see on the sides where supports were and how those exposed and lifted materials could assist in the fit not working properly.

## Fit-Test

The fit was unsuccessful. If you look at the drawing you will notice how the tolerances were less than .1 mm. This means that the tolerances set were too small for the resin printers to work with. This is the primary reason that the fit was unsuccessful.

## Lessons Learned

The main lesson I learned was about the tolerances. I want to try and think about this like I would about governing stresses when designing parts. Now I will know to calculate the tolerances needed for the fit I am designing for and then compare those results to the printer's tolerances and then I will create the fit based on which ever value is larger. 

