## SCCS-NY 2021 - Species Distribution Modeling for Conservation in R & Wallace: A Wallace workshop


# Description
Species distribution modeling (SDM) is an important tool for conservation scientists, as it enables us to estimate present species range limits and make predictions about ranges for other areas and time periods. Advances in model-building and evaluation theory are common in the ecology and evolution literature. However, most cutting-edge methods are only accessible to those scientists who can read and write computer code, which results in a ‘barrier to use’ for many potential users. The Wallace ecological modeling application, implemented in the R programming language as the CRAN package “wallace”, provides a graphical user interface allowing any user to implement advanced SDM methods. Additionally, Wallace provides extensive guidance text and references key papers from the literature to help both new and experienced users learn best practices. Each model-building session can be exported as a fully documented R Markdown script file, to ensure reproducibility, ease of reporting, and for more advanced users, an easily modifiable code that extends Wallace’s functionality. In this workshop, we will go through the basics of SDM using Wallace. We will demonstrate the key features of the modular software, show applications to conservation science, and specifically the utility of SDM outputs for formal IUCN assessments.


# Organizers
- Beth E. Gerstner, Michigan State University
- Samuel Chang, Pace University 
- Bethany Johnson, City College of New York, CUNY
- Gonzalo Pinilla-Buitrago, City College of New York, CUNY

# Logistics
- Date: Thursday, October 7, 2021
- Time: 1:00 PM to 4:00 PM
- Place: Zoom

# Workshop Schedule
- 1:00 - 2:00: Intro to SDMs & Applications
- 2:00 - 2:30: Wallace overview
- 2:30 - 4:00: Working with Wallace

# Pre- and Post-Workshop Survey Links
Please take the pre- and post-workshop surveys. They really help us!

- [Pre-workshop survey](https://docs.google.com/forms/d/e/1FAIpQLScObNbLwPsQU8IMeiGBPazdJzc2xodw2JTndC82mCVqSmYY3g/viewform?usp=sf_link)

- [Post-workshop survey](https://docs.google.com/forms/d/e/1FAIpQLSe5l1W07bwiZ6epCF2nQViDTLXOVmWCtJYKVbFthBxjXWe4qg/viewform?usp=sf_link) 

# Background R Materials
*You do not need to know this information to effectively begin using Wallace. However, this will give you a better understanding of what Wallace is doing behind the scenes (and it may be helpful if you see a future in research!).*

- [Short introduction to R/RStudio](https://mlammens.github.io/SCCS-R-Wallace/docs/Intro-to-RStudio.html)
- [Even shorter introduction to R/RStudio](https://github.com/bgerstner90/SCCS_2021/blob/f8719086341de081676dd0cf3a77e9d4c18e53f9/Crash-Course-R.html)

# Installing R/RStudio and Wallace
*Please install R and Wallace prior to this Workshop. Downloading Wallace in R can take a while depending on your computer.*
1. Install R (version ≥ v.3.5.0) and Rstudio 

2. Install the ‘wallace’ package from CRAN (v.1.0.6; stable)

   - Once you have both R and Rstudio, open Rstudio.
   - In the console write 'install.packages("wallace") and hit enter
   
   *A note that this will take R quite a while to download so set aside at least 20 minutes for this*

3. Once Wallace is installed (you'll notice in Rstudio the stop button will disappear), you can try and run it. To do this:

   - In the console write "library(wallace)" and hit enter
   - Then write "run_wallace()" and hit enter. Make sure you have a browser open because the Wallace page will open through your browser.


# Data for workshop
*During the workshop, we will allow you to choose your own species to work with during the demo portion. However, in the event of internet connectivity issues or issues with GBIF during the workshop, we have included a dataset you can work with here.*
- [Download Olinguito data here](https://drive.google.com/drive/folders/11E2Dt1Y1BLTE5t0IvQEnUSDagckhvv5M?usp=sharing)



# Wallace Specific Resources
- [Wallace homepage](https://wallaceecomod.github.io/)
- [Link to Wallace How-to Vignette](https://wallaceecomod.github.io/vignettes/wallace_vignette.html)



