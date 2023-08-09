**Episode-4: Geospatial Analysis**

Hello Friends, Welcome to the recap of Ms. Bonny McClain\'s geospatial
analysis talk. Don\'t worry if you weren\'t able to attend the session;
we\'ve got you covered in this short but insightful overview. So let\'s
get started without further delay.

**What is Geospatial Analysis?**

When applied to geographic models, geospatial analysis is the
collection, visualisation, and manipulation of imagery, GPS, satellite
photography, and historical data that is either explicitly described in
terms of geographic coordinates or implicitly in terms of a street
address, postal code, or forest stand identifier.

The earliest geographic information systems were developed in Canada in
the 1960s for documenting natural resources (GIS). All kinds of
occurrences affecting the globe, its systems, and its inhabitants can be
predicted, managed, and learned about using geographic information
systems.

**Data Visualization in our surrounding**

One of the most crucial phases of geospatial analysis is comprehending
and interpreting the narrative of the data that scientists have
collected. Many overlook the fact that since the beginning of human
history, data has been visualised.

**Case-1: Visualisation in Art: Las Meninas**

The most well-known portrait in Velázquez\'s body of work is Las
Meninas. Its focus is the Royal Family of Spain. By the artist\'s
experimentation with perspective, the artwork serves as a psychological
puzzle. In his own work, Velázquez skilfully plays with the observer\'s
perspective by portraying himself as the creator.

At Madrid\'s Alcázar palace of Philip IV, Velázquez\'s studio is the
setting of Las Meninas.

 It is \"a simple box that may be divided into a perspective grid with a
single vanishing point,\" according to Silvio Gaggi.

We are put in an unusual situation when we view the painting from the
characters\' various points of view. Researchers have frequently been
perplexed by the picture since it may be divided into numerous grids of
perspectives, and different interpretations can result depending on the
perspective.

**Case-2: Visualisation in Geography: Earthquake in Turkey**

We can learn about regional trends in earthquake magnitude trends by
looking at a chart or graph that compares the magnitude of the most
recent earthquake to other recent earthquakes.

Researchers identified a pattern in the chart by examining the map that
showed the amount of buildings that were damaged or destroyed in various
locations. It became clear that only a small portion of the map had been
substantially more impacted than the rest.

The outcome of this investigation brought up a crucial issue:
\"Buildings in this area shouldn\'t be impacted in light of the
standards for developing the structure.\" Later it was discovered that
several builders had skimmed the building guidelines and that many homes
had a pancake effect because of their weak cores and structures.

These are a few instances of data visualisation in our environment and
how frequently we deal with them.

**How Does Geospatial Analysis Work?**

**Data collection:** The first step in geospatial analysis is collecting
data that has a geographic component. This can include data on things
like population density, land use, natural resources, weather patterns,
and more.

**Data processing:** Once the data is collected, it needs to be
processed and organized in a way that can be analyzed. This involves
cleaning and preparing the data, formatting it so that it can be
analyzed with GIS software, and creating maps and other visualizations
to help with analysis.

**Spatial analysis:** Once the data is organized and formatted, it can
be analyzed using various geospatial analysis techniques. This can
include identifying patterns and relationships between different
geographic features, measuring distances and areas, identifying clusters
of data points, and more.

**Visualization:** Finally, the results of the analysis can be
visualized on a map or other spatial format. This can include creating
heat maps, choropleth maps, or other visualizations that help to
communicate the results of the analysis to others.

**Fundamentals of Geospatial Analysis**

**Longitude:** Longitudes are vertical lines that measure east or west
of the meridian in Greenwich, England.

**Latitude:** Latitudes are horizontal lines that measure distance north
or south of the equator.

**Winkel Tripel:** German mapper Oswald Winkel proposed three
projections, including the Winkel tripel projection (Winkel III), a
modified azimuthal map projection of the world. The projection is the
equirectangular projection plus the Aitoff projection divided by their
arithmetic means.

**AuthaGraph:** Created in 1999 by Japanese architect Hajime Narukawa,
AuthaGraph is a roughly equal-area map projection of the entire earth.

**Laws of Geospatial Analysis**

**Law-I:** "everything is related to everything else, but near things
are more related than distant things"

**Law-II:** "the phenomenon external to a geographic area of interest
affects what goes on inside"

**Open Source Software for Geospatial Analysis**

**Copernicus EU:** The European Union\'s space program\'s Earth
observation component, Copernicus examines our planet and its
environment for the good of all European residents. It provides
information services based on in-situ (non-space) data and satellite
Earth observation.

The quality of life for European citizens and others around the world is
improved because to the vast volumes of global data collected by
satellites and other ground-based, airborne, and seaborne measuring
equipment. Users can freely access and use the information services
offered.

**Disaster Practitioner Resources from NASA:** Disaster Management
Professionals and Decision-Makers can benefit from NASA\'s Disasters
Practitioner Resources (DPR) collection of tools and materials before,
during, and after natural catastrophes. The DPR programme offers a
variety of tools, data products, and satellite imagery that might help
in disaster management.

**Kaggle:** Kaggle is a platform for machine learning, data exploration,
and data science competitions.

Data scientists and machine learning professionals can work together,
examine, and analyse data using the tools provided by Kaggle.
Additionally, the platform provides a marketplace where businesses may
hold data science competitions, giving them access to a vast global
talent pool of highly qualified data scientists and machine learning
specialists.

**SQL Database and Spatial Function**

Postgres.app is a popular PostgreSQL database management tool for macOS,
Windows and Linux that can be used for geospatial analysis. Here are the
general steps to use Postgres.app for geospatial analysis:

**Install Postgres.app:** Download and install Postgres.app from the
official website.

**Install PostGIS:** PostGIS is an extension for PostgreSQL that enables
geospatial analysis. You can install PostGIS by opening a terminal
window and running the following command:

**CREATE EXTENSION postgis;**

**Import spatial data:** You can import spatial data in a variety of
formats, including GeoJSON, Shapefile, and KML. You can use the
**ogr2ogr** command line tool to convert the data to a
PostgreSQL-compatible format and then import it into the database.

**Query the data:** Once the data is imported, you can use SQL to query
the data and perform geospatial analysis. For example, you can use the
ST_Contains function to find all the points that are contained within a
given polygon.

**SELECT \* FROM points WHERE ST_Contains(polygon, point);**

**Visualize the data:** You can use tools like QGIS or Tableau to
visualize the data and create maps.

**Advantages**

The visualization of spatial data also makes it easier to see how things
are changing over time and where the change is most pronounced.

Benefits of geospatial analytics include:

**Engaging insight:** Seeing data in the context of a visual map makes
it easier to understand how events are unfolding and how to react to
those events.

**Better foresight:** Seeing how spatial conditions are changing in real
time can help an organization better prepare for change and determine
future action.

**Targeted solutions:** Seeing location-based data helps organizations
understand why some locations and countries, such as the United States,
are more successful for business than others.

**Career Opportunities in Geospatial Analysis**

Geospatial analysis is a rapidly growing field that offers a variety of
career opportunities.

Here are some of the most popular career paths in geospatial analysis:

**Geospatial Analyst:** Geospatial analysts use geographic information
systems (GIS) to create maps and analyze data. They work in a variety of
industries, including environmental science, urban planning, and
defense.

**GIS Developer:** GIS developers create and maintain software
applications that use GIS data. They may work on web-based mapping
applications, mobile apps, or desktop GIS software.

**Remote Sensing Scientist:** Remote sensing scientists use satellite
and aerial imagery to collect and analyze data about the earth\'s
surface. They work in a variety of industries, including agriculture,
environmental science, and natural resource management.
