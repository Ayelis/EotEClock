# OWClock

This mod adds a clock overlay to Outer Wilds. It can be set to count up, or down to the sun exploding.
Default events included in this version include events based upon DLC content.

There's also an additional event logging system; upcoming events defined in `events.json` are displayed above the clock, turning red as they approach.
New events can be added from the pause menu (timestamp will be set to the current loop time).

## Options
 - Count Up: Counts the elapsed seconds and minutes. When off, will count down to events/the end of the loop
 - Milliseconds: For speedrunners; uses millisecond timestamps
 - Events to Display: Number of upcoming events to display
 - Event List Width: Fraction of the available resolution that the event list can take up

## KNOWN ISSUES
Running this during more intensive moments seem to sometimes cause a BSOD with CRITICAL_PROCESS_DIED (At least on my PC). If anyone has this issue (or a solution), please let me know.
