# The CCNC
A Cheap (Relatively), yet capable CNC router/mill
<br> 
-----
![Cheaper_CNC_Master_Build_Threaded_2022-Jul-21_03-48-01AM-000_CustomizedView20607925930](https://github.com/potatoworld/CCNC/assets/37276609/3f392ea6-2e18-456e-ad06-828fdff8bcd0)
![Cheaper_CNC_Master_Build_Threaded_2022-Jul-15_05-47-59AM-000_CustomizedView9717156544](https://github.com/potatoworld/CCNC/assets/37276609/b4e3dd9c-8f25-42ac-a409-4a4063d7723c)
![Cheaper_CNC_Master_Build_Threaded_2022-Jul-15_05-22-21AM-000_CustomizedView19849931560](https://github.com/potatoworld/CCNC/assets/37276609/58769810-5b29-40f4-9b49-0999aff6ab67)

The Goal for this project is to create a relatively cheap (Sub $500CAD) CNC Machine that is capable of cutting wood, plastics and soft metals. 

This machine utilizes many 3D Printed parts in order to keep costs down, assuming you already have a 3D Printer. Some printed parts have off the shelf alternatives, some can also be replicated in wood using basic hand tools, while other (Mainly the X Gantry Uprights) have to be printed. More information is found in the documents.

The machine/files should be relatively adapatble to different use cases

This assembly guide is rough, but will be refined and updated as the design gets better overall

# Parts (bill of materials)

The Bill of Materials is available in multiple versions
PDF
Spreadsheet
Markdown

There are a few tools that are required to put this machine together;

* Metric Hex/Allen Keys
* Jigsaw with metal cutting blades/Chop saw (Essentially some way to cut the aluminum extrusions and leadscrews)
* M5 Tap Drill
* Circular Saw (To cut the MDF Spoilboard)
* Drill bit set


# Prepare Raw Materials

#### 1. Print and Prepare required parts
Follow the Print Settings file in the STLs Folder

#### 2. Cut Aluminum Extrusions
Follow the Cutlist file, I would recomend not cutting the X Axis extrusions until the uprights are mounted in order to get a snug fit. 

#### 3. Tap Aluminum Extrusions
All of the extrusions need to be threaded with an M5x0.50 tap, except for the 2 frame crossmembers.

#### 4. Cut Lead Screws
Follow the cutlist file if you need to cut your leadscrews, if you purchase the legnths I listed in the parts list, there is no cutting required

# Build the Machine

## 1. Assemble the frame

#### 1. Mounting the Extrusions
Start by mounting a pair of 520mm extrusions to each pair of brackets as shown in the photo (Using M5x20 SHCS). Then attach the 450mm Crossmembers using the corner brackets.
![Cheaper_CNC_Master_Build_Threaded_2022-Jul-27_03-12-39PM-000_CustomizedView15145977333 (2)](https://user-images.githubusercontent.com/37276609/181285714-c22e731b-7568-4b3b-9684-3f5220d3062a.png)

#### 2. Mount the Linear Rails
Mount the 500mm Linear rails on top of the top most frame rail using M3x8 SHCS as well as M3 T-Nuts. Leave 10mm of gap on either side of the rail.
![Cheaper_CNC_Master_Build_Threaded_2022-Jul-27_03-23-58PM-000_CustomizedView48378132536 (2)](https://user-images.githubusercontent.com/37276609/181287748-cdc954f7-093f-4acd-ae3b-4c0472d55cf3.png)


#### 3. Mount the Pillow Blocks and hard stops
Mount one pillow block to each of the front frame brackets using M5x16 SHCS. Use the top screw to also mount the Y Axis hard stop. I would recommend tapping these holes as well.
![Cheaper_CNC_Master_Build_Threaded_v2_2022-Aug-07_02-21-52AM-000_CustomizedView17407069426](https://user-images.githubusercontent.com/37276609/183272396-67e349ea-c75c-4993-9f20-b628a69330cf.png)


#### 4. Mount Stepper motors 
Prepare 2 stepper motors by installing a flexible coupler onto each, then mount one to each of the rear frame brackets using M3x55 SHCS and the 3D Printed Spacers.
![Cheaper_CNC_Master_Build_Threaded_v2_2022-Aug-07_02-25-20AM-000_CustomizedView8771721841](https://user-images.githubusercontent.com/37276609/183272423-f46f13af-0c4b-4dec-b20f-2f84fbdbb9c8.png)

#### Frame is Assembled
Ensure frame is square by utilizing a carpenters square and that all bolts are tight.



## 2. Assemble the X Axis Gantry

#### 1. Prepare the Uprights
Install T-Flanges into the X Gantry Uprights

#### 2. Mount Uprights to Frame
Using 16 M3x18 SHCS, mount both uprights to to the frame as shown in the photo. 
[Cheaper_CNC_Master_Build_Threaded_v2_2022-Aug-07_02-33-53AM-000_CustomizedView3710265809](https://user-images.githubusercontent.com/37276609/183272637-f534e99f-406f-4ec1-a07f-7fb0adbf4d35.png)


#### 3. Install X Axis Extrusion and Rails
Using 4 M5x20 SHCS, Mount both 530mm extrusions to the uprights. The small flanges should help the extrusions stay square during assembly. 
![Cheaper_CNC_Master_Build_Threaded_v2_2022-Aug-07_02-40-22AM-000_CustomizedView10348442718](https://user-images.githubusercontent.com/37276609/183272678-7b2bfb1f-1580-469a-be05-887b54f815ff.png)


#### 4. Install X Axis Stepper Motor
Prepare the stepper motor by installing a flexible coupler onto the shaft, then mount to the right side upright using M3x55 SHCS and the 3D Printed Spacers.
![Cheaper_CNC_Master_Build_Threaded_v2_2022-Aug-07_02-43-08AM-000_CustomizedView12554706739](https://user-images.githubusercontent.com/37276609/183272723-6fde183e-a196-4f94-9bbd-a3d79d0ba8bf.png)


## 3. Assemble Z Axis Gantry

#### 1. Mount the Linear Rails

#### 2. Mount the Motor

#### 3. Attach Z Axis to X Axis

#### 4. Attach Spindle Mounting Plate

#### 5. Install Lead Screw

#### 6. Install Spindle Mount

## 4. Install Lead Screws and Wiring

## 5. Wire up the Machine



----
Yes, these instructions aren't great. I am planning on releasing a much more detailed video tutorial once V2 is finalized. I am still constantly iterating and upgrading this machine and don't want to create a detailed guide only for it to be outdated within days.


----

### License
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

