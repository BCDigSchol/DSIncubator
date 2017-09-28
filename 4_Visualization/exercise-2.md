# **Exercise 2**

## **Create a map using Boston landmarks and neighborhoods data**

### Points

1. Login to the [Carto](https://carto.com/) dashboard:
   * Find "Your datasets" where you will upload new datasets.
   * Find "Your maps" where you will be able to see your published maps.

2. Download the [Boston_Neighborhoods](https://github.com/BCDigSchol/DSIncubator/blob/master/4_Visualizations/datasets/Boston_Neighborhoods.zip) and [Boston_Landmarks](https://docs.google.com/spreadsheets/d/e/2PACX-1vSDy2yIioREvlj6HXiTCKsBoIRTWSuT2iV1AZu_EvrrftPKhhbHCY2uh4uFWzz0nhMPUwvNknhIPvLZ/pubhtml) datasets.

3. In your Carto dashboard go to "datasets":
    * Select "new dataset" and upload the Boston Landmarks dataset (or connect via Google Drive).
    * You can view your table in Carto and make edits to the column headers here.
    * Select "create map" to generate a map based on this table.

4. Your map now has points!
   * Zoom in to Boston to see the points on your map.
   * You'll notice that your sidebar now has additional menu items:
     * Data, Analysis, Style, Pop-up, Legend
     * Within the "Style" section, you can adjust how your points are aggregated. This is where you can, for example, create a 
     torque map (interactive time-based map).
   * Notice that you can toggle between your data table and map view in the bottom right corner of your map.

Let's pause and look at our maps.


### Polygons

1. We will now add a data layer within our current map.

2. Select "add" and upload the Boston Neighborhoods dataset.

3. Your map now has polygons, but where did the points go?
    * Move your layer cards so that A (landmarks) is before B (neighborhoods).

Let's explore the data layers and the basemap options.


### Displaying & Styling Data

Within each layer card you will see options for "Data, Analysis, Style, Pop-up, and Legend.

1. Boston Landmarks layer:
    * Go to the "pop-up" section and identify the data that will display in a pop-up box.
    * Select the items you wish to have display in a pop-up box, re-order the items, and re-name the field names.
    * Select the "style" section and change your landmark points into an image icon.
    * Select the "legend" section and create a legend to identify what the icons represent.

2. Boston Neighborhoods layer:
    * Select the "style" section and select a color for your polygons.
      * You can choose one color or adjust the color for specific values, such as the neighborhood name.
      * When you have more than 10 values, you can assign specific colors for each value by adjusting the CSS.
    * Next, create labels identifying your neighborhood.

Let's take a look at our maps and discuss any questions. We can also look at the "Widgets" function to explore making our maps interactive.







