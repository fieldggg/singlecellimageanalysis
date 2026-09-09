Hi, if you are here maybe you are a neurobiologist like me, or more computational, or something else entirely whether that be inside of science or not

Anyways I am happy you decided to look at these scripts

I hope they are pretty self explanatory, if not please do not hesitate to reach out with any questions about use, application, or anything else that comes to mind




Some brief notes on running the scripts within this repository:

1. These are java scripts, but are able to be edited in any coding software whether that be Panda, RStudio, even a word doc, as long as the rules of java are followed
2. In order to run these scripts you must have a version of FIJI that was released after 2023 (has bioformats installed)
3. This script will automatically terminate if the images in your input folder are not tiffs (so no ndpis, czis, omis, etc)
4. You can have your images on an offloaded drive, if just has to be connected to the computer you are running the script on the entire time
5. This script can analyze thousands of cells in a single scan, so make sure your ROI is only your region of interest, or the script will analyze everything
6. These are human made scripts(i.e. me), so there might be errors or grammatical mistakes, if you run into any please let me know





In order to run these script:

1. Download or copy the script, and save the file to your desktop or a location easily accessible
2. Read through the script and make sure you have made the proper edits where noted (i.e. changing tested antibody names, thresholds)
   
   -  I have given thorough instructions on how to make these changes and where within the script
3.  Read through the script and make sure you have made the proper edits where noted (i.e. changing tested antibody names, thresholds)
    -  I have given thorough instructions on how to make these changes and where within the script
    - I have given thorough instructions on how to make these changes and where within the script
4.  Make sure your image folder with a corresponding results folder is ready
5.  Open FIJI
6.  On the top bar select 'Plugins' -> 'Macros' -> 'Run'
7.  Run!
8.  Find and select your saved script


 ** if fiji gives you errors about size or memory, this is not a script issue, this is a fiji memory per use issue**

 to fix this on the top bar select 'Edit' -> 'Memory & Threads' -> increase your limit, try to run the script again
