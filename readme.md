# QGIS Indonesian Coordinate Layout Formatter

This repository contains a custom QGIS Expression used in the QGIS Print Layout to format map grid coordinates into the standard Indonesian DMS (Degrees, Minutes, Seconds) format with dynamic **BT** (Bujur Timur), **LS** (Lintang Selatan), and **LU** (Lintang Utara) notations.

## Sample Result
7°30′00″ LS
120°03′00″ BT

## How to use
1. Open your QGIS Print Layout.
2. Select your Map item and go to the **Item Properties** panel.
3. Scroll down to the **Grids** section and add/modify a grid.
4. In the **Draw coordinates** section, change the format to **Custom**.
5. Click the **ε (Expression)** button.
6. Paste the code and click **OK**.
