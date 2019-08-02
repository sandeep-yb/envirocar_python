# envirocar_python
Analysis of envirocar data:

enviroCar is an open platform under 52 degrees North organisation,Germany for collecting and analyzing floating car data.The collected data consists of GPS position along with vehicles internal details.

AIM : To provide different possibilities to access, process and visualize enviroCar data.

Accessing data :

Requested data from enviro car API (https://envirocar.github.io/enviroCar-server/api/).

Libraries used for storing data : pandas and geo pandas.


Processing data:

Implemented the following advanced means of pre processing:

Map matching

Resampling of tracks

Detecting hotspots

Spatio-temporal aggregation

Congestion detection

Implemented basic algorithms to compute the following using trajectory data:

Number of stops in a track

Average stopping time in a track


Visualising data:

Tracks were visualized on a map as well as a heatmap.

Changes before and after resampling of tracks were visualized by plotting speed vs time graph.

 Libraries used : folium,matplotlib.

