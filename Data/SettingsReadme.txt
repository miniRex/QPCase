I can't use comments in the json, so here is the same code with comments.
This code has all the original values replaced with x.
DO NOT PUT COMMENTS IN "Settings.json"!

Here is how the settings json looks like with comments:

{
  I recomend doing a backup of Settings.json before touching anything.
  I 90% sure that inside the program in settings there is a option to reset values.

  "StartTab": x,
  recent, all, settings, unknown (unknown tab means no tab opened).

  "DisplayTime": x,
  The display time is the label that appears at the corner telling the current time.

  "Transparency": x,
  The transparency value of the window. Min value is capped to 35.
  Low values will make harder to see what you are actually doing.
    
  "CloseOnExecute": x,
  Close this when you execute a program.

  "StartWithComputer": x,
  Start the program along with the computer, don't turn it on.

  DISPLAY
  This thing controls the colors, feel free to mess around with it.
  Let me explain how it works. the color is a string because is simple "Red,Green,Blue".
  COMMAS MUST BE BETWEEN VALUES

  "DepthBackground": x,
  "OverallBackground": x,
  "Background": x,
  "LightBackground": x,
  "Front": x,
  "Text": x

  There are some colored text's that can't be changed, like the one in the settings save button
  
  "NotifyUpdates": x
  This is just to toggle the notification that pops up when the version is not the same as the online version.
  It doesn't really matter, I won't release any updates any time soon, or yes, idk.
  If i release an update is gonna be in a lot of time.
}