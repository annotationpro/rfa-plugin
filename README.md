# rfa-plugin
Rhythm Formant Analysis plugin for Anotation Pro based on Dafydd Gibbon's RFA tools. For details regarding the concept of the tools please refer to https://wwwhomes.uni-bielefeld.de/gibbon/Dafydd_Gibbon_Publication_PDFs/Dafydd_Gibbon_Publications.html (e.g. the 2024 publications)
The Annotation Pro plugin has been developed so that the original Python code (https://github.com/dafyddg/RFA) with further updates by Dafydd Gibbon is launched from within Annotation Pro by means of the C# plugin named RFA. The results are therefore obtained with the original Python script and operated by the user via the Annotation Pro graphical user interface.  

Several minor edits have been introduced to the Python script (but not to the core functionality, just technical things to successfully launch the script and add comments in the cmd window). 

**How to use the Annotation Pro RFA plugin**
In order to use the plugin:
1. You must have the newest version of Annotation Pro (above ver 3) 
2. Ensure that you have Python 3.x installed on your system, as the plugin relies on this to function correctly. If you do not have Python, you may install it separately or together with the plugin files (see below) which is convenient.

**Operation modes of the RFA plugin for Annotation Pro**
Two operation modes of the RFA plugin for Annotation Pro are available:
1. Audio Layer RFA -
The Audio Layer RFA mode uses the wave file currently open in Annotation Pro as input for the analysis. 
3. Chart Layer RFA - 
The Chart Layer RFA uses Annotation Pro chart layer as input. The data in the chart layer must be in numerical format and the number can represent any types of values (frequency, distance, intensity, space etc.). Example chart layers for analysis could be the layers representing movement variability obtained from Motion Capture, e.g.  imported from BVH files (see the BVH import summary here: Import BHV to Annotation Pro). 
