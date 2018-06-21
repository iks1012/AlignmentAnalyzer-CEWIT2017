# Scoliosis Diagnosis-CEWIT2017

## Inspiration
An earlier project used video to capture an image and then take the height of an individual. If the computer could identify a point of measurement and various other points, we could use these points of reference to do something for us. We decided to use these points to tackle a health problem which we thought best fit spine alignment.

## What it does
Our project, Scoliosis Diagnosis, uses a pattern recognition technique to pinpoint key parts of an image. After figuring out the coordinates of these references, we create the simple regression. We use simple simple regression to figure out the slope of the spine in the image then cross compare that to the slope of a perfect spine. The difference would be displayed to test if you possibly had scoliosis.

## How we built it
We were able to build this project using Java and many Java libraries, mainly OpenCV. We used a stock image obtained through the camera feed and then had a final image that the user could select. The final image was used to detect similar images in the camera feed. The final images were found using a formula that was in the OpenCV library. Every time images were found, we stored it's coordinates and then used an apache library, simple regression, to analyze the data obtained. Then we created a GUI using swing.

## Challenges we ran into
One of the biggest challenges that we ran into was familiarizing ourselves with the the APIs/Libraries Java had to offer. We over came this by programming and researching together.

## Accomplishments that we're proud of
We are proud of completing a project that could have a large impact in technology. This could be used for many other things besides detecting for scoliosis in the future and could impact the way we use cameras.

## What we learned
We learned how to work with OpenCV and Java. In OpenCV we learned how to capture image on camera, process the image and analyze the display. In Java, we learned about swing and learned about various calculations that are possible using its libraries.

## What's next from us
There are a lot more applications this program can be applied to. This is a basic prototype but there are many real world applications that this program can tackle in the future. For example, we may use a different camera such as an infrared camera to find out information that would otherwise not be easily seen by humans. This technology is not limited to medical imaging as we could also use it for home security. For example, movement detection is possible for security systems.
