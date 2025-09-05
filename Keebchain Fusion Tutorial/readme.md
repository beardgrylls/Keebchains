# Here go the general steps I followed using Fusion360:

1. Fill all the empty space within the case (deleting faces, extruding, push/pulling, whatever you need to do to make it not hollow). After it's filled, I leave a 1mm gap from the case top. Randomly chosen just so the caps will sit below the top face
![Step 1](https://github.com/DashDashUnderscoreDash/Keebchains/blob/main/Keebchain%20Fusion%20Tutorial/Step%201.png)

2. Add caps. I went through the trouble of modeling something that looked cap-like (18mm square base about 7/8mm tall, with 15 degree angled side walls). We found that making the top face of the caps parallel with the case bottom reduces print time a ton and looks better. Adding caps was the most time consuming part for me. Mainly just placed one cap, used a rectangular pattern to do the full row, then move/copy feature to copy and move one cap down a row and repeat. For the non 1u caps, I split the body in half with a construction mid-plane, moved one of the new bodies over however many units it needed, then extruded the split face to join them again.
![Step2.1](https://github.com/DashDashUnderscoreDash/Keebchains/blob/main/Keebchain%20Fusion%20Tutorial/Step%202.1.png)
![Step2.2](https://github.com/DashDashUnderscoreDash/Keebchains/blob/main/Keebchain%20Fusion%20Tutorial/Step%202.2.png)

3. Scale everything down. I used a scale of .2182 (making Denali 50mm wide, but decided to match the scale for Laela), but any scale around that should be fine

4. Finally, add the ring. These are dimensions I used and extruded to a thickness of 2.25mm. I also added small fillets around the ring, but that's likely unnecessary
![Step4](https://github.com/DashDashUnderscoreDash/Keebchains/blob/main/Keebchain%20Fusion%20Tutorial/Step%204.png)

*Worth noting, I just had at it following no guidelines, so there could very well be easier ways to accomplish each step. If something feels right to you, don't feel like you need to do what I did*
-HaiZeus
