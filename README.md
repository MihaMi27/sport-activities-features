<p align="center">
  <img width="200" src="https://raw.githubusercontent.com/firefly-cpp/sport-activities-features/main/.github/logo/sport_activities.png">
</p>

<h1 align="center">
sport-activities-features --- A minimalistic toolbox for extracting features from sports activity files written in Python
</h1>

<p align="center">
  <img alt="PyPI Version" src="https://img.shields.io/pypi/v/sport-activities-features.svg" href="https://pypi.python.org/pypi/sport-activities-features">
  <img alt="PyPI - Python Version" src="https://img.shields.io/pypi/pyversions/sport-activities-features.svg">
  <img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dm/sport-activities-features.svg">
  <img alt="Fedora package" src="https://img.shields.io/fedora/v/python3-sport-activities-features?color=blue&label=Fedora%20Linux&logo=fedora" href="https://src.fedoraproject.org/rpms/python-sport-activities-features">
  <img alt="AUR package" src="https://img.shields.io/aur/version/python-sport-activities-features?color=blue&label=Arch%20Linux&logo=arch-linux" href="https://aur.archlinux.org/packages/python-sport-activities-features">
  <img alt="Packaging status" src="https://repology.org/badge/tiny-repos/python:sport-activities-features.svg" href="https://repology.org/project/python:sport-activities-features/versions">
  <img alt="Downloads" src="https://pepy.tech/badge/sport-activities-features" href="https://pepy.tech/project/sport-activities-features">
  <img alt="GitHub license" src="https://img.shields.io/github/license/firefly-cpp/sport-activities-features.svg" href="https://github.com/firefly-cpp/sport-activities-features/blob/master/LICENSE">
  <img alt="Documentation Status" src="https://readthedocs.org/projects/sport-activities-features/badge/?version=latest" href="https://sport-activities-features.readthedocs.io/en/latest/?badge=latest">
</p>

<p align="center">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/firefly-cpp/sport-activities-features">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/w/firefly-cpp/sport-activities-features.svg">
  <img alt="Average time to resolve an issue" src="http://isitmaintained.com/badge/resolution/firefly-cpp/sport-activities-features.svg" href="http://isitmaintained.com/project/firefly-cpp/sport-activities-features">
  <img alt="Percentage of issues still open" src="http://isitmaintained.com/badge/open/firefly-cpp/sport-activities-features.svg" href="http://isitmaintained.com/project/firefly-cpp/sport-activities-features">
  <img alt="All Contributors" src="https://img.shields.io/badge/all_contributors-6-orange.svg" href="#-contributors">
</p>

<p align="center">
  <img alt="DOI" src="https://img.shields.io/badge/DOI-10.1109/INES52918.2021.9512927-blue" href="https://doi.org/10.1109/INES52918.2021.9512927">
</p>

<p align="center">
  <a href="#-detailed-insights">🔍 Detailed insights</a> •
  <a href="#-installation">📦 Installation</a> •
  <a href="#-api">📮 API</a> •
  <a href="#-graphical-user-interface">💻 Graphical User Interface</a> •
  <a href="#️-historical-weather-data">🌦️ Historical weather data</a> •
  <a href="#-overpass-api-open-elevation-api--opentopodata-integration">🧩 Overpass API, Open Elevation API & OpenTopoData integration</a>
  <a href="#-examples">🚀 Examples</a> •
  <a href="#-license">🔑 License</a> •
  <a href="#-cite-us">📄 Cite us</a> •
  <a href="#-further-read">📖 Further read</a> •
  <a href="#-related-frameworks">🔗 Related frameworks</a> •
  <a href="#-contributors">🫂 Contributors</a>
</p>

## Unleashing the Power of Sports Activity Analysis: A Framework Beyond Ordinary Metrics 🚀

Prepare to dive into the thrilling world of sports activity analysis, where hidden geographic, topological, and personalized data await their grand unveiling. In this captivating journey, we embark on a quest to extract the deepest insights from the wealth of information generated by monitoring sports activities. Brace yourself for a framework that transcends the limitations of conventional analysis techniques. 💪🔍

Traditional approaches often rely on integral metrics like total duration, total distance, and average heart rate, but they fall victim to the dreaded "overall metrics problem." These metrics fail to capture the essence of sports activities, omitting crucial components and leading to potentially flawed and misleading conclusions. They lack the ability to recognize distinct stages and phases of the activity, such as the invigorating warm-up, the endurance-testing main event, and the heart-pounding intervals. ⏱️🚴‍♀️📈

Fortunately, our sport-activities-framework rises above these limitations, revealing a comprehensive panorama of your sports activity files. This framework combines the power of identification and extraction methods to unlock a treasure trove of valuable data. Picture this :camera: : effortlessly identifying the number of hills, extracting average altitudes of these remarkable formations, measuring the total distance conquered on those inclines, and even deriving climbing ratios for a true measure of accomplishment (total distance of hills vs. total distance). But that's just the tip of the iceberg! The framework seamlessly integrates a multitude of extensions, including historical weather parsing, statistical evaluations, and ex-post visualizations that bring your data to life. 🗻📊🌦️

For those seeking to venture further, we invite you to explore the realms of scientific papers on data mining that delve into these captivating topics. Discover how our framework complements the world of generating and predicting automated sport training sessions, creating a harmonious synergy between theory and practice. 📚🔬💡

* **Free software:** MIT license
* **Python versions:** 3.8.x, 3.9.x, 3.10.x, 3.11.x, 3.12.x
* **Documentation:** https://sport-activities-features.readthedocs.io/en/latest
* **Tested OS:** Windows, Ubuntu, Debian, Fedora, Alpine, Arch, macOS. **However, that does not mean it does not work on others.**

## 🔍 Detailed insights

Prepare to be astounded by the capabilities of the sport-activities-features framework. It effortlessly handles TCX & GPX activity files and harnesses the power of the [Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API) nodes. Presenting the range of functions at your disposal:

- **Unleash the integral metrics**: From total distance to total duration and even calorie count, witness the extraction of these vital statistics with a single glance. 📏⏰🔥 ([See example](examples/integral_metrics_extraction.py))

- **Conquer the peaks**: Ascend to new heights by extracting topographic features like the number of hills, their average altitudes, the total distance covered on these majestic slopes, and the thrilling climbing ratio. Prepare for a breathtaking adventure! ⛰️📈🧗‍♂️ ([See example](examples/hill_data_extraction.py))

- **Embark on a visual journey**: Immerse yourself in the beauty of your accomplishments as you plot the identified hills on a mesmerizing map. Witness the landscape come alive before your eyes. 🗺️🏞️🖌️ ([See example](examples/draw_map_with_identified_hills.py))

- **Embrace the rhythm of intervals**: Explore the intervals within your sports activities, uncovering their numbers, durations, distances, and heart rates. Unveil the heartbeat of your performance! 🏃‍♀️📊💓 ([See example](examples/draw_map_with_identified_intervals.py))

- **Calculate the training loads**: Dive deep into the intricate world of training loads and discover the Banister TRIMP and Lucia TRIMP methods. Gain invaluable insights into optimizing your training regimen. 📈⚖️🏋️‍♂️ ([See example](examples/calculate_training_load.py))

- **Weather the storm**: Unlock the power of historical weather data from external services, adding a fascinating layer of context to your sports activities. ☀️🌧️⛈️

- **Unveil the secrets within coordinates**: Explore the integral metrics of your activities within specific geographical areas, uncovering valuable data on distance, heart rate, and speed. Peer into the depths of your performance! 🌍📍📉 ([See example](examples/extract_data_inside_area.py))

- **Embrace randomness**: Extract activities from CSV files and indulge in the excitement of randomly selecting a specific number of activities. Embrace the element of surprise! 🎲📂🎉 ([See example](examples/extract_random_activities_from_csv.py))

- **Conquer the dead ends**: Unravel the mysteries of your sports activities by identifying the dead ends. Prepare to navigate the uncharted territories of your performance! 🚧🗺️🔍 ([See example](examples/dead_end_extraction.py))

- **Unlock the format**: Seamlessly convert TCX files to GPX, opening doors to even more possibilities. Adapt and conquer! ⚙️🔄✨ ([See example](examples/convert_tcx_to_gpx.py))

And that's just the beginning! The sport-activities-framework holds countless other features, awaiting your exploration. Brace yourself for an exhilarating journey of discovery, where the ordinary becomes extraordinary, and your sports activities come alive like never before. 🌟🔥🏃‍♂️

The framework comes with two (testing) [benchmark datasets](https://github.com/firefly-cpp/sports-activity-dataset-collections), which are freely available to download from: [DATASET1](http://iztok-jr-fister.eu/static/publications/Sport5.zip), [DATASET2](http://iztok-jr-fister.eu/static/css/datasets/Sport.zip).


## 📦 Installation

### pip

Install sport-activities-features with pip:

```sh
pip install sport-activities-features
```

### Alpine Linux

To install sport-activities-features on Alpine, use:

```sh
$ apk add py3-sport-activities-features
```

### Fedora Linux

To install sport-activities-features on Fedora, use:

```sh
$ dnf install python3-sport-activities-features
```

### Arch Linux

To install sport-activities-features on Arch Linux, please use an [AUR helper](https://wiki.archlinux.org/title/AUR_helpers):

```sh
$ yay -Syyu python-sport-activities-features
```

## 📮 API

There is a simple API for remote work with the sport-activities-features package available [here](https://github.com/alenrajsp/sport-activities-features-api).

## 💻 Graphical User Interface

There is a simple Graphical User Interface for the sport-activities-features package available [here](https://github.com/firefly-cpp/sport-activities-features-gui).

## 🌦️ Historical weather data
Weather data parsed is collected from the [Visual Crossing Weather API](https://www.visualcrossing.com/).
Please note that this is an external unaffiliated service, and users must register to use the API.
The service has a free tier (1000 Weather reports/day) but is otherwise operating on a pay-as-you-go model.
For pricing and terms of use, please read the [official documentation](https://www.visualcrossing.com/weather-data-editions) of the API provider.

## 🧩 Overpass API, Open Elevation API & OpenTopoData integration
Without performing activities, we can use the [OpenStreetMap](https://www.openstreetmap.org/) for the identification of hills,
total ascent, and descent. This is done using the [Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API)
which is a read-only API that allows querying of OSM map data. In addition to that altitude, data is retrieved by using the
[Open-Elevation API](https://open-elevation.com/) or [OpenTopoData API](https://www.opentopodata.org/)  which are open-source and free alternatives to the Google Elevation API.
Both of the solutions can be used by using free publicly acessible APIs ([Overpass](https://wiki.openstreetmap.org/wiki/Overpass_API), [Open-Elevation](https://open-elevation.com/#public-api), [OpenTopoData](https://www.opentopodata.org/#public-api)) or can be self hosted on a server or as a Docker container ([Overpass](https://wiki.openstreetmap.org/wiki/Overpass_API/Installation), [Open-Elevation](https://github.com/Jorl17/open-elevation/blob/master/docs/host-your-own.md), [OpenTopoData](https://www.opentopodata.org/server/)).

## 🚀 Examples

### Reading files

#### (*.TCX)
```python
from sport_activities_features.tcx_manipulation import TCXFile

# Class for reading TCX files
tcx_file=TCXFile()
tcx_exercise = tcx_file.read_one_file("path_to_the_file")
data = tcx_file.extract_activity_data(tcx_exercise) # Represents data as dictionary of lists

# Alternative choice
data = tcx_file.extract_activity_data(tcx_exercise, numpy_array= True) # Represents data as dictionary of numpy.arrays

```

#### (*.GPX)
```python
from sport_activities_features.gpx_manipulation import GPXFile

# Class for reading GPX files
gpx_file=GPXFile()

# Read the file and generate a dictionary with 
gpx_exercise = gpx_file.read_one_file("path_to_the_file")
data = gpx_file.extract_activity_data(gpx_exercise) # Represents data as dictionary of lists

# Alternative choice
data = gpx_file.extract_activity_data(gpx_exercise, numpy_array= True) # Represents data as dictionary of numpy.arrays

```

### Extraction of topographic features
```python
from sport_activities_features.hill_identification import HillIdentification
from sport_activities_features.tcx_manipulation import TCXFile
from sport_activities_features.topographic_features import TopographicFeatures
from sport_activities_features.plot_data import PlotData

# Read TCX file
tcx_file = TCXFile()
tcx_exercise = tcx_file.read_one_file("path_to_the_file")
activity = tcx_file.extract_activity_data(tcx_exercise)

# Detect hills in data
Hill = HillIdentification(activity['altitudes'], 30)
Hill.identify_hills()
all_hills = Hill.return_hills()

# Extract features from data
Top = TopographicFeatures(all_hills)
num_hills = Top.num_of_hills()
avg_altitude = Top.avg_altitude_of_hills(activity['altitudes'])
avg_ascent = Top.avg_ascent_of_hills(activity['altitudes'])
distance_hills = Top.distance_of_hills(activity['positions'])
hills_share = Top.share_of_hills(distance_hills, activity['total_distance'])
```

### Extraction of intervals
```python
import sys
sys.path.append('../')

from sport_activities_features.interval_identification import IntervalIdentificationByPower, IntervalIdentificationByHeartrate
from sport_activities_features.tcx_manipulation import TCXFile

# Reading the TCX file
tcx_file = TCXFile()
tcx_exercise = tcx_file.read_one_file("path_to_the_file")
activity = tcx_file.extract_activity_data(tcx_exercise)

# Identifying the intervals in the activity by power
Intervals = IntervalIdentificationByPower(activity["distances"], activity["timestamps"], activity["altitudes"], 70)
Intervals.identify_intervals()
all_intervals = Intervals.return_intervals()

# Identifying the intervals in the activity by heart rate
Intervals = IntervalIdentificationByHeartrate(activity["timestamps"], activity["altitudes"], activity["heartrates"])
Intervals.identify_intervals()
all_intervals = Intervals.return_intervals()
```

### Parsing of Historical weather data from an external service
```python
from sport_activities_features import WeatherIdentification
from sport_activities_features import TCXFile

# Read TCX file
tcx_file = TCXFile()
tcx_exercise = tcx_file.read_one_file("path_to_the_file")
tcx_data = tcx_file.extract_activity_data(tcx_exercise)

# Configure visual crossing api key
visual_crossing_api_key = "weather_api_key" # https://www.visualcrossing.com/weather-api

# Explanation of elements - https://www.visualcrossing.com/resources/documentation/weather-data/weather-data-documentation/
weather = WeatherIdentification(tcx_data['positions'], tcx_data['timestamps'], visual_crossing_api_key)
weatherlist = weather.get_weather(time_delta=30)
tcx_weather = weather.get_average_weather_data(timestamps=tcx_data['timestamps'],weather=weatherlist)
# Add weather to TCX data
tcx_data.update({'weather':tcx_weather})
```

The weather list is of the following type:
```json
     [
        {
            "temperature": 14.3,
            "maximum_temperature": 14.3,
            "minimum_temperature": 14.3,
            "wind_chill": null,
            "heat_index": null,
            "solar_radiation": null,
            "precipitation": 0.0,
            "sea_level_pressure": 1021.6,
            "snow_depth": null,
            "wind_speed": 6.9,
            "wind_direction": 129.0,
            "wind_gust": null,
            "visibility": 40.0,
            "cloud_cover": 54.3,
            "relative_humidity": 47.6,
            "dew_point": 3.3,
            "weather_type": "",
            "conditions": "Partially cloudy",
            "date": "2016-04-02T17:26:09+00:00",
            "location": [
                46.079871179535985,
                14.738618675619364
            ],
            "index": 0
        }, ...
    ]
```

### Extraction of integral metrics
```python
import sys
sys.path.append('../')

from sport_activities_features.tcx_manipulation import TCXFile

# Read TCX file
tcx_file = TCXFile()
tcx_exercise = tcx_file.read_one_file("path_to_the_file")
integral_metrics = tcx_file.extract_integral_metrics(tcx_exercise)

print(integral_metrics)

```

### Weather data extraction
```python
from sport_activities_features.weather_identification import WeatherIdentification
from sport_activities_features.tcx_manipulation import TCXFile

#read TCX file
tcx_file = TCXFile()
tcx_exercise = tcx_file.read_one_file("path_to_the_file")
tcx_data = tcx_file.extract_activity_data(tcx_exercise)


#configure visual crossing api key
visual_crossing_api_key = "API_KEY" # https://www.visualcrossing.com/weather-api

#return weather objects
weather = WeatherIdentification(tcx_data['positions'], tcx_data['timestamps'], visual_crossing_api_key)
weatherlist = weather.get_weather()
```

### Using Overpass queried Open Street Map nodes
```python
import overpy
from sport_activities_features.overpy_node_manipulation import OverpyNodesReader

# External service Overpass API (https://wiki.openstreetmap.org/wiki/Overpass_API) (can be self-hosted)
overpass_api = "https://lz4.overpass-api.de/api/interpreter"

# External service Open Elevation API (https://api.open-elevation.com/api/v1/lookup) (can be self-hosted)
open_elevation_api = "https://api.open-elevation.com/api/v1/lookup"

# OSM Way (https://wiki.openstreetmap.org/wiki/Way)
open_street_map_way = 164477980

overpass_api = overpy.Overpass(url=overpass_api)

# Get an example Overpass way
q = f"""(way({open_street_map_way});<;);out geom;"""
query = overpass_api.query(q)

# Get nodes of an Overpass way
nodes = query.ways[0].get_nodes(resolve_missing=True)

# Extract basic data from nodes (you can, later on, use Hill Identification and Hill Data Extraction on them)
overpy_reader = OverpyNodesReader(open_elevation_api=open_elevation_api)
# Returns {
#         'positions': positions, 'altitudes': altitudes, 'distances': distances, 'total_distance': total_distance
#         }
data = overpy_reader.read_nodes(nodes)
```

### Extraction of data inside the area
```python
import numpy as np
import sys
sys.path.append('../')

from sport_activities_features.area_identification import AreaIdentification
from sport_activities_features.tcx_manipulation import TCXFile

# Reading the TCX file.
tcx_file = TCXFile()
tcx_exercise = tcx_file.read_one_file("path_to_the_file")
activity = tcx_file.extract_activity_data(tcx_exercise)

# Converting the read data to arrays.
positions = np.array([*activity['positions']])
distances = np.array([*activity['distances']])
timestamps = np.array([*activity['timestamps']])
heartrates = np.array([*activity['heartrates']])

# Area coordinates should be given in clockwise orientation in the form of 3D array (number_of_hulls, hull_coordinates, 2).
# Holes in area are permitted.
area_coordinates = np.array([[[10, 10], [10, 50], [50, 50], [50, 10]],
                             [[19, 19], [19, 21], [21, 21], [21, 19]]])

# Extracting the data inside the given area.
area = AreaIdentification(positions, distances, timestamps, heartrates, area_coordinates)
area.identify_points_in_area()
area_data = area.extract_data_in_area()
```

### Identify interruptions
```python
from sport_activities_features.interruptions.interruption_processor import InterruptionProcessor
from sport_activities_features.tcx_manipulation import TCXFile

"""
Identify interruption events from a TCX or GPX file.
"""

# read TCX file (also works with GPX files)
tcx_file = TCXFile()
tcx_exercise = tcx_file.read_one_file("path_to_the_file")
tcx_data = tcx_file.extract_activity_data(tcx_exercise)

"""
Time interval = time before and after the start of an event
Min speed = Threshold speed to trigger an event/interruption (trigger when under min_speed)
overpass_api_url = Set to something self-hosted, or use a public instance from https://wiki.openstreetmap.org/wiki/Overpass_API
"""
interruptionProcessor = InterruptionProcessor(time_interval=60, min_speed=2,
                                              overpass_api_url="url_to_overpass_api")

"""
If classify is set to true, also discover if interruptions are close to intersections. Returns a list of [ExerciseEvent]
"""
events = interruptionProcessor.events(tcx_data, True)
```

### Overpy (Overpass API) node manipulation
Generate TCXFile parsed like data object from overpy.Node objects
```python
import overpy
from sport_activities_features.overpy_node_manipulation import OverpyNodesReader

# External service Overpass API (https://wiki.openstreetmap.org/wiki/Overpass_API) (can be self-hosted)
overpass_api = "https://lz4.overpass-api.de/api/interpreter"

# External service Open Elevation API (https://api.open-elevation.com/api/v1/lookup) (can be self-hosted)
open_elevation_api = "https://api.open-elevation.com/api/v1/lookup"

# OSM Way (https://wiki.openstreetmap.org/wiki/Way)
open_street_map_way = 164477980

overpass_api = overpy.Overpass(url=overpass_api)

# Get an example Overpass way
q = f"""(way({open_street_map_way});<;);out geom;"""
query = overpass_api.query(q)

# Get nodes of an Overpass way
nodes = query.ways[0].get_nodes(resolve_missing=True)

# Extract basic data from nodes (you can, later on, use Hill Identification and Hill Data Extraction on them)
overpy_reader = OverpyNodesReader(open_elevation_api=open_elevation_api)
# Returns {
#         'positions': positions, 'altitudes': altitudes, 'distances': distances, 'total_distance': total_distance
#         }
data = overpy_reader.read_nodes(nodes)
```
### Missing elevation data extraction
```python
from sport_activities_features import ElevationIdentification
from sport_activities_features import TCXFile

tcx_file = TCXFile()
tcx_exercise = tcx_file.read_one_file("path_to_the_file")
tcx_data = tcx_file.extract_activity_data(tcx_exercise)

elevations = ElevationIdentification(tcx_data['positions'])
"""Adds tcx_data['elevation'] = eg. [124, 21, 412] for each position"""
tcx_data.update({'elevations':elevations})
```

### Example of a visualization of the area detection

![Area Figure](https://i.imgur.com/Iz8Ga3B.png)

### Example of visualization of dead-end identification
![Dead End Figure](https://imgur.com/LgZzCFS.png)

## 🔑 License

This package is distributed under the MIT License. This license can be found online at <http://www.opensource.org/licenses/MIT>.

## Disclaimer

This framework is provided as-is, and there are no guarantees that it fits your purposes or that it is bug-free. Use it at your own risk!

## 📄 Cite us

I. Jr. Fister, L. Lukač, A. Rajšp, I. Fister, L. Pečnik and D. Fister, "[A minimalistic toolbox for extracting features from sport activity files](http://iztok-jr-fister.eu/static/publications/294.pdf)", 2021 IEEE 25th International Conference on Intelligent Engineering Systems (INES), 2021, pp. 121-126, doi: [10.1109/INES52918.2021.9512927](http://dx.doi.org/10.1109/INES52918.2021.9512927).

## 📖 Further read

[1] [Awesome Computational Intelligence in Sports](https://github.com/firefly-cpp/awesome-computational-intelligence-in-sports)

## 🔗 Related frameworks

[1] [AST-Monitor: A wearable Raspberry Pi computer for cyclists](https://github.com/firefly-cpp/AST-Monitor)

[2] [TCXReader.jl: Julia package designed for parsing TCX files](https://github.com/firefly-cpp/TCXReader.jl)

[3] [TCXWriter: A Tiny Library for writing/creating TCX files on Arduino](https://github.com/firefly-cpp/tcxwriter)

## 🫂 Contributors

Thanks go to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/alenrajsp"><img src="https://avatars.githubusercontent.com/u/27721714?v=4?s=100" width="100px;" alt="alenrajsp"/><br /><sub><b>alenrajsp</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=alenrajsp" title="Code">💻</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=alenrajsp" title="Tests">⚠️</a> <a href="#example-alenrajsp" title="Examples">💡</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=alenrajsp" title="Documentation">📖</a> <a href="#ideas-alenrajsp" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/firefly-cpp/sport-activities-features/issues?q=author%3Aalenrajsp" title="Bug reports">🐛</a> <a href="#maintenance-alenrajsp" title="Maintenance">🚧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.iztok-jr-fister.eu/"><img src="https://avatars.githubusercontent.com/u/1633361?v=4?s=100" width="100px;" alt="Iztok Fister Jr."/><br /><sub><b>Iztok Fister Jr.</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=firefly-cpp" title="Code">💻</a> <a href="https://github.com/firefly-cpp/sport-activities-features/issues?q=author%3Afirefly-cpp" title="Bug reports">🐛</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=firefly-cpp" title="Tests">⚠️</a> <a href="#example-firefly-cpp" title="Examples">💡</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=firefly-cpp" title="Documentation">📖</a> <a href="#ideas-firefly-cpp" title="Ideas, Planning, & Feedback">🤔</a> <a href="#mentoring-firefly-cpp" title="Mentoring">🧑‍🏫</a> <a href="#platform-firefly-cpp" title="Packaging/porting to new platform">📦</a> <a href="#maintenance-firefly-cpp" title="Maintenance">🚧</a> <a href="#data-firefly-cpp" title="Data">🔣</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/luckyLukac"><img src="https://avatars.githubusercontent.com/u/73126820?v=4?s=100" width="100px;" alt="luckyLukac"/><br /><sub><b>luckyLukac</b></sub></a><br /><a href="#ideas-luckyLukac" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=luckyLukac" title="Code">💻</a> <a href="https://github.com/firefly-cpp/sport-activities-features/issues?q=author%3AluckyLukac" title="Bug reports">🐛</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=luckyLukac" title="Tests">⚠️</a> <a href="#example-luckyLukac" title="Examples">💡</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/rhododendrom"><img src="https://avatars.githubusercontent.com/u/3198785?v=4?s=100" width="100px;" alt="rhododendrom"/><br /><sub><b>rhododendrom</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=rhododendrom" title="Code">💻</a> <a href="#design-rhododendrom" title="Design">🎨</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=rhododendrom" title="Documentation">📖</a> <a href="#ideas-rhododendrom" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/lukapecnik"><img src="https://avatars.githubusercontent.com/u/23029992?v=4?s=100" width="100px;" alt="Luka Pečnik"/><br /><sub><b>Luka Pečnik</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=lukapecnik" title="Code">💻</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=lukapecnik" title="Documentation">📖</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=lukapecnik" title="Tests">⚠️</a> <a href="https://github.com/firefly-cpp/sport-activities-features/issues?q=author%3Alukapecnik" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/spelap"><img src="https://avatars.githubusercontent.com/u/19300429?v=4?s=100" width="100px;" alt="spelap"/><br /><sub><b>spelap</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=spelap" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://carlosal1015.github.io"><img src="https://avatars.githubusercontent.com/u/21283014?v=4?s=100" width="100px;" alt="Oromion"/><br /><sub><b>Oromion</b></sub></a><br /><a href="#maintenance-carlosal1015" title="Maintenance">🚧</a> <a href="https://github.com/firefly-cpp/sport-activities-features/issues?q=author%3Acarlosal1015" title="Bug reports">🐛</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/KoprivcLuka"><img src="https://avatars.githubusercontent.com/u/45632449?v=4?s=100" width="100px;" alt="Luka Koprivc"/><br /><sub><b>Luka Koprivc</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/issues?q=author%3AKoprivcLuka" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/garyjellyarms"><img src="https://avatars.githubusercontent.com/u/79595804?v=4?s=100" width="100px;" alt="Nejc Graj"/><br /><sub><b>Nejc Graj</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/issues?q=author%3Agaryjellyarms" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Mtvrt123"><img src="https://avatars.githubusercontent.com/u/50879568?v=4?s=100" width="100px;" alt="MlinaricNejc"/><br /><sub><b>MlinaricNejc</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/issues?q=author%3AMtvrt123" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/KukovecRok"><img src="https://avatars.githubusercontent.com/u/33880044?v=4?s=100" width="100px;" alt="Tatookie"/><br /><sub><b>Tatookie</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=KukovecRok" title="Code">💻</a> <a href="https://github.com/firefly-cpp/sport-activities-features/issues?q=author%3AKukovecRok" title="Bug reports">🐛</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=KukovecRok" title="Tests">⚠️</a> <a href="#example-KukovecRok" title="Examples">💡</a> <a href="#maintenance-KukovecRok" title="Maintenance">🚧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/zala-lahovnik"><img src="https://avatars.githubusercontent.com/u/105444201?v=4?s=100" width="100px;" alt="Zala Lahovnik"/><br /><sub><b>Zala Lahovnik</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=zala-lahovnik" title="Documentation">📖</a> <a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=zala-lahovnik" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/lahovniktadej"><img src="https://avatars.githubusercontent.com/u/57890734?v=4?s=100" width="100px;" alt="Tadej Lahovnik"/><br /><sub><b>Tadej Lahovnik</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=lahovniktadej" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/HlisTilen"><img src="https://avatars.githubusercontent.com/u/44733158?v=4?s=100" width="100px;" alt="HlisTilen"/><br /><sub><b>HlisTilen</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=HlisTilen" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/MihaMi27"><img src="https://avatars.githubusercontent.com/u/82605811?v=4?s=100" width="100px;" alt="Miha Mirt"/><br /><sub><b>Miha Mirt</b></sub></a><br /><a href="https://github.com/firefly-cpp/sport-activities-features/commits?author=MihaMi27" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome!
