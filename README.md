# Coati viz tool

This is an interactive visualization tool for coati calls.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/marathomas/coati_viz/HEAD?urlpath=%2Fvoila%2Frender%2Fcoati_viz_tool.ipynb)



## About

It visualizes 2.033 coati calls. I used unsupervized UMAP (a neighborhood-based dimensionality reduction method) to embed the call spectrograms into 3D space. Similar calls should be close together in this space, dissimilar calls more distant. All these calls have also been categorized and labelled by human listeners. The color of the datapoints indicates what label group they belong to.

<p align="center">
  <img src="/other_imgs/coati_pic_small.jpg" width="260" height="200" />
</p>


## How to use the tool

<p align="center">
  <img src="/other_imgs/tool_view.png" width="550" height="260" />
</p>


* Right-click on the "launch binder" badge right above this section and select "open in another tab" (else the tool will load in this window). 

* Wait until the app is built (this can take from a few seconds up to 5min if you're doing it for the first time), then initialize the tool by moving your mouse over the 3D plot. 

* When you hover over datapoints with your mouse, you'll be able to see some more details like ID of the coati that gave the call. You'll also see the label that researchers have given to this call. 
* In the lower left corner, you can see a spectrogram of the respective call. 
* Click on a datapoint to hear the sound.
* Click on call groups in the legend to let them disappear/appear
* If you remain inactive for a longer period of time (10min or so?), the tool won't be reactive anymore, so you need to reload it.

## Troubleshooting

If the build takes too long (>5min) or functionalities in the tool are missing, close the window and please re-click the badge. Building the app a second time usually does the trick.

## Data accessibility

This data is part of an ongoing study and is protected by copyright law, meaning that no one may reproduce, distribute, or create derivative works from it. If you want to use data or code, please get in touch with me.



