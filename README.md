# HSMA Session 3C

## Slides

<a href="https://docs.google.com/presentation/d/1Xj9jYaJ_FH7ko84DGJ2M1l4DWfJ-W5wmY906UkUEgRg/edit?usp=sharing"><img src="https://img.shields.io/static/v1?label=Google+Slides&message=Click+here+to+view+the+slides+for+this+session&color=%23FBBC04&style=for-the-badge&logo=googleslides&logoColor=%23FBBC04" alt="Google Slides - Click here to view slides for this session"></a>

## Book

<a href="https://hsma-programme.github.io/hsma6_geographic_optimisation_and_visualisation_book/"><img src="https://img.shields.io/static/v1?label=Book&message=Click+here+to+view+the+relevant+HSMA+book&color=%23782828&style=for-the-badge&logo=mdbook" alt="Book - Click here to view the relevant HSMA book"></a>

## Lecture Recording

<a href="https://youtu.be/_14heKZ9YjA"><img src="https://img.shields.io/static/v1?label=Youtube&message=Click+here+to+watch+the+interactive+python+map+section&color=%23282828&style=for-the-badge&logo=youtube&logoColor=%23FF0000" alt="Youtube - Click here to watch the QGIS section of the lecture"></a>

<a href="https://youtu.be/_KD7gOMPFgY"><img src="https://img.shields.io/static/v1?label=Youtube&message=Click+here+to+watch+the+travel+time+visualisation+section&color=%23282828&style=for-the-badge&logo=youtube&logoColor=%23FF0000" alt="Youtube - Click here to watch the python section of the lecture"></a>

<a href="https://www.youtube.com/watch?v=Zd8mQIXNq-o"><img src="https://img.shields.io/static/v1?label=Youtube&message=Click+here+to+watch+the+routingpy+section&color=%23282828&style=for-the-badge&logo=youtube&logoColor=%23FF0000" alt="Youtube - Click here to watch the python section of the lecture"></a>

Note that due to time constraints the routingpy section does not go into detail about routingpy code; an additional video explaining this will be uploaded in the future, but you can follow through this code in the slide and in the ebook.

## Exercises

The notebooks in the `exercises` folder can be downloaded and run locally if you have Python installed.

Alternatively, you can run each exercise on **Google Colab**, a free online platform for coding exercises. You will need to be logged in to a google account in your browser. 

Using the links below will open a fresh copy of the notebook to work on - your changes will not be visible to anyone else. However, if you want to be able to refer back to your version of the notebook in future, make sure you click **'File --> Save to Drive'**. 
Your changes will then be saved to your own account, and you can access your edited copy of the notebook from https://colab.research.google.com/.

Open Exercise 1 in Google Colab: <a target="_blank" href="https://colab.research.google.com/github/hsma-programme/h6_3c_interactive_plots_travel/blob/main/h6_3c_interactive_plots_travel/exercises_colab/HSMA 3C Exercise 1 - Interactive Plots.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Open Exercise 2 in Google Colab: <a target="_blank" href="https://colab.research.google.com/github/hsma-programme/h6_3c_interactive_plots_travel/blob/main/h6_3c_interactive_plots_travel/exercises_colab/HSMA 3C Exercise 2 - Using Precalculated Travel Time Matrices.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Open Exercise 3 in Google Colab: <a target="_blank" href="https://colab.research.google.com/github/hsma-programme/h6_3c_interactive_plots_travel/blob/main/h6_3c_interactive_plots_travel/exercises_colab/HSMA 3C Exercise 3 - Getting Travel Matrices with routingpy.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


### Exercise Structure

Notebooks are split into **core**, **extension** and **challenge** sections. 

All students should aim to complete the exercises within the **core** section. Completing these exercises will give you practice of all of the key concepts discussed in the lectures and you can stop after this section if you wish. 

Students looking to push themselves and their understanding can go on to attempt the **extension** exercises if they would like to.

The **challenge** section contains exercises that may go beyond what is covered in the lectures; there will be an expectation of looking things up in documentation or on sites such as StackOverflow, or using tools such as perplexity.ai to obtain boilerplate code. These exercises may take significantly longer than is allocated during the lectures and are designed to be an enjoyable challenge for those who want to push their coding skills.

## Solutions

Solution notebooks are available in the **solutions** folder, or can be opened in Colab. 

Open Exercise 1 in Google Colab: <a target="_blank" href="https://colab.research.google.com/github/hsma-programme/h6_3c_interactive_plots_travel/blob/main/h6_3c_interactive_plots_travel/solutions/HSMA 3C Exercise 1 - Interactive Plots.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Note - this notebook can struggle in Colab due to the size of the interactive plots. Running the whole notebook from top to bottom may result in your Colab instance disconnecting, so just run the cells relating to one dataset at a time, before choosing runtime --> restart kernel. 

After restarting the kernel, you will need to rerun the colab-specific cell to import the repository and also rerun the cell relating to package imports. 


Open Exercise 2 in Google Colab: <a target="_blank" href="https://colab.research.google.com/github/hsma-programme/h6_3c_interactive_plots_travel/blob/main/h6_3c_interactive_plots_travel/solutions/HSMA 3C Exercise 2 - Using Precalculated Travel Time Matrices.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Open Exercise 3 in Google Colab: <a target="_blank" href="https://colab.research.google.com/github/hsma-programme/h6_3c_interactive_plots_travel/blob/main/h6_3c_interactive_plots_travel/solutions/HSMA 3C Exercise 3 - Getting Travel Matrices with routingpy.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


## Learning Objectives

### Part 1: Interactive Maps

Students should be able to:

- Create an interactive point map using Folium
- Create an interactive choropleth using Folium
- Add custom markers to Folium maps
- Change the basemap tiles in a Folium map
- Explain when to choose Folium vs Kepler for interactive maps

### Part 2: Working with Travel Times

Students should be able to:

- Use a pre-collected dataset of LSOA-LSOA centroid travel times to generate a choropleth
- Use the matrix method of the routingpy package to generate car and walking travel times from an open-source API for a given combination of sources and destinations
- Explain the benefits and downsides of using routingpy over directly interacting with different travel time APIs
- Show an awareness of the limitations of different travel time APIs
- Explain what an isochrone is
