# Regulatory-grade FEA

*Placeholder for final, "regulatory-grade" FEA simulations*

Todo:
V&V:

1. Verification
  - [ ] Code verification? (i.e., MMS?)
  - [ ] Numerical verification (i.e., grid refinement study)
  - [ ] Material model verification: in collaboration with Confluent Medical, 
    - [ ] obtain lot-specific nitinol material properties
    - [ ] fit constants to raw material testing data 
    
2. Validation
  1. Fatigue testing with sub-component model
    - same material processing history as prototype devices (e.g., heat treating and electropolishing)
  2. Other?
  
  
  
Generic IVCF FEA:

1. Determine final geometry of generic IVC filter
  - [ ] Account for differences between design and manufactured prototypes (tolerances?)
  - [ ] Account for material removed during finishing processes (e.g., electropolishing)
2. Simulate sheathing (prestrain)
3. Simulate placement (contact area/length/forces)
  - [ ] Finalize IVC diameters used to represent variability in human population
4. Valsalva (fatigue)
  - [ ] Finalize boundary conditions (CI=0.5?)
