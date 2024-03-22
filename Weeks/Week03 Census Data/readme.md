---
marp: true
theme: uncover
headingDivider: 3
footer: UP221 | Intro to GIS and Spatial Data Science ![width:30px](../images/globe.png)
paginate: true

---

<style>
kesmall {font-size:0.6em}
medium {font-size:0.9em}
large {font-size:2em}
xlarge {font-size:4em}
gray {padding:20px;background-color:whitesmoke;font-weight:800}
plum {padding:20px;background-color:plum;line-height:3}
xl { font-size:2.5em;font-weight:100;line-height:1}
h1,h2,h3,h4,h5{font-family:serif}
section {font-size:2em;font-weight:300;}
left {text-align:left;}
</style>

# Week 3

<xl>

Census Data Exploration

</xl>

[Course zoom link for Winter Quarter 2024](https://ucla.zoom.us/j/94971812993?pwd=NjI4bkxRR2s3Q0FVblU0WmlHbXNodz09)


January 22, 2024

##
<xl>

*Note that this course will be recorded🎥

</xl>

##

<xl>
Street art in Italy
</xl>

##

![width:500px](../images/cigs.JPG)


##

![bg](../images/rome.JPG)


##

![bg](../images/gator.JPG)

##
<xl>
My rainy weekend ...
</xl>

##

![width:700px](../images/courts.JPG)

##

![bg](../images/burbank.JPG)

##

![width:700px](../images/blue.JPG)

##

![width:700px](../images/walts.JPG)

## Hands on Lab
First, grab the course material, and "pull" it into your JupyterHub:

* [UP221 Git Puller](https://jupyter.idre.ucla.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcgiamarino9%2F24W-UP221&urlpath=lab%2Ftree%2F24W-UP221%2F&branch=main) 
(This link will automatically launch JupyterHub and clone the course material into your directory)

<small>Note that you have to do this at the start of every lecture to get the latest material.
</small>


# Assignments (due 11:59 Sunday, January 28th the day before class)


## Group Assignment #1
<xl>Project Proposal</xl>
<hr>

<left>

The course will largely be guided by your final project, which will be conducted in groups of 4-5. Consider that your final project will be a representation of what you learn in this course, and how you apply it on a project level. Consider also that your final project can serve to showcase your data science and mapping skills, which may become a valuable asset for your career moving forward.


### Step 1: Plan
<hr>

<left>
Meet with your groups, discuss and identify a research question, identify and collect data, articulate how you intend to use and analyze it, and begin to speculate how the data can answer your research inquiry. Understand that this may change later, especially as we learn more about what we can do with our methods, and also, as you find the data sources that can or cannot support your research.

### Step 2: Data
<hr>
<left>
Next, identify and download at least two datasets that you believe can guide your research. Make sure that at least one of them has a spatial component. For example, if one of your datasets comes from the census, identify which survey you will use (e.g. Decennial or American Community Survey), and which variables you will select. Note that we will be covering census data in detail in Week 3. Your second dataset should come from a separate source. For example, you may want to do a crime analysis and obtain data from the LA Data Portal.

### Step 3: Create a group repo. 

1. Select a member of the group who will be the main account holder of the repo
2. Create a new repository for your group project
3. Go to Settings, Manage Access, and add your partner as a collaborator
1. Create a Group Assignments folder (hint: click on Add File, Create new File, and enter "Group Assignments/readme.md" in the text box)
4. Create a markdown file for your project proposal

### Step 4: Write your proposal
<hr>

<medium>

Your project proposal should include the following:
*   An introduction of your research question
*   An explanation of why it is important to you, why it matters to others, and what is at stake
*   A description of the spatial scope (e.g. Boyle Heights or Hong Kong), and why space and/or time matters for your project
*   A preliminary but definitive description of data sources (at least two) that you will use
    * Include datasource with links
*   A scope that explains the intended analysis and resulting visualizations for your project
*   A concluding paragraph of what insights you expect to gain from your research

### Step 5: Submit
Submit your assignment [here](https://github.com/cgiamarino9/24W-UP221/discussions/9)

## Group Assignment #2

<xl>

Census Data Exploration

</xl>

### Step 1: Plan
<hr>
<left>
For this group assignment, each group member will create and submit a separate Jupyter Notebook. Each notebook should choose census indicators that are relevant to your research project. For example:
<hr>
<medium>

-  one group member may choose to do a race profile for Los Angeles, and the other member may choose to do the same race profile for New York
-  one member may choose to do a transportation profile for Los Angeles, and the other member may choose an education profile also for Los Angeles
-  each member may choose a different time period to do a temporal analysis.

### Warnings:
<hr>
<left>

**Do not copy and paste the class lab. Make sure to start a brand new notebook.**

**If you are working on a project outside of the United States, consult with me to find an alternative dataset to explore.**

### Step 2: Program
<hr>
<small>

1.   The first cell of the notebook should be a markdown cell that includes a title, description, and author of the assignment.
1.   Download census variables relevant to your research question (if you are working outside of the United States, consult with me to find an alternative dataset)
1.   Create a Jupyter Notebook and use pandas/geopandas to explore and visualize the data
1.   Produce several charts, including one or more maps
1.   Make sure to document each procedure with markdown cells with relevant headers
1.   Run the cells in the notebook, and make sure the notebook "reads" from top to bottom, telling a story
1.   Upload each Jupyter Notebook along with the associated census data file to your group repo
</small>

### Step 3: Submit

- Submit your assignment by posting a link to your notebook [here](https://github.com/cgiamarino9/24W-UP221/discussions/5).
