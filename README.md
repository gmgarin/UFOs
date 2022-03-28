# UFOs: Data Analysis Using JavaScript

# Overview of the Project
### The purpose of this project is to create a webpage with dynamic tables. Furthernore, it intends to provide in-depth analysis of UFO sightings from the data provided to allow users to filter through multiple criteria at the same time. The tools used in this projects are:
- JavaScript
- HTML
- Bootstrap
- CSS

## Results
### The results of this analysis created a [webpage](https://github.com/gmgarin/UFOs/blob/2b9030de9cda2030a3d6a9f12f5eaaa23549062e/index.html). The [data](https://github.com/gmgarin/UFOs/blob/0e3b27b87240a55db5c067bb526729a39072beae/static/js/data.js) were transformed into an interactive [webpage](https://github.com/gmgarin/UFOs/blob/2b9030de9cda2030a3d6a9f12f5eaaa23549062e/index.html) were visitors can use the filter feature to narrow down their search. 

![This is an image](https://github.com/gmgarin/UFOs/blob/312db3e23803b8e12340428f12477b4b27bfa141/static/images/webpage.png)

<p align="center">
   UFO Sightings Webpage
</p>

![This is an image](https://github.com/gmgarin/UFOs/blob/4f585e24393a6f196b5f33d1d46d7c3d4e710e10/static/images/filter.png)

<p align="center">
   Filter Search Feature
</p>


### As mentioned, the [webpage's](https://github.com/gmgarin/UFOs/blob/2b9030de9cda2030a3d6a9f12f5eaaa23549062e/index.html) feature is the filter search using criteria. Users can filter using one or more criteria at the same.

### Using single criteria:
![This is an image](https://github.com/gmgarin/UFOs/blob/54c5e9abe1a3674ca5d45964d2771d253f625c68/static/images/single_criteria.png)

### Using multiple criteria:
![This is an image](https://github.com/gmgarin/UFOs/blob/54c5e9abe1a3674ca5d45964d2771d253f625c68/static/images/multiple_criteria.png)

### Users can also reset search by deleting entry in each criteria boxes. 

## Summary
### JavaScript can be used to analyze data and visualize results using HTML. Using these tools can make it easier for end users to search through the data using filter search. 

### **_Drawback_**
### One drawback of this particular project is that the filter search is "case-sensitive" which means that end users cannot use uppercase letters when searching. When typing, the input words has to match the manner in which the criteria is written.

![This is an image](https://github.com/gmgarin/UFOs/blob/f4a8931225552c32ffcfaf2f8dedd59866d757f1/static/images/drawback_1.png)

<p align="center">
   Uppercase search using "State" criteria with no results found
</p>

1[This is an image](https://github.com/gmgarin/UFOs/blob/f4a8931225552c32ffcfaf2f8dedd59866d757f1/static/images/drawback_2.png)

<p align="center">
   Lowercase search using "State" criteria
</p>

### Since all the states in "State" criteria are written with lowercase letters, input should be in lowercase letters, otherwise, no results will populate. 

### To futher enhance this project, I would recommend the following:
- "Search" button on the webapge.
- Word suggestions and/or dropdown list in each criteria
- Additonal data which may include UFO sightings in other countries to fully utilize "Filter Search" feature.