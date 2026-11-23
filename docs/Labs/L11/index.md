# L11 – Snap Fit

## Documentation
<img width="500" height="550" alt="Screenshot 2026-11-23 151829" src="https://github.com/user-attachments/assets/29ca77cc-5b76-4ebb-a4cf-287565260f07" />

Using a narrowing cantilever design, this snap fit was made to have a socket and a joint that snap fits into the socket, it was modeled after a button press fit so it could be mass printed for uses like seating items on vertical surfaces or other materials. The SLA made it so the deflection had to be minimal due to its brittle nature and the fact that it was not ductile meant that the tolerances had to be very accurate.

## Snap Fit CAD Design

<img width="500" height="250" alt="Screenshot 2026-11-15 171336" src="https://github.com/user-attachments/assets/62f4ab10-ff33-46fc-b536-81ebd6f2c4f5" />

This is the top surface that will be on the top piece of the button fit. This is meant to be smooth and flat so it can seat neatly onto a wall or adhesive material.

<img width="750" height="500" alt="Screenshot 2026-11-15 173750" src="https://github.com/user-attachments/assets/664fac58-d71e-4d7a-9a9a-9c349a1d5d98" />

This is the portion of the top piece that will snap into place on the bottom piece. The sketch portion of this image will be revolved around the base creating a lip that if fitted correctly, will slide into the bottom piece and sit in a gap on the inside if the bottom piece.

<img width="1000" height="500" alt="Screenshot 2026-11-15 173800" src="https://github.com/user-attachments/assets/18318347-5108-402b-8998-da08b2f0e84e" />

This is the finished top piece that will be used to slide into the bottom piece, the cylinder in the middle is hollow because there is an extrusion on the base of the bottom piece that will help hold this top piece in position once snap fit in.

<img width="1000" height="500" alt="Screenshot 2026-11-15 180009" src="https://github.com/user-attachments/assets/4b784136-4c0f-4c6c-8179-dced72eacd55" />

This is the bottom piece of this snap fit. The extrusion highlighted is the piece that the cylinder on the top piece will fit around.

<img width="1000" height="500" alt="Screenshot 2026-11-15 184412" src="https://github.com/user-attachments/assets/2af46942-9f95-4d73-b2a0-fd3495b8ab81" />

 When completed this is how the two will fit together, the bottom piece has a narrow top opening that will widen further down and then the top piece's lip will sit in between the wall and the extrusion of the bottom piece. The only issue is that due to the limited ductility of the V5 resin, the top piece has a very small tolerance window to be able to fit into the bottom piece correctly.

## Preprocessing and 3D Printing

<img width="750" height="500" alt="Screenshot 2026-11-16 130803" src="https://github.com/user-attachments/assets/17f8ffcf-b70b-4f10-ab04-4d285ef39ec3" />

I will be printing 4 parts instead of just the two for this snap fit in this one printing operation. These are the parts leyed out on the plate.

<img width="750" height="500" alt="Screenshot 2026-11-16 131847" src="https://github.com/user-attachments/assets/5feb597a-f5de-4850-9a88-a78df8143598" />

Using the "1 click" feature, I had this arranged due to lab advisor recommendation as well as the fact that I had warnings for pooling even after adding holes to compensation for that factor, the "1 click" build orientation solved this problem while adding sufficient supports to my models as well.

## Post Processing 

<img width="500" height="500" alt="Screenshot 2026-11-18 104603" src="https://github.com/user-attachments/assets/1ce4c68c-2340-45bc-b643-118098aca094" />

This was a post curing picture that shows how the models were still with supports, I chose to do this because I was worried about the prints not holding shape while not being cured and having no supports. This would later be an issue however when it came to fitting.

## Fit Validation

<img width="750" height="500" alt="Screenshot 2026-11-18 104552" src="https://github.com/user-attachments/assets/3274f9a8-22cc-43f0-afa3-2acc9970d168" />

Due to the lack of ductility, the piece would not fit correctly, the goal was to allow for one side of the piece to enter first, then due to the widening depth of the bottom piece, the second half of the top piece would then be able to enter. However, this would require some flex which the V5 resin did not have. For this main reason, the fit would not be successful. The difference between my experience with the resin and FDM was the flex which would allow for more tolerance for fitting parts. Because of this, I was not accounting for the V5's stricter tolerance requirement. Overall, the main problem was the fit being too tight and it would not allow for the snap fit to function as intended.

## Lesson Learned

During this Process I learned that I need to think about what material properties my fits would require to be successful. In this case, I chose a fit that would require flex and higher ductility. I designed this fit thinking about how the fit would would based on FDM properties. If I were to do this again I would choose a different style of cantilever snap fit that would all for a fit that would not rely on as much on a flexing material for a successful fit. Additionally, I would remove the supports before curing to limit the edges that protrude from the final product due to the supports being harder to remove cleanly than prior to curing.
