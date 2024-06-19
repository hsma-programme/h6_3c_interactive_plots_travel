# HSMA Session 3C

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
