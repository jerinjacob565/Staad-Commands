# STEPS TO USE STAAD (beam)
Question 
![Screenshot 2023-08-03 160551](https://github.com/jerinjacob565/Staad-Commands/assets/82531317/75559a99-52d6-4288-ad59-6cb7605c1a03)

 ## STEP 1 
New file<br>
Rename<br>
Space<br>
Meter<br>
Kilonewton<br>
Add Beam<br>
 ## STEP 2
 Geometry <br>
 Add Beam<br>
 Add Beam from Point to Point <br>
 ## STEP 3
 General<br>
 Property<br>
 Define <br>
 Rectangle<br>
 .................................              Yd:0.4 (must be large)<br>
 .................................              Xd:0.2 (must be smaller than YD)<br>
 Add,close <br>
 Assign to view 
 ## Step 4 Support 
 Create ----Fixed <br>
 create....Pinned<br>
 create....Pinned<br>
 Create....Pinned<br>
                  Use cursor to Assign
  ## Step 5 Load And Deflection 
Load case details....Add  Dead Load, Live LOad <Br>
Dead lOAD......ADD....selfweight<br>
Live load ....ADD.....member load .....Concentrated Force ......-10 KN for this question <br>
d1=1,d2=0  <br>
Add,close<br>
live load ......uniform force.....-2 for this question<br>
live load ......linearly varying ........W3  -5kN for this question <br>
Self weight...Assign to view....assign...<BR>
Load case details ...ADD...DEfine combine....default ...1.5 <br>
>>add,close<br>
 ## step 6  Design
 concrete <br>
 Current code....is 456<BR>
select Parameter <br>
FY<br>
FYMAIN<br>
FYSEC<br>
MAXMAIN<br>
MAXSEC<br>
MINIMAIN<br>
TRACK<br>
assign to view <br>

 
 
