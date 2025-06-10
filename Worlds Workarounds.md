# Worlds Workarounds  

# __About__  
  This community-sourced collaborative document aims to provide a home for the running list of workarounds, ‘hacks’, and other alternative approaches that have helped creators overcome obstacles or break through barriers. These tips and tricks may not be common knowledge, but this document is meant to remedy that.
  <br><br>

<!-- # __Response Template__  

## **Title**  
Description  
<br>
**Steps**:	Steps to fix  
<br>
Additional Notes  

**Keywords**:  
Tested in v218  
**Credit**:  Username  
<br>

-->

# __Submission Form__  

  Worlds Workarounds can submitted via [this Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfazKdHlNWtwUvvvxSET1q-JaV__xUAzDYBxLNRon7FJEk0Rw/viewform). *Please fill out **_all required fields_**
  <br><br>

# __Desktop Editor Workarounds__  

## **Leaderboards/Quests Not Working in Desktop Editor**  
  Leaderboards, Quest boards not working in DE	
  
  **Steps**:	Test scripting in published world environment or in headset editor
  
  Sometimes it does take letting the server shut down before coming back and new quests, PPVs being accessible via scripting  
  
  **Keywords**: Desktop Editor, TypeScript, Quests, Leaderboards 
  Tested in v214  
  **Credit**:  MKE_TheGuru  
  <br>

## **Oversized Bounding Box Causing Issues**  
  Oversized bounding box with empty objects causing inability to change position.  
  <BR>
  **Steps**:	Leave the world and come back.  
  <BR>
  **Keywords**: Desktop Editor, Custom Model Import  
  Tested in v214  
  **Credit**:Tellous  
  <br>

## **Object Transform Handles Disappear**  
  Object transform handles disappear.  
  <br>
  **Steps**:	Leave the world and come back.  
  <br>
  **Keywords**: Desktop Editor  
  Tested in v214  
  **Credit**: Tellous  
  <br>

## **Grabable Objects Not Grabable**  
  Set an object top grabable and it’s not grabable  
  <br>
  **Steps**:	Leave Desktop Editor and come back  
   <br>
  **Keywords**: Desktop Editor, Object Interactivity  
  Tested in v214  
  **Credit**: Tellous  
   <br>

## **Can’t Export Geo from Standalone Editor**  
  Unable to export geometry using the standalone Desktop Editor. Dialogue Box does not show up to set directory  
  <br>
  **Steps**:	Use the Quest Link version and the popup will appear  
  <br>
  **Keywords**: Desktop Editor  
  Tested in v214  
  **Credit**:  MKE_TheGuru  
  <br>

## **Can’t Import World in Desktop Editor**  
  Unable to import other world into current world via the Desktop Editor  
  
  **Steps**:	Use the VR editor  
  
  This is because the Desktop Editor does not give us any option to import. In the VR editor, while in the target world, open the build menu, find the world you wish to import, click the 3 dots menu and choose import  
  
  **Keywords**: Desktop Editor    
  Tested in v214  
  **Credit**:  MKE_TheGuru  
  <br>

## **Object Alignment Issues**  
  Getting proper alignment of objects in the Desktop Editor is challenging due to lack of granular/intuitive transform controls  
   <BR>
  **Steps**:	Use the VR editor for more precision and robust snapping tools. Or use origin blocks when exporting from 3D software  
   <BR>
  **Keywords**: Desktop Editor, Custom Model Import  
  Tested in v218  
  **Credit**:  MKE_TheGuru  
  <BR>

# __Scripting Workarounds__  

## Local UIs not Loading Images on Binding Change  
  Local UIs are not loading previously unseen images when bindings change  
   <br>
  **Steps**:	Create a default-scripted UI somewhere in the world and fill it with all the UI images you’ll need the player to see, thereby pre-caching them.  
   <br>
  Local clients are unable to unload images they no longer need, causing high memory usage and a finite cap on images that can be cached in this way  
   <br>
  **Keywords**: TypeScript, Custom UI  
  Tested in v214  
  **Credit**:  blender93  
  <br>

## **Kudos Board Asset not Working in CMI World**  
  Kudos Board Asset not Working in CMI World  
  <br>
  **Steps**:	Remove all primitive mesh pieces that are part of the asset and try again  
  <br>
  **Keywords**: TypeScript, Custom model Import, In-World Purchase  
  Tested in v214  
  **Credit**:  High Octane Software  
  <br>

## **PPVs not Initializing When Needed**  
  Attempting to access player persistent variables through TypeScript yields error message "player persistent variables are still being initialised, returning empty state"  
  <BR>
  **Steps**:	Check if the player is a real player or not before setting/getting their PPVs  
  <BR>
  This normally happens when trying to set PPVs from local scripts, or for NPCs  
  <BR>
  **Keywords**: TypeScript, Player Persistent Variable  
  Tested in v214  
  **Credit**:  Daz1996  
  <BR>


