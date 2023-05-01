# DENSITY-BASED-TRAFFIC-TIME-ALLOCATION

The main idea of our project of allocating the traffic lights according to the density of the vehicles is raised by the series of issues of the growing population and the trouble caused by it. Thus, there is a need for adaptive traffic signals which can do real-time monitoring to control traffic light signals based on traffic density. The density of traffic in the images at each junction is compared. Results show that more time is allocated for the vehicles on the densest road to pass compared to other less dense roads.

We perform image processing on captured images and object detection on all those images that we have taken.
Based on the vehicle count obtained from each lane by object counting , we allocate time accordingly.
We have considered the ratio method from simple math to allocate green signal timing, 
followed by a small algorithm for red signal as well.

And then comes the last module where led controlling is done based on time allocated for each lane using GPIO pins.
