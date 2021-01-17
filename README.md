# AI Satellite Tile Classifier Interface

This interface can be used to apply a self-made Convolutional Neural Network on satellite tiles systematically. This was used in a project to detect mountains, forests, lakes... shaped like penisses. But the interface is made so that any custom CNN can easily be used (inputs are now hard coded as 70x70x1 dimensions and a binary output).

## How to use

Simply download the repository and open the html file in your browser. All dependencies (Leaflet and TensorFlow) are included in the html file via CDN. When opening the HTML you are required to add a model that should be applied on each tile. The model used in the original YouTube video (detecting penis shapes) is added in the jsModel folder if you want to play with that. After choosing the other variables, you can initialize using the 'init' button and start the search by using the 'Next' button. The interface will scan all image tiles systematically and when they trigger the AI, the tile will be marked on the map and a link will be stored at the bottom of the page.

The countries.js file contains all borders of the world and is used to determine whether a tile will be over the ocean. These tiles do not need to be downloaded in order to save processing time and bandwidth.

If you like this project and foud this repository useful, consider buying me a coffee 💪.

<a href="https://www.buymeacoffee.com/programsam"  target="_blank"><img  src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png"  alt="Buy Me A Coffee" height=50 ></a>

## Watch the project on YouTube

[![AI Satellite Tile Classifier Interface](https://user-images.githubusercontent.com/75586344/104844821-a0422d00-58d2-11eb-9261-7fa27dc937f3.png)](https://youtu.be/9-y7u1Xkpa0 "AI Satellite Tile Classifier Interface")

## Screenshot

![Interface](https://user-images.githubusercontent.com/75586344/104844863-d4b5e900-58d2-11eb-97b0-d070b40aa423.png)
