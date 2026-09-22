# A5 – Design A Snap Fit

## Objective  
Parametrically design an assembly of two constituents that snap together by treating the parts as cantilever beams and solving for the geometry using the beam bending equations.

## Analyze  

The design I came up with is a U-shaped bracket with two right triangle extrusions that act as clips for a coin-shaped cylinder to snap into. The cylinder is attached at the bottom to a longer cylinder shell with two cuts down the length so that a squeezing action can be performed on the cylinder.  

<img src="DesignOG.jpg" alt="Description" width="40%" />

Before I could model my parts parametrically in SolidWorks I did a combination of choosing dimensions and solving for the related dimensions to accommodate for loads and dimensions. I began by analyzing an axial load that would be applied to the individual clips when the cylinder would be pushed against it  using an allowable stress found from the yield strength and a safety factor. These calculations would give me a minimum area the back of the clip would need to prevent fracture. I figured this would be a good place to start because I would use the height of this clip as the deflection the connected beam would need to undergo, which I will use in later calculations. I used an estimated 8 lbf for this axial load.     

<img src="axial.jpg" alt="Description" width="40%" />  

Now that I have an minimum area, I can decide a base/height and width, and check to ensure they met the minimum requirement. Throughout my design process the height I chose did not change, but I reduced the width. I didn't want to overcompensate for the axial load and make it more difficult to flex the part.  

<img src="bwchoose.jpg" alt="Description" width="40%" />  

Next I needed to solve for the length of the to arms of the bracket, I had already decided the width in the last part, and just needed the base of the arm, which I labeled b2. I decided to make b2 the same as the width so it would be a square cross section, both for ease of calculation and appearance, I didn't want to make it less than the width, and cause the length to be too long, as it wasn't needed for my design. I used beam bending formulas for a cantilever beam with a concentrated load at the free end. First I used the one with consideration of a flexing deformation, which would be the height of the clip I solved for. Then I used the beam bending equation in consideration of maximum stress, or in this case the allowable stress in relation to the safety factor.  

<img src="lengthsolve.jpg" alt="Description" width="40%" />  
<img src="lengthstrength.jpg" alt="Description" width="40%" />  

The larger of the two lengths would be what I needed to use, which was 1.28 inches.  

I then checked for shear stress in the clip, and compared it to the allowable shear stress, using the safety factor and shear strength of PLA.  

<img src="clipshear.jpg" alt="Description" width="40%" />  

Finally I created dimensions for the parts of the bracket and cylinder that did not carry loads that needed to be considered or calculated. The connection between the arms I chose as 1.0in so that it would be relatively proportional to the arms, and its thickness I dimensioned to be less than the arms so that it would have less impact on the flexure of the arms. For the cylindrical piece, I made the top cylinders diameter 0.005 inches less than the width of the gap between the arms(0.6 in). I did this to account for accuracy tolerance limitations of the Prusa, from research I found this tolerance to be about 0.004 inches. The 0.005 inch difference would ensure that the cylinder wouldn't print to a diameter larger than the gap.  

The lip between the top cylinder and bottom hollow cylinder on each side was 0.05 inches wide, this lip is where the clip would be against when in the clipped in position, so they are equal in width. the diameter i


## Decide


## Communicate

