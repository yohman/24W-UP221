# UP221: Introduction to GIS and Spatial Data Science

Winter 2024

Mondays 5pm - 7:50pm

[Recurring Zoom link](https://ucla.zoom.us/j/94971812993?pwd=NjI4bkxRR2s3Q0FVblU0WmlHbXNodz09)

## Course format:

**Live-Online/Synchronous**

This course will meet in real time via Zoom. Classes meet at regularly scheduled times and you will have the opportunity to interact with your instructor and your classmates. Just like a regular on-campus class, you are expected to attend and participate in discussions.

**Camera use**

Cameras are expected to be on during instruction. If you have any concerns about using your camera during class, please share those in the survey distributed at the beginning of the quarter, contact me via email, and/or talk to me during office hours. We will work together to determine the best approach to address any concerns you may have.

## Instructor: 

Chris Giamarino (cgiamarino@g.ucla.edu)

## Teaching Assistants:

Ariella Ventura (ariellasventura@gmail.com)

Lucy Briggs (lbriggs@g.ucla.edu)

## Special Technology Assistant:

For issues regarding JupyterHub.

Ben Winjum (bwinjum@ucla.edu)

## Office Hours: 

* Chris, Mondays 8 - 9 pm after class and Tuesdays from 6 - 7 pm (use course Zoom link; available via email and slack)

* Ariella, Tuesdays from 1-3 pm (schedule via email/Zoom)

* Lucy, Thursdays from 4 - 6 pm (schedule via email/Zoom)

## Course Description

The goal for this course is to expose you to the foundations of spatial data science. Where once there was a dearth of available digital information, we now live in a world of too much data. How can these data be transformed into human expressions and narratives, and how can these be represented spatially? Our understanding of social phenomena through spatial constructs in urban data allows us to address location-based questions on social justice, the environment, transportation, community development and design, amongst many other themes, and how these factors may affect different population groups in different ways. 

This course prepares you for challenges in urban data beyond off-the-shelf cartographic approaches. It looks at the various components of data’s journey—acquisition, exploration, modeling, and communication through visualization—and how it enables and advances your research from a data science perspective.

We begin with an introduction to various data science tools, and review the basics of programming with Python. Once a foundation of Python programming and data wrangling is achieved, spatial analysis through Python Libraries, and subsequently, through advanced geoprocessing will be introduced. All lessons will be based on “real” data with analytical methods addressing relevant and contemporary urban problems. 

In addition to the programming lab sessions, you will be given weekly or bi-weekly "thinking cap" assignments, where you will be asked to think critically about contemporary urban issues. Be prepared to address various topics from the perspective of your own lived experiences, how it informs the topic, and what kind of research can advance knowledge in a positive way.

While there are no prerequisites for taking this course, people who are approaching programming for the first time will admittedly find the course to be intense and challenging.

## Learning Objectives for UP206A

At the conclusion of this course, students will be able to critically describe, analyze, and visualize spatial data for planning practices and research.

Specifically, students will learn to:

- Demonstrate the value of data for planning purposes through discovery, exploration, and analysis
- Critically evaluate data and create frameworks to prepare data for research
- Apply data science programming techniques to produce relevant visualizations that inform urban policy
- Learn to visualize data spatially to communicate the importance of place-based informatics
- Learn to produce publication-ready scholarly materials in the form of tables, charts, and maps

### Zoom and Slack

The following applications must be launched at the start of every class session:

- Zoom: In order for instructors to be able to troubleshoot, or to demonstrate solutions to problems, it is constructive for students to share their screens with the class. In addition, in-class presentations (midterms, finals) will use a shared zoom screen to present content to the class.
- Slack: Sharing resources, code snippets, and general commentary on class material is better situated in Slack, as unlike the zoom chat, the records are archived and made available after class. 

## Inspirations

I would be remiss if I do not mention various inspirations that have led to the creation of this course. First and foremost, [Yoh Kawano](https://luskin.ucla.edu/person/yoh-kawano) crafted this course and was gracious enough to mentor me as a TA for several years, lend me the material, and show me how to teach GIS and python effectively. Second, the late and great [Leo Estrada](https://luskin.ucla.edu/in-memoriam-leo-estrada-urban-planning-scholar-and-champion-of-diversity), who was Yoh's mentor and confidant over the years, who taught GIS at our department for many decades. Leo and Yoh spoke extensively about modifying this course to a more “modern” approach, and I am delighted and honored to uphold both of their legacies moving forward.

Third, we have taken the liberty (with permission) to borrow ideas and materials from other courses. We specifically took inspiration from [Paul Waddell](https://ced.berkeley.edu/ced/faculty-staff/paul-waddell)’s “[Urban Informatics and Visualization](https://github.com/waddell/CP255)” course at UC Berkeley, and [Geoff Boeing](https://geoffboeing.com/about/)’s “[Data, Evidence, and Communication for the Public Good](https://github.com/gboeing/ppd534)” at the Department of Urban Planning and Spatial Analysis at USC’s Sol Price School of Public Policy.

## Course materials

The course will almost entirely be conducted on Jupyter Notebooks. A [JupyterHub](https://jupyter.idre.ucla.edu), a web-based Jupyter Notebook environment, has been set up specifically for this class, and is available at the following [URL](https://jupyter.idre.ucla.edu). Note that you will need multi-factored authentication to login:

*   [JupyterHub](https://jupyter.idre.ucla.edu) (choose UCLA)
* [Course slack](https://join.slack.com/t/24w-up221/shared_invite/zt-2a3ipi7fa-J2T3HyDezDLVabcIzG7V_w)

Weekly course materials, including presentations, interactive notebooks (.ipynb), and data will be made available through a course github repository (here) that you will interact with through your JupyterHub account.

## Assignments and Evaluation

All assignments, unless otherwise specified, must be posted on your individual GitHub accounts or on the class GitHub discussion section by midnight of the Sunday prior to our class on Monday. Assignments are posted in each week's page, so make sure to read the instructions carefully. 

- Participation, individual progress, coding and reading assignments 10%
- Group assignments 40%
   - There will be four group assignments throughout the quarter. Each assignment will be worth 25% of the total group assignment grade.
- Mid-term 20%
- Final report 30%

| Task | Number of items | Points |
|------|-----------------|--------|
| Participation and individual assignments | 7-10 | 100 |
| Group Assignments | 4 | 400 |
| Mid-term | 1 | 200 |
| Final report | 1 | 300 |

## Grading criteria

All assignments are graded on the following criteria:

- **Timeliness**: Unless otherwise specified, all assignments are due at midnight of the day before the next class. For most assignments, you will be asked to submit them as posts in the discussion section of the class repo. The timestamp of your post will be used to determine whether they were submitted on time. 
- **Cleanliness**: Nobody wants to go through unreadable code! Make sure to document your work accordingly, providing markdown cells and comments throughout.
- **Does it work?**: Unless you purposefully created code cells that produce errors to make a point, notebook assignments must run from top to bottom without any errors. Verify this by restarting the kernel, and running all cells.
- **Thinking out of the box**: It is easy to copy an existing notebook, and replace datasets and parameters to fulfill an assignment. But how well have you/your group grasped the underlying concepts? This can be demonstrated by your ability to think outside the box, and *applying* rather than *copying* each step of a given assignment. For example, you may experiment with functions not demonstrated in class, or create your own workflow that borrows certain concepts learned in class to make them your own.


Grade | Description
---|---
A/A+ | Exceptional/creative/innovative work, demonstrating grasp of material, application of concepts to your own inquiry, going above and beyond course material
A- | Good grasp of material and solid application to your own research inquiry
B+ | Average understanding of material, largely duplicating course material to fit with your own research inquiry
B and below | Submission is incomplete or produces errors

[Hints for creating an exceptional assignment](https://docs.google.com/document/d/1D4ud1I9vuDPNDudINPC4-MLG-PV7AnzvkexZ-KFqyWk/edit?usp=sharing)

## Late assignments

Late assignments will be marked down one grade for each day it is late. For example, if your assigment warrants an "A" but is a day late, you will receive an "A-." As long as you submit your assignment before 10th week, you will get at least a "C."

## Weekly Schedule 

**Note:** Weekly content is subject to change, and will be modified as needed based on class discussions, needs, and progress.

### Preparation

*   Fill out the [pre-class survey](https://docs.google.com/forms/d/e/1FAIpQLSfs2NtxTY5HTcT6fr3-5TqoiD0fVcWptpjRifR1NU6v5jdXRg/viewform?vc=0&c=0&w=1&flr=0) 
*   If you do not have a GitHub account, create one for the class
	*   [https://github.com/](https://github.com/)
*   Make sure you can log into the class JupyterHub
	*   [JupyterHub](https://jupyter.idre.ucla.edu) (choose UCLA)

Week | Topic
--- | ---
Week 1 | [Introduction to spatial data science](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week01%20Intro)
Week 2 | [Data in Urban Studies: The challenge in data acquisition](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week02%20Spatial%20Data%20Exploration)<br> → [Group assignment #1: Project Proposal](https://github.com/cgiamarino9/24W-UP221/blob/main/Group%20Assignments/GroupAssignment1.md)
Week 3 | [Understanding communities: Census data profiles](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week03%20Census%20Data)<br> →   [Group assignment #2: Census Data Exploration](https://github.com/cgiamarino9/24W-UP221/blob/main/Group%20Assignments/GroupAssignment2.md)
Week 4 | [Open Data and APIs](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week04%20Open%20data)
Week 5 | [Open street maps](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week05%20Open%20Street%20Map)
Week 6 | [Mid-terms](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week06)<br> →  [Midterms](https://github.com/cgiamarino9/24W-UP221/tree/main/Midterm%20and%20Finals)
Week 7 | [Geocoding, multiple overlays, and functions](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week07%20Isochrone%20Maps)<br> →  [Group assignment #3: Data Visualization](https://github.com/cgiamarino9/24W-UP221/blob/main/Group%20Assignments/GroupAssignment3.md)
Week 8 | [Spatial statistics](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week08%20Spatial%20Autocorrelation)
Week 9 | [Point pattern analysis](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week09%20Point%20Patterns)<br> →  [Group assignment #4: Spatial Analysis](https://github.com/cgiamarino9/24W-UP221/blob/main/Group%20Assignments/GroupAssignment3.md)
Week 10 |[Remote Sensing and Sentiment Analysis](https://github.com/cgiamarino9/24W-UP221/tree/main/Weeks/Week10-Metro%20scraping%20and%20remote%20sensing)
Finals Week | [Finals](https://github.com/cgiamarino9/24W-UP221/tree/main/Midterm%20and%20Finals)

## How to ask a technical question

Given the nature of the course, you will have many, many questions along the way. However, we ask that you adhere to the following guidelines in order to make consultations as productive as possible. Students who do not follow these guidelines will be asked to reschedule.

Before asking a question:

1. Close all open programs, restart your computer, then try your task again
2. Search google and stackoverflow for the topic/problem (for example, the name of the function you're struggling with or the error message you are seeing)
3. Check out GitHub's [CoPilot AI coding helper](https://docs.github.com/en/copilot/quickstart). It is free with a [GitHub Educator profile](https://education.github.com/), which you need to provide proof of enrollment such as a photo of your UCLA ID. 
4. Go back through the relevant lecture materials to look for any insights
5. Go back through the assigned reading materials to look for any insights

If the above steps haven't solved your problem, send an email (or attend office hours) and include the following information:

1. A detailed description of what you're trying to do, why, and how
2. A complete [minimal reproducible example](https://stackoverflow.com/help/minimal-reproducible-example) of your code so far (never send screenshots of code)
3. What you've already tried to do to solve your problem and what you have learned from it (specifically, explain the results of steps 1-5 above, including relevant links from stackoverflow etc)

## Readings and Resources

Readings will be posted in the assignment sections for each week. The following are a list of resources to help you with the more technical aspects of the course:

*   [Geographic Data Science with PySAL and the PyData Stack](https://geographicdata.science/book/intro.html)
*   [Spatial Analysis Methods and Practice by George Grekousis](https://www.cambridge.org/core/books/spatial-analysis-methods-and-practice/4C135005A621335D06CC63EFF17E3913)   
*   Think Python 2nd Edition by Allen B. Downey
	*   [https://greenteapress.com/wp/think-python-2e/](https://greenteapress.com/wp/think-python-2e/)
*   Jupyter Notebooks
	*   [https://jupyter.readthedocs.io/en/latest/index.html](https://jupyter.readthedocs.io/en/latest/index.html) 
*   [gboeing/ppd534: USC PPD534: Data, Evidence, and Communication for the Public Good](https://github.com/gboeing/ppd534)
	*   University of Southern California
	*   Professor: Geoff Boeing
*   [CP255: Urban Informatics and Visualization](https://github.com/waddell/CP255)
	*   University of California, Berkeley Department of City and Regional Planning
	*   Professor: Paul Waddell
*   [Automating GIS-processes 2019](https://automating-gis-processes.github.io/site/)
	*   University of Helsinki, Finland
*   [Computing for the Social Sciences](https://cfss.uchicago.edu/notes/) (R focused)
	*   University of Chicago

## Statement of Affirmation

I intend to make this classroom a space that affirms all identities and perspectives, including your race, color, national origin, ethnic origin, ancestry, marital status, religion, age, sex, gender, gender expression, gender identity, transgender status, pregnancy, physical or mental disability, medical condition, genetic information (including family medical history), sexual orientation, political ideology and affiliations, citizenship, or service in the uniformed services. Regardless of background, all students have a right to an equitable education. Because of the multi-faceted and complex nature of our identities, it is imperative that we are committed to affirming one another’s perspectives as a community for all enrolled in this course. I encourage all members to embrace and learn from the diversity in this classroom, school, and university. I want to highlight that discrimination, harassment, or forms of hateful transgressions will not be tolerated in our learning environment. If you have any recommendations about how to make our environment more inclusive please feel free to let me know. 

## Accommodations based on disability

If you are already registered with the Center for Accessible Education (CAE), please request your Letter of Accommodation on the Student Portal. If you are seeking registration with the CAE, please submit your request for accommodations via the CAE website. Please note that the CAE does not send accommodations letters to instructors--you must request that I view the letter in the online Faculty Portal. Once you have requested your accommodations via the Student Portal, please notify me immediately so I can view your letter.

Students with disabilities requiring academic accommodations should submit their request for accommodations as soon as possible, as it may take up to two weeks to review the request. For more information, please visit the CAE website (www.cae.ucla.edu), visit the CAE at A255 Murphy Hall, or contact by phone at (310) 825-1501.

