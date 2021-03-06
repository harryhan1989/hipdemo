# HIPie: HIP Insights Explorer
This is an *interactive* visualization of the plots in the paper: the endo-exo map, observed and fitted popularity series and video metadata.
It has additional visualizations of TED videos and VEVO musicians.
Furthermore, it allows users to add and compare their own videos.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=x5xIf4vUScI
" target="_blank"><img src="https://github.com/computationalmedia/hipdemo/blob/master/screenshot.jpeg" 
alt="x5xIf4vUScI" width="480" height="320" border="10" /></a>

# Citation
The project was introduced in this [paper](https://arxiv.org/pdf/1801.04117.pdf):
```
KONG, Q., RIZOIU, M.-A., WU, S., AND XIE, L. 2018. Will this video go viral? Explaining and predicting the popularity of youtube videos. (p. 1)
```

# How to run HIPie?
A public available version of HIPie is hosted at http://www.hipdmeo.ml. If one wants to run a local version, please follow these steps:
1. Clone the repo
2. Fill in the Google developer key in file: scripts/youtube_crawler.py
3. Install required R packages by running requiredPackages.R
4. Open the project in Rstudio and it will be detected as a Shiny project
5. Click Run in Rstudio and the project will start running

# License
Both dataset and code are distributed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license, a copy of which can be obtained following this link. If you require a different license, please contact us at Marian-Andrei@rizoiu.eu or Lexing.Xie@anu.edu.au.
