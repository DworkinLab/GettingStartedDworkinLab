RT PCR Dworkin Lab old protocol (not yet updated)
================================================


1. Spec the RNA samples using a nanodrop and run a gel to determine concentration and integrity.  Dilute to the desired concentration. Then transfer the dilution to a 96well plate.  Make sure you have enough solution in the plates to account for error (i.e. add 5microL more then you need)
2. Hydrate Primers to a concentration of 100microM using RNase free water
   1. Calculate the amount of H2O that needs to be added using the amount of nMole given on the information sheet for each primer
   2. Example: 35.1nMoles = 351microL of H20 added
1. From the Hydrated Primers make a solution of equal parts forward and reverse primer to a final concentration of 10microM. (i.e. add 10microL of each primer to 80microL of RNase free water)
2. RT-PCR recipe (for one rxn) added in the order listed
   1. H~2~O: 1.9microL
   2. 2x QF RT-PCR Mix: 5microL
   3. Primers: 1microL
   4. QF RT Mix: 0.1 microL
   5. Template: 2 microL
   6. Total reaction volume: 10microL
1. Make enough of the RT-PCR master mixes to account for error, or enough for one or two extra rxns.
EpMotion 5070 editor (top left-hand corner of the desktop)
Note: This part is all in the Ep Motion 5070 Basic User Protocol made by David, it will be near the robot.  There are pictures and everything!  You should set this part up the day before you want to run your RTPCR so you have time to check everything over.
1.  Inset sdcard then select Top-directory (E:/top).  Check to make sure “dongle found” appears at the bottom left-hand corner of the screen, otherwise you will not be able to save your layout to the sdcard.
2. Set up the worktable.  
A1 = TIP50F epTIPS Motion 50 miroL, Filter
A2 = 1.7ml Epi Tubes (Master Mixes)
B1 = thermocycler plate 1 (Templates)
B2 = thermocycler plate 2 (RTPCR rxn plate, empty to start)
1. Set up procedure
   1. Reagent Transfer of MMs
      1. Add 8microL from A1 to B2
      2. Check filter tips, irregular source pattern, and that you mix 3x for 15mm/sec and 8microL
      3. Change tips when command finishes
   1. Sample Transfer of templates (RNA)
      1. Add 2microL from B1 to B2
      2. Check filter tips, irregular source pattern, and that you mix 2x for 15mm/sec and 2microL
      3. Change tips before each aspiration
   1. Reagent Transfer of water controls
      1. Add 10microL from A1 to B2 
      2. Check filter tips and irregular source pattern
   1. Reagent Transfer of noRT controls
      1. Add 8microL from A1 to B2
      2. Check filter tips…..3x for 15mm/sec and 8microL
   1. Sample Transfer noRT controls (RNA)
      1. Add 2microL from B1 to B2 
      2. Check filter tips….2x for 15mm/sec and 2microL
   1. Reagent Transfer noTemplate controls (MMs)
      1. Add 10microL from A1 to B2 
      2. Check filter tips….
   1. Sample transfer noTemplate controls (H2O)
      1. Add 2microL from B1 to B2
      2. Check filter tips….


Note: this is how I set it up, but you can change it to make more sense to you
1. Set up sample pattern
   1. If works best if you set up a layout of your plate before hand in excel (see attached document)
   2. If you mess up you will have to start over, so go slowly!  And double check!
1. Add comments where you need them (e.g. “Distribute Master Mixes” or “Distribute sample templates”)
2. Save!  This is important because it does not save changes as you go.  Save it into the E:/top under your name.
3. Double check that all your patterns are correct and that everything has the right conditions
4. Hurray you have made a program for the robot!


RealPlex (underneath the EpMotion Editor icon)


Note: this should also be done the day before so you have time to check that everything is correct


1. It will ask you to sign it, you can create your own account or you can use the “Chandler” account and the password is “drosophila”
2. Open a new template
3. Check that 520nm filter = SYBR and 550nm is blank
4. On the right choose DT_TwinTec10microL for calibration, SYBR Green for probe, and 10microL for volume
5. Set up the plate in the layout that you have (blue for samples and yellow for controls)
6. If you are using these primers for the first time then run a melting curve.  The procedure is attached to that back of the Ep Motion 5070 Basic User Protocol packet


epMotion 5070 “The Robot”


1. Switch on the workstation and properly inset the sdcard 
2. Login to Admin using the password ‘5070’ and press OK
3. Go into the sdcard folder and copy the program that you made using the editor
4. Paste this program into a user folder (preferably your own), this allows the program to run smoothly
5. Press Start
6. In the worktable display, check that the supply of the worktable and confirm with ok
7. Then the display for the volume inputs will appear automatically.  Enter the volumes in microL and confirm with OK
8. Check that the Tip Racks have enough tips in them and that all tubes are open and that the waste container is empty
9. Make sure the hood is closed and press start
10. Then let it do its thing.  You might need to come back and feed it more tips.  It will beep at your until this is done
11. After completion press shutdown and switch off the workstation.  Then return everything to its proper place and seal thermoplate 2
12. Turn on the RTPCR thermocycler and place your plate inside (make sure A1 is in the top left corner).  Then click the start button in RealPlex.  Let it run it will take an hour or so.  Then click “start analysis” and you will get your ct values.
