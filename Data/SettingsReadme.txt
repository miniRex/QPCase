I can't use comments in the json (or maybe yes, idk), so here is the same code with comments
This code has all the original values replaced with x
DO NOT PUT COMMENTS IN Settings.json!

Here is how the settings json looks like with comments:

{
  //I recomend doing a backup of Settings.json before touching anything

  "StartTab": x,
  //recent, all, settings, unknown (unknown tab means no tab opened)

  "DisplayTime": x,
  //The display time is the label that appears at the corner telling the current time

  "Transparency": x,
  /*The transparency value of the window. Recomended values higher than 35.
    Low values will make harder to see what you are actually doing*/
    
  "CloseOnExecute": true,
  //Close this when you execute a program

  "StartWithComputer": x,
  /*THIS IS NOT DONE YET!
    Start the program along with the computer, don't turn it on.
    And dont ask why it's here if it's unfinished :/ */

  //Dont expect a window scale setting, it would mess all up

  //DISPLAY
  /*This don't actually work, sorry :/
    This thing controls the colors, feel free to mess around with it
    Let me explain how it works. the color is a string because im lazy "Red,Green,Blue"
    COMMAS MUST BE BETWEEN VALUES*/

  "DepthBackground": x,
  "OverallBackground": x,
  "Background": x,
  "LightBackground": x,
  "Front": x,
  "Text": x

  //There are some colored text's that can't be changed, like the one in the settings save button
}