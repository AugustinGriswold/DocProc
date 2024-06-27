# Evaporator

> [!WARNING] Preflight checks  
>
> - [ ] Turn on cooling water >20 gph, turn on at the sink.  
> - [ ] Compressed air ~70 psi.  
> - [ ] LabVIEW, STM-2 and material information txt file open.  
>
> **In the LabVIEW program,**
>
> - [ ] `Shut Down System?` or `Shutting Down System...` has a green light.
> - [ ] `Hornet COM port` set to COM 9.  
>
> **In the STM-2 program,**  
>
> - [ ] The crystal is reading a frequency  
> - [ ] The lifetime of the crystal is >90% (We do not have a hard number for this, instead we say that it should be changed about every 3 runs or so...)  
>

## Preparing the Deposition  

- Once Preflight checks are done, fill out the logbook.
- Vent the chamber (`Vent Chamber to ATM?`) and wait for hissing to stop.  
- Lift the bell jar and remove the front shield.  
- If the slides are opaque, replace them.  
- Vacuum the chamber to remove flakes.  
- Find the crucibles containing the materials you plan to deposit. Inspect for cracks or holes and replace if present. Fill to ~80% if low.
- Place crucibles into the hearth, which we denote as LEFT/CENTER/RIGHT with X for an empty slot, and the chemical symbol for a loaded slot.  
- Center the metal reflector on the material you will deposit first.  
- Remove the sample holder from the top of the chamber, and load samples with Kapton tape. Replace the sample holder.  
- Close the shutter.
- Replace the front shield. The front shield should slip behind the back shield with the viewport and glass slides aligned so you can see.  
- Pull down the bell jar, ensuring it is fully in contact with the bottom.

## Pump down

- Get ~11 lbs liquid Nitrogen from chemstores. This will fill the entire dewar.
- Pump down the tool with `Pump to Hi-Vac` and fill the funnel ~1/4 full.
- Every 12 minutes, fill the funnel again. Do this until the ion gauge reaches <2.5 uTorr.
- Once at pressure, add another round of nitrogen.
- 