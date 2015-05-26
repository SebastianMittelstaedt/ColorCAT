# ColorCAT

**Color**maps for **C**ombined **A**nalysis **T**asks. 

This tool helps you to design colormaps for your data visualization. Please take a look into the video, it already explains many functions and how to use the tool.

## Pre-release info

This is a pre-release. I will provide the first release of ColorCat_1.0 very soon (approx. 05.06.2015), including a complete manual and a video matching the version. 

## Quick-Start

1. If you haven't already, please download and install Java: https://java.com/de/download/
2. Download ColorCAT by either cloning the repository, downloading the zip file (right side of this page), or click here on the file and then get the "raw" file on the following page.
3. You should be able to start ColorCAT with the `*.jar` otherwise open the command prompt and type: `java -jar ColorCAT_0.9.jar`.
4. If ColorCAT starts, you can start designing your colormap.

## General Workflow
(Please refer to the video, especially for the interactive parts.)

1. Decide which of the elementary analysis task you want to perform
	* *Localization*: In this task, you have certain data values in your mind that you want to find in the display. The colormap will then **highlight** data values in the visualization, while you control which data values should be highlighted by the *interactive splines*.
	* *Identification*: In this task, you look at single color encoded data values and you want to **read the metric quantities** (also categories) from the display according to the color legend.
	* *Comparison*: In this task, you look at two or more color encoded objects and you want to **perceive their absolute or relative differences** (or perceive natural forms and shapes).
2. Select whether your data is sequential (this comprises continuous, categorical, and ordinal data) or diverging (only for continuous and ordinal data).
3. If you want, you can design your own colormap by using the colorpicker tool. ColorCAT will take care that the colormap that you design matches the analysis task. You can add knots (click in the color area), remove knots (click on knots), or rotate knots (dragging the mouse in circular fashion).
4. If you are satisfied, you can export the colormap by clicking on "Save to File". You can select the output format and the file for the export.








