# Void_Nicator

This is a script for creating your own performances, songs, events, speeches, rituals, and sermons.

After installing, you may test out the pre-loaded example by simply entering: ***nicator perform firstperformance***
    
   *Note: be certain to not capitalize any of the words*

This will fill your command window with the first movement in a performance. Simply hit enter and it will act it out and fill your command line with the second movement in the performance. All you need to do is hit enter over and over again and it will go through the entire performance.

## Adding Performances

To add a performance, open the **Nicator's Bones** script. In the *void.nicator.performances* table, start a new table named whatever you want the performance to be called. Here is an example of the formatting:

```lua
  myperformance = {
    [[emote steps to the centre of the stage]],
    [[say This is my first performance]],
    [[say I hope you like it!]],
    [[emote crosses their eyes for an uncomfortable length of time.]],
    [[emote (With a theatrical flourish,) bows deeply.]],
  },
```

## Starting a Performance

To begin one of your performances, enter ***nicator perform \<performance name\>***
Be sure to not add any capitalization or punctuation to the command.

As your performance continues, it will automatically fill your command line with the next movement. It will start with ***NICATOR PERFORM \<performance name\>***. Do not change these first three words, they are necessary for the script to function properly. "NICATOR PERFORM" is intentionally capitalized.

You may edit the performance on-the-fly by clicking into the command line and changing what will be sent.

I hope you enjoy!
