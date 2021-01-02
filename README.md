# WhiteHouseAR

WhiteHouseAR is an augmented reality application developed as a project for the Computer Graphics course in 2019.

Apk file is avaliable on the following link: https://drive.google.com/file/d/1lUsutE-YNqyU9CvtrlbQSA3dA3ITURXo/view?usp=sharing

## Model
The model of the White House is designed in Blender. The most famous part of the White House - the Residence - was modeled. The original model also featured a garden around the White House, which was omitted in the application itself to simplify the model. 

## Application
Augmented reality application is developed using Unity3D. The application displays 3D content based on Image recognition. The Unity plugin Vuforia was used, as it supports most devices. Scripts for manipulating objects on the scene are written in C#.

Points of interest (POI) are designed in accordance with its content. For video POI is vintage TV, for audio it is a tuba and for interesting facts, it is a magnifier.

Resources for POIs
- Video: https://www.youtube.com/watch?v=BW6hxlThB_o
- Audio: https://www.youtube.com/watch?v=9AIAKVst7jw
- Text: https://www.thoughtco.com/surprising-facts-about-the-washington-dc-white-house-178508

## How to use the application?

To use the application your device must be one of the recommended devices as stated in this article: https://library.vuforia.com/platform-support/vuforia-engine-recommended-devices.html

After downloading and installing the application, on the first run you will need to allow the application to use your camera and storage.
You will see camera area with icons (as shown below) and you just need to scan the marker, the image you can find in the repository, to see the 3D model and points of interest.

<img src = "https://scontent.fsjj1-1.fna.fbcdn.net/v/t1.15752-9/135313515_206611311119927_1351212033707220294_n.jpg?_nc_cat=107&ccb=2&_nc_sid=ae9488&_nc_ohc=XDIa1w7g8SAAX_ucdgL&_nc_ht=scontent.fsjj1-1.fna&oh=e4c7c7d2eb0a82b1ae84c251fb2b1d6a&oe=6015F793" alt = "WhiteHouseAR">
