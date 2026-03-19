🌍 World Map Country Highlights

This repository contains a Python script to create a world map and highlight selected countries.

📌 Overview

This project allows you to:

Generate a world map using shapefiles

Highlight specific countries of interest

Display country names clearly on the map

🛠️ Requirements

Before running the script, make sure you have:

Python installed

Required Python libraries:

geopandas

matplotlib

adjustText

You can install the required packages using:

pip install geopandas matplotlib adjustText
📂 How to Use
1. Select Countries to Highlight

Open the script file and update the list of countries (around line 5) with the names of the countries you want to highlight.

⚠️ Make sure to use standard country names as recognized in the shapefile.

2. Set the Shapefile Path

Locate the section labeled:

# Load shapefile

Update the file path (around line 20) to point to the location of your shapefile on your system.

Example:

world = gpd.read_file(r"E:/your-folder/ne_110m_admin_0_countries.shp")
3. Run the Script

Open Command Prompt (CMD)

Navigate to the folder containing your script:

cd path\to\your\folder

Run the script using:

python Basmati_export_countryNAMES_highlight.py
📌 Important Note

If your file is saved as:

Basmati_export_countryNAMES_highlight.py.txt

Rename it to:

Basmati_export_countryNAMES_highlight.py

Then run the script as shown above.

📊 Output

The script will generate a world map image where:

Selected countries are highlighted

Country names are labeled clearly

The map is saved as an image file

✅ Summary

Update country list

Set correct shapefile path

Run the script via CMD

Get your highlighted world map


