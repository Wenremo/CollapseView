# CollapseView - Computer Vision
Building damage classifier for coordinating intervention teams to damaged areas in real time. 

Trained a CNN (convolutional neural network) in TensorFlow to recognize houses from satellite imagery. The aim was to re-run the model on an image post-earthquake for identifying collapsed units. 97%+ accuracy.

Core idea: Collapsed building classifier. Extendable to damage intensity classifier. 

1) Get a dataset - intact and collapsed/damaged buildngs - orthogonal view / eagle eye view. 
2) Transform data - invariance - split, scale, contrast, rotate, colour change. 
3) Use IBM's image recognition model via API - using generated account key (Currently replaced with a CNN based method trained from scratch)
4) Train it on building data that was sourced. Can detect multiple buildings

TO DO:
5) Assess model's accuracy and improve. 
6) Visualise output on google maps in a flask web server. 
