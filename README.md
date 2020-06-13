# interval-timer
Interval Training timer

# Meeting Notes: Add Workout Flow Sync
Takeaways:
- combine Claire's details overall design
  - pills for tags
  - button for 'apply timings to all workouts'
  - Yenni's display of contextual data (workout, block, exercise details) and back arrow
- button placement - where should the "add" buttons be for adding a block or adding an exercise, e.g. you already added some, and want to add more
- differentiate between within circuit rest time, and between circuit rest times

# Meeting Notes: Add Workout Flow Sync w/ Hal
- distinguishing between lap and set
  - lap: number of times to repeat block before moving on to next block
  - set: number of times to repeat exercise before moving on to next exercise
- need a way to change active seconds between laps e.g. first lap active is 30s, second lap is 45s (duplicating circuits? adding extra parameter)
- repeater block? do we need blocks? or just exercises that can be repeated
- need a data model for warm-up up type exercises

Questions to think about for next meeting:
- what are the minimum building blocks (active/rest at a minimum? )?
- what are the parameters/options for each building block type? (do we need different blocks for EMOM, untimed (just a sequence?), no rest, etc.)
- should users be able to create their own block?
- how do we label blocks?
- biggest frustration with other timer apps: too structured - let's aim for flexibility

- need a detail/summary view
