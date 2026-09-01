# L2 – Print something small
Individual Research: DfAM
Orientation-choose printing direction before you begin your design. This impacts finish roughness and printing time. 

45-Degree Rule- I 45 degree overhang is recommended when designing models. IF an angle becomes too steep, it risks collapsing without proper support. Designing items with a 45 degree overhang can also lead to faster printing time and less material usage. Designers can work around this by dividing the part into smaller sections, changing the geometry or reorienting the model. Another option to work around the overhang is to change the material so that it can endure a greater overhang. 

Source used- https://bigrep.com/posts/design-for-additive-manufacturing/

Proper Adhesion- If a printed model cools too quickly, this can lead to bad adhesion. Finding the correct temperature and nozzle can help prevent inadequate adhesion.

# Download
Downloaded model from:
https://www.printables.com/

The design must fit the following criteria:

-Max height:0.25 in

-dimension- 2in X 2in or smaller

-must have a flat surface

-print time 1.5 hours or less.

After some searching I landed on this print: https://www.printables.com/model/553028-peeking-cat-bookmark
<img width="1427" height="757" alt="image" src="https://github.com/user-attachments/assets/eb01cee6-37fd-4e6c-b9d6-b3429fd4718a" />
I decided to go with this print because not only did it fit the requirements but it is also something that I can always use outside of class. 
prints that I considered choosing:
<img width="1422" height="767" alt="image" src="https://github.com/user-attachments/assets/97c2e00d-c3c4-400d-95ee-6568c63d7759" />
Ultimately did not choose this piece, because the height for this print exceeded the 0.25 inches. 
# Preprocessor
Using Prusa Slcer, I opened the file and noticed that the print exceeded 2 inches. The original print measured 32.2mm(x direction) by 76.94mm(y dir.) by 2.3mm(z dir). Converting this to inches, I get a print with a dimension of 1.27 by 3.03 by 0.09.
<img width="1915" height="1198" alt="Screenshot 2026-08-27 131414" src="https://github.com/user-attachments/assets/fc84f253-88b1-46ef-9955-75af6a7fd3d2" />
Slicer information before scaling:
<img width="347" height="356" alt="Screenshot 2026-08-27 131420" src="https://github.com/user-attachments/assets/cf069f2f-6fb6-4ded-852b-e74b20f65911" />

I decided to scale the print down just enough for the y direction measurement to be under 2 inches. Once I scaled it down, the print had dimensions of 0.83 in. by 1.986 in. by 0.0594 in. 
<img width="1917" height="1198" alt="Screenshot 2026-08-27 132123" src="https://github.com/user-attachments/assets/ed9f10fc-14a5-414b-bf35-88efa1edabfc" />
After scaling down the print, I clicked on "slice down" and I recieved a breakdown of the print time:
<img width="435" height="315" alt="Screenshot 2026-08-27 132131" src="https://github.com/user-attachments/assets/80898b25-1e76-450e-829d-21dd5cc2918d" />

At this point, we got into small groups and we combined out 4 parts and we exported G-Code. 

<img width="1920" height="1128" alt="image" src="https://github.com/user-attachments/assets/ef6f80da-58f5-4d97-9225-9ebf360af62b" />

Scaling factor for each print:

<img width="960" height="564" alt="Screenshot 2026-08-29 153918" src="https://github.com/user-attachments/assets/76cb820a-a264-4bb3-8665-4c227afd83ba" />

<img width="960" height="564" alt="Screenshot 2026-08-29 153924" src="https://github.com/user-attachments/assets/41ded70f-2c68-4e4b-a6ee-0f7f3d59040b" />

<img width="960" height="564" alt="Screenshot 2026-08-29 153929" src="https://github.com/user-attachments/assets/006cddf7-012d-4b98-bb0b-d0f609f6aceb" />

<img width="960" height="564" alt="Screenshot 2026-08-29 153935" src="https://github.com/user-attachments/assets/38c0ca9a-db16-4ab3-b193-1b6f688d9370" />
# print
Group members:
Derek H.,
Brendan S.,
Nathan J.,
Luz R.
Before printing, we made sure to change filament to PLA. 
We then saved our file to the USB drive and headed over to the printing lab. 
Print right after being removed from the printer. 

<img width="1903" height="2189" alt="IMG_6297" src="https://github.com/user-attachments/assets/6183d775-339c-4db2-97df-942469915d74" />

Total Print time: 25 Minutes

# Lessons Learned
- It's important to always double check what filament the printer you are using is equipped with. If you choose
- print orientation matters. While moving all our pieces into PrusaSlicer, some prints would show up sideways and not on a flat surface. Having the prints in a sideways orientation, meant that we would need to include supports.
- After playing around with the setting under print settings and  reading https://help.prusa3d.com/article/support-material_1698 , I learned that PrusaSlicer is able to automatically add supports in a print. The three supports if offer are Grid, Snug, and Organic. PrusaSlicer also has the option to add supports in manually.
- Once all the designs were printed and we were removing the prints out of the mat, my piece cracked a little. This is possibly due to the print being on the thin side. If I could go back and change my print, I would change the thickness to the bookmark. This would make the removing process and prevent it from breaking.

