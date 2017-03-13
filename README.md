# Gazebo Models Repository

This repository is for storing all the models that we might find useful when using Gazebo as a simulator

## Opening files in Blender

`blender filename.blend`

## Exporting Collada File
Open the file in Blender then:

`File->Export->Collada`

The Collada file will be saved in the same directory as the .blend file

## Opening the Model in Gazebo

Create a copy of the sample.world file in the root of the directory, for example copying it int other buoy directory

`cp sample.world buoy/`

edit the <uri> tag so that the file points to the collada (.dae) file
