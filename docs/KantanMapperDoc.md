#Touch Designer
## Projection mapping using Kantan mapper




###Setting up:
* Movie-In top OP 
	- connect to the video you want to map
	- Don't go beyond a resolution of 1280 x 1280
* Null Top OP - acts as the output


Connect your laptop to the projector and make sure you set it as an 'Extended Display' and that it is not mirroring to your screen. 


### Kantan Mapper:

* In the panel section on the kantan mapper op, turn off `Display`
* Pulse the kantan mapper window from the kantan section.

	![Kantan editor window](/Users/dhivyabharathichellakumar/Desktop/kantanMapper.png)
* In the newly opened window, click on window options

	![window options window](/Users/dhivyabharathichellakumar/Desktop/kantan2.png)
* Do the following:
	- Set `monitor` as 1, here 1 denotes the projector
	- Set `Opening size` as fill
	- Turn off `borders`
	- Turn on `always on top`
	- For testing purporses, you could click on `open as a seperate window`

Now you should have the new window up in the projector and it should let you mark shapes using the kantan mapper window

Now you can map using quadrilaterals or free form shapes.


### How to add the video

* With the kantan mapper edit window open, drag and drop the texture/video on to the shape drawn.

### Output
* Connect the kantan mapper to a NULL top this will act as the output instead of the kantan mapper op directly. Name this component as ' *bg* '
* Now zoom out, you should see two components
* Click on the project1 components and go to the `look` category, under this change the `Background TOP` category from *./out* to *./bg*

![zoomed out window](/Users/dhivyabharathichellakumar/Desktop/projectWin.png)

* Click on the perform component and under the `window` category, go to the `monitor` category and set it to *1* (denoting the projector display')
* Finally click on the Perform icon, Picture looking icon at the top left of the window. This should open the projection mapping on the projector.

