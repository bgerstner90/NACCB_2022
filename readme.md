## NACCB 2022 -  Interactive, reproducible, and accessible species distribution modeling for conservation with Wallace


# Description
Species distribution modeling (SDM) enables conservation scientists to make range estimates for species of concern, as well as predictions of potential range in unsampled areas and for different time periods. Since the field’s inception 20 or so years ago, modeling and methodological best practices continue to advance at a rapid pace, and cutting-edge techniques are increasingly accessible only to those with advanced programming knowledge. We developed the application Wallace to lower the barriers for modern species distribution modeling by offering access to the latest programmatic tools through an interactive graphical interface. Wallace implements a range of analysis functions from existing packages in the R programming language without necessitating any user programming knowledge. Additionally, Wallace offers extensive guidance text that explains methodological details and theory with literature references using simple language that benefits both new and experienced users. Each session can be exported as a readable, documented script that can be run to reproduce the analysis in R. The Wallace application is available in the R package wallace, with a single function that opens the interface. In this workshop, we will review the basics of SDM using Wallace, demonstrate key application functions, highlight some new features, and show applications to conservation science through a brief case study. Participants will use their own laptops to run Wallace for a hands-on learning experience, and will emerge more confident SDM users. Those with prior experience are encouraged to bring their own datasets for analysis.


# Organizers
- Jamie M. Kass, Okinawa Institute of Science and Technology Graduate University
- Beth E. Gerstner, Michigan State University (gerstn11@msu.edu)
- Samuel Chang, Pace University 
- Bethany Johnson, City College of New York, CUNY
- Mary E. Blair, American Museum of Natural History

# Logistics
- Date: Sunday, July 17, 2022
- Time: 9:00 AM to 12:00 PM
- Place: Room Silver Baron 2,3 at the Silver Legacy Resort

# Workshop Schedule
- 9:00 – 9:15: Who we are, why are we here, and who you are
- 9:15 – 10:00: Introduction to species distribution modeling
- 10:00 – 10:30: Introduction to R and Wallace
- 10:30 – 10:45: Break / troubleshooting
- 10:45 – 11:15: Wallace v2 live demo and walkthrough
- 11:15 – 11:45: Using Wallace v2 with your own data
- 11:45 – 12:00: Preview of new v3 features for conservation


# Pre- and Post-Workshop Survey Links
Please take the pre- and post-workshop surveys. They really help us!!

- [Pre-workshop survey](https://docs.google.com/forms/d/e/1FAIpQLSfWHHjgWtrJJ-ThQ59_sd5MOjxh5Mxrh32kYTDXITDmgSuQAA/viewform)

# Background R Materials
*You do not need to know this information to effectively begin using Wallace. However, this will give you a better understanding of what Wallace is doing behind the scenes (and it may be helpful if you see a future in research!).*

- [Short introduction to R/RStudio](https://mlammens.github.io/SCCS-R-Wallace/docs/Intro-to-RStudio.html)
- [Even shorter introduction to R/RStudio](https://github.com/bgerstner90/SCCS_2021/blob/f8719086341de081676dd0cf3a77e9d4c18e53f9/Crash-Course-R.html)

# Installing R/RStudio and Wallace
*Please install R and Wallace prior to this Workshop. Downloading Wallace in R can take a while depending on your computer.*
1. Install R (version ≥ v.3.5.0) and Rstudio 

2. Install the ‘wallace’ package from CRAN (1.9.3-6)

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



