# LearningFlexHub
**Public code release for:** *A Network Science Cartography of Cognitive Control System Dynamics*

**PhD Candidate Qualifying Examination**, Rutgers University Center for Molecular and Behavioral Neuroscience, 2018

**Carrisa Cocuzza** (carrisacocuzza@gmail.com), The Cole Lab (http://www.colelab.org/)

See README.md for general usage instructions and comments

## Directory Structure
Ordered by project workflow (e.g., not alphabetical)

**Directory:** partitionDemos/

- Contains demo code for implementing the Cole-Anticevic (CA) network partition to organize functional connectivity (FC) estimates (e.g., adjacency matrices) into a network community structure. Also contains demo code for assessing empirical resting-state reassignments in relation to the CA partition and applying this empirically adjusted partition to task-evoked FC data (and to be used for analyses represented in the following directories) 

**Directory:** restTaskFC_Comparisons/

- Contains demo code for assessing rest-to-task changes in FC; e.g., descriptive analyses of changes to FC architecture between resting state and task-evoked state(s); as opposed to mechanistic and/or functional analyses (see below) 

**Directory:** networkDiagnosticMetrics/

- Contains demo code for diagnosing network-mechanisms of interest. Diagnostic metrics demonstrated include: global variability coefficient (GVC), between-network variability coefficient (BVC), and network flexibility (NF) 
- See networkDiagnosticMetrics/References.txt for a full reference list associated with each metric (and additional info on public repositories outside of github) 

**Directory:** npdDemos/

- Contains demo code for implementing our novel diagnostic metric, network partition deviation (NPD), as well as follow up analyses related to NPD 

**Directory:** controlCartography/

- Contains demo code for implementing our cartographic representation of cognitive control system functioning, vis-a-vis the previously demonstrated analyses and diagnostic metrics 

**Directory:** masterScriptsMATLAB/

- Contains MATLAB scripts, functions, and helper scripts to run all analyses on independent datasets (e.g., related to, but standalone from demo code in the prior directories). Note that the bulk of this code may be attempted with the open-source software Octave 

**Directory:** masterScriptsPython/

- Contains python scripts, functions, and helper scripts to run all analyses on independent datasets (e.g., related to, but standalone from demo code in the prior directories). Note that this project was originally written in MATLAB, so these scripts serve as the python adaptation to the code in masterScriptsMATLAB/

**Directory:** sampleResults/

- Contains sample figures and videos associated with the project herein. See sampleResultsText.txt for associated text. 
