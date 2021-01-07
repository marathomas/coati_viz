# Coati viz tool

This is an interactive visualization tool for coati calls.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/marathomas/coati_viz/HEAD?urlpath=%2Fvoila%2Frender%2Fcoati_viz_tool.ipynb)



## About

It visualizes 4.278 coati calls. I used unsupervized UMAP (a neighborhood-based dimensionality reduction method) to embed the call spectrograms into 3D space. Similar calls should be close together in this space, dissimilar calls more distant. All these calls have also been categorized and labelled by human listeners. The color of the datapoints indicates what label group they belong to.


## How to use the tool

* Right-click on the "launch binder" badge right above this section and select "open in another tab" (else the tool will load in this window). 

* Wait until the app is built (this can take from a few seconds up to 5min if you're doing it for the first time), then initialize the tool by moving your mouse over the 3D plot. 

* When you hover over datapoints with your mouse, you'll be able to see some more details like the sex and status of the meerkat that gave the call and its name/identifier. You'll also see the label that researchers have given to this call. 
* In the lower left corner, you can see a spectrogram of the respective call. 
* Click on a datapoint to hear the sound.

* **It may happen that the tool is not working properly the first time you build it. Bear with me please and simply close the window and try loading it a second time. It's very likely that it will work now!**

## Troubleshooting

If the build takes too long (>5min) or functionalities in the tool are missing, close the window and please re-click the badge. Building the app a second time usually does the trick.



