These two notebooks are tools for building datasets (leabra_datagen.ipynb) and demonstrating the network via webcam recording (leabra_demo_webcam.ipynb).
## leabra_datagen.ipynb
This notebook allows the user to provide commandline input  to choose if they are producing good or bad squat images and how many will be attempted at a time. It is intended to allow relatively rapid production of image data. It's results are used in the demo.
## leabra_demo_webcam.ipynb
This can be used to capture the bottom of a squat and pass it through the network. This was ultimately not used, due to issues with performance of the network related to images captured via open-cv in this way. A modified version was used to test the network on every frame of a squat, however the code was not put in the repository.
