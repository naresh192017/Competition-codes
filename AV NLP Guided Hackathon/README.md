![AV-NLP-Hackathon-thumbnail-1200x1200](https://datahack-prod.s3.ap-south-1.amazonaws.com/__sized__/contest_cover/cover_copy-thumbnail-1200x1200-90.jpg)

# NLP Guided Hackathon by AnalyticsVidhya

Link to the competition [here](https://datahack.analyticsvidhya.com/contest/hacklive-3-guided-hackathon-text-classification/).

## Problem Statement:

**Building a model to  predict the tags associated with the research  articles.**

The research article abstracts are sourced from the following 4 topics: 
1. Computer Science
2. Mathematics
3. Physics
4. Statistics

List of possible tags are as follows:
[Tags, Analysis of PDEs, Applications, Artificial Intelligence,Astrophysics of Galaxies, Computation and Language, Computer Vision and Pattern Recognition, Cosmology and Nongalactic Astrophysics, Data Structures and Algorithms, Differential Geometry, Earth and Planetary Astrophysics, Fluid Dynamics,Information Theory, Instrumentation and Methods for Astrophysics, Machine Learning, Materials Science, Methodology, Number Theory, Optimization and Control, Representation Theory, Robotics, Social and Information Networks, Statistics Theory, Strongly Correlated Electrons, Superconductivity, Systems and Control]

## Data Description:


| __Variable__ | __Definition__ |
|-------------|------------|
| id         | Unique ID for each article     |
| ABSTRACT         | Abstract of the research article     |
| Computer Science         | Whether article belongs to topic computer science (1/0)     |
| Mathematics         | Whether article belongs to topic Mathematics (1/0)     |
| Physics        | Whether article belongs to topic physics (1/0)     |
| Statistics         | Whether article belongs to topic Statistics (1/0)     |
| Tags        | (TARGET) There are 25 columns of possible tags with (1/0) :
1 : if article belongs to that tag
0 : if article doesn't belong to that tag     |

