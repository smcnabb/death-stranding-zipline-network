## Death Stranding Zipline Network Tool

To view my zipline network [click here](http://smcnabb.github.io/death-stranding-zipline-network/).

### Notes

* You can hover over any of the dots to show a tooltip with extra info.
* Because it uses vector graphics you can use your browser zoom to get more detail or get it to fit on your screen.
* This tool only covers the Central Region.
* Some ziplines will show as connected when they're not in-game because of the terrain. That can't be helped without terrain data.
* It's easy to miss in-game but co-ordinates of structures are displayed at the top right of the map when you hover over them. You may have to look at a dark wall and zoom in or out to see them clearly.
* The in-game map of the Central Region goes from -3584, 3584 at the top left, to 3584, -3584 at the bottom right, with each unit representing 1 meter. So the map is 7168 meters by 7168 meters, though not all of it is playable area. The Weather Station is pretty close to being the center of the map.
* Free free to download or fork the code and make your own, or use the code to build your own tool.
* All you need to do is replace the data in the Javascript `ziplines` array at the top of index.html to make your own. So you only need some basic coding skills. The code figures out the distances between the ziplines and draws the lines automatically.
