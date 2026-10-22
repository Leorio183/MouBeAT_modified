# MouBeAT
############# Leorio183 modified this macro script, the updated scripts are MouBeAT_modified_plotalso_onlyinsideROI.ijm and MouBeAT_modified_OFT.ijm#########################
#############Supports rectangular ROI: for the area set by the ROI, only the region inside it is calculated, rather than additionally calculating a ring of radius R around it as the original script does. In addition, when a field is selected during OFT analysis, the software by default widens it slightly and also includes the content within the slightly widened video area in the analysis; if a 2x2 OFT field is used and there is a mouse in the adjacent chamber, the problem of tracking multiple subjects will occur.##################################

 Toolbox for mouse behavioural analysis of several maze types:
 Open Field; Elevated Plus Maze; Morris Water Maze; Y Maze
 * Author - Helio Roque - Centro Nacional Investigaciones CardioVasculares, Madrid, Spain
 * Contact - Helioalexandre@hotmail.com 

 * To install the toolbox please download the MouBeAT.ijm file and copy it into the ImageJ/FIJI macro/toolset folder.
 * To use the conversion tools of the tool, either install FFMPEG in order to have it in the system path or download the ffmpeg.exe file and copy it into the folder mentioned in the previous bullet point.
 
 MouBeAT has now been published. If you use it in your paper please cite:
 
If you use MouBeAT in a publication please cite the following paper:
Bello-Arroyo E, Roque H, Marcos A, Orihuel J, Higuera-Matas A, Desco M,
Caiolfa VR, Ambrosio E, Lara-Pezzi E, Gómez-Gaviro MV. MouBeAT: A New and Open
Toolbox for Guided Analysis of Behavioral Tests in Mice. Front Behav Neurosci.
2018 Sep 7;12:201. doi: 10.3389/fnbeh.2018.00201. eCollection 2018. PubMed PMID: 
30245618; PubMed Central PMCID: PMC6137138.
