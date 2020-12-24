## Auto Drawer
Auto Drawer is a simple freehand drawing tool using mouse automation.
From a source image, it draws a [binary image](https://en.wikipedia.org/wiki/Binary_image)
in applications that allow freehand mouse drawing (ex. Microsoft Paint or [Roll20](https://roll20.net/)).

<p align="center">
  <img src="/assets/examples/Github.gif" width="200"></img>
</p>


## Motivation
Online gaming services, like Roll20, often allow users to freehand draw onto maps 
for other players to see. I wanted a way to make decent drawings without requiring
a drawing tablet and artistic skill. 

## Features

| <img src="/assets/source/github.png" height="100"></img> | <img src="/assets/examples/Resolution.png" height="100"></img> | <img src="/assets/examples/Scales.png" height="100"></img> | <img src="/assets/examples/GithubCrop.gif" height="100"></img> |
| :---: | :---: | :---: | :---: |
| *Source* | *Resolution* | *Size* | *Speed* |

## Examples

#### Works with photographs

| <img src="/assets/source/face.jpg" height="200"></img> | <img src="/assets/examples/FaceDrawn.png" height="200"></img> | <img src="/assets/examples/FaceDrawnHighRes" height="200"></img> |
| :---: | :---: | :---: |
| *Source* | *Low Resolution* | *High Resolution* |

#### Works with color images

| <img src="/assets/source/GreatWave.jpg" height="200"></img> | <img src="/assets/examples/GreatWaveDran.png" height="200"></img> | 
| :---: | :---: |
| *Source* | *Output* | 

## Built using
- [Pillow (PIL Fork)](https://pillow.readthedocs.io/en/stable/#) for image processing
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) for mouse automation
- [NumPy](https://numpy.org/) to organize image data array

