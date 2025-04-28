To run the Shiny app from GitHub, use the following code:
shiny::runGitHub("heatmap_shiny_Heatmaps", "DevGenBasel")

How to Use the Gene Expression Heatmap Generator
This app generates heatmaps from gene expression data. Here's a step-by-step guide:
1.	Upload Data:
o	Click "Upload Count Data (.csv or .xlsx)".
o	Select your gene expression data file. The app accepts both CSV and Excel formats.
2.	Select Gene Name Column:
o	Use the "Select Column Containing Gene Names" dropdown.
o	Choose the column in your data that contains the gene names (e.g., "gene_names_norm", "GeneID", etc.).
3.	Enter Gene List:
o	In the "Enter Gene List (one gene per line)" text box, type or paste the list of genes you want to include in the heatmap. Enter one gene name per line.
4.	Select Samples:
o	Use the "Initial Sample" dropdown to select the first sample you want to include in the heatmap.
o	To add more samples, click the "Add Sample" button. For each added sample, a new dropdown will appear where you can select the sample name.
5.	Clustering Options:
o	"Cluster Rows": Check this box to cluster the genes (rows) in the heatmap based on their expression patterns.
o	"Cluster Columns": Check this box to cluster the samples (columns) in the heatmap based on their gene expression profiles.
6.	Color Palette:
o	Use the "Color Palette" dropdown to select a color scheme for the heatmap. Available options include "RdBu", "viridis", "magma", "plasma", "inferno", and "Custom".
o	If you select "Custom", additional options will appear:
	"Color for <0": Enter the color you want to use for values below zero.
	"Color for 0": Enter the color you want to use for values equal to zero.
	"Color for >0": Enter the color you want to use for values above zero.
	You can use color names (e.g., "blue", "red", "green"), hex codes (e.g., "#0000FF"), or RGB values (e.g., "rgb(0,0,255)").
7.	Plot Size:
o	Use the "Plot Width (pixels)" and "Plot Height (pixels)" sliders to adjust the dimensions of the heatmap.
8.	Generate Heatmap:
o	Click the "Generate Heatmap" button to create the heatmap. The plot will appear in the main panel. Any error messages will be displayed below the plot.
9.	Download Heatmap:
o	Click the "Download Heatmap" button to save the heatmap as a PDF file.
