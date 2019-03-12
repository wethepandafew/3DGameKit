# 3DGameKit
This is the *ORIGINAL* 3D GAME KIT w/ some assets added onto it.

* Do not reupload this exact file without making changes, 
  if changes are made re-upload as a new file and SPECIFY changes.

* Folder hierarchy: **Pandamonium > Original3DGameKit > OriginalBuild3.12** The last folder is the project

*ONCE OPEN YOU CAN SAVE AS WHATEVER YOU WANT/CHANGE NAMES AND REORGANIZE BUT PLEASE SPECIFY IN A READ ME WHAT YOU HAVE DONE WHEN YOU REUPLOAD, Thank you!*

  
## *CHANGES*

+ MAIN FILE
  - Added some free assets with the 3D Game Kit asset from the unity store.
   - Did not check the liceneses for these assets or 3D game kit
     (we can remove what is not allowable later on by simply deleting it and it's codes)
     
+ Basic Errors
  - Assets/PostProcessing/Editor/PropertyDrawers/MinDrawer.cs(6,34): error CS0104: 'MinAttribute' is an ambiguous reference between 'UnityEngine.PostProcessing.MinAttribute' and 'UnityEngine.MinAttribute'
  
  - Replaced code/made changes to fix this (Should keep changes after I saved and uploaded/ if this error shows up when you download and reopen the file on your comp then go to the MINDRAWER . md file below this file and copy the code and paste it inplace of what is on your file.
  - To get to the MINDRAWER . css file just double click on the error in the console panel on your project and it should open visual studio or whatever program you use. *if this does not work go to **Assets > Post Processing > Property Drawers > MinDraw.cs**
  
  - **AFTER YOU SAVE THE CHANGES** A box in unity will ask if you want to keep changes/update etc > Click YES (I've made a backup) and then let it update. The errors will go away.
              
### MUST DO ON EACH MACHINE

+ Fix this error
  - **Error:** Assets/3DGamekit/Scripts/Game/Utility/QualitySettingPostprocessProfileSwitch.cs(19,37): error CS0012: The type 'Enum' is defined in an assembly that is not referenced. You must add a reference to assembly 'netstandard, Version=2.0.0.0, Culture=neutral, PublicKeyToken=cc7b13ffcd2ddd51'.
  
  - Fixed by going to **Window > Package Manager > Post-processing > UPDATE-TO**
  - Once updated the error should go away. This may be needed everytime you open this project on a new machine.
        *THIS IS IMPORTANT TO DO SO PLEASE DO THIS.*
