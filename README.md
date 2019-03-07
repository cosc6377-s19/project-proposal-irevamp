### Video on the Internet

### Problem
With the cloud allowing for remote processing, many applications including video games could now be played remotely and have frames sent over the internet.  Surgeries could be performed remotely provided the surgeon has a real-time feed of the procedure. Trucks could also be driven by remote operators. All these applications would require a low latency video feed usually in the 10 to 100 ms range using special dedicated video processing chips. Cheap off the shelf cameras are usually measured in seconds. This project will setup a system to test the latency of a network camera through different network settings, and Wi-Fi vs wired networks.

### Solution 
The project will use a camera connected to a RaspberryPi and a remote display. The camera will create a raw data feed that will be processed by the Pi and will be sent over Internet to the display. The project will consider three main ways to send data over the Internet. First, each frame will be sent as an RGB feed, then each frame will be sent in a compressed format, and finally the last method will use multi frame compression. It is expected that each method will reduce bandwidth but will add delay due to extra end-to-end processing needed. The project will also consider how to efficiently send the video stream to multiple displays and compare the latency on a Wi-Fi network vs. a wired network. 
 
### Networking components

This project involves the following steps:

*	Setup raspberryPi and camera
*	Learn how to process raw data and packet it (will consider creating UDP packets)
*	Test Wi-Fi setup and wired setup
*	Create connection between camera and multiple devices for display
*	Communicate both ways by adding a simple application on the device to change camera pixels or number of frames (TCP packets), or even shut it off to save energy or reduce bandwidth

### Milestones
* End of March: First 3 steps above
* End of April: Next 2 steps, plus packet analysis and statistics and writeup.
