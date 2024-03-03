[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/nT4M_vAo)
# Sprint 2 - 90803
### Machine Learning Foundations with Python
#### Spring 2024

---

> Modify here: 

For this Lab, you will need to do the following:

1. Git clone your repo to your local machine (look back at Lab 1 if you have any doubts), using the SSH connection.
2. Open the `Sprint2_S24_TeamName` jupyter notebook and work through it.
3. It is advisable to work on different branches and, in the end, merge your branches to `main`.
4. Periodically go back to the terminal to commit your changes to your Jupyter Notebook. Do not wait until the end; make sure to commit for at least every question in the notebook. Remember that doing a commit involves:
	-  Making changes to your jupyter notebook
	-  Adding changes to your staging area (`git add`)
	-  Committing, with a descriptive message of the task you are committing (`git commit -m "descriptive message"`).
	-  Add a gitignore `git add .gitignore` - for the files you want the commit to ignore. For example, in MacOS you might want to ignore `.DS_Store`. Add this to your gitignore `echo .DS_Store >> .gitignore`. Other files that you might want to include here are `ipynb_checkpoints/*`.
	-  Here are some links if you want to read more on [ipynb checkpoints](https://stackoverflow.com/questions/46421663/what-are-jupyter-notebook-checkpoint-files-for) or how to [gitignore](https://stackoverflow.com/questions/35916658/how-to-git-ignore-ipython-notebook-checkpoints-anywhere-in-repository) them.
5. When you are ready to push back to your GitHub remote repo, make sure to:
	- Have any branches merged into `main`
	- `git push origin main`
	- Have your passphrase at hand
	- After the first push, remember to always `git pull` before working on your local repo (to make sure you're up to date) and then `git push` when you are ready to push changes back to your remote repo.



## Notes on this Sprint - To Modify
- Please follow the instructions provided in the videos (CANVAS)
- Once you are done, please answer the questions below. Make sure you have discussed and come to a consensus when addressing the following questions.

> Modify here: 

**1. List the names of all your teammates:**
Gracie Siu, Sharon John, Sara Clemente

**2. Agree as a team, what branching strategy do you plan to use in your final projects? Justify your choices**
We will each work on our own branches and merge to a main branch

**3.Communication: Outline how the team will communicate — including frequency and methods (e.g., email, WhatsApp, team meetings).  What is the maximum expected response time?**
We will communicate via WhatsApp
Expected response time is same day

**4. Decision-Making: How will decisions be made in this team? How will you stay on track? Do you plan on having meetings or any strategies for working through your final project**
Decisions will be made through consensus
We will stay on track through mid-sprint deadlines and regular check-ins 
We will meet in person (prefer to meet in person) as much as possible for regular project items

**5. As with any team project there is always the possibility of conflict arising, if it does in the future, how will you resolve differences? List at least two strategies**
We will resolve differences through open and honest communication and discussion, over snacks and good coffee!



**6.Commitments: How will you handle different levels of participation and commitment? What process will you follow if someone does not live up to his/her/their responsibilities? (3-5 sentences)**
We will openly discuss with the team member with curiosity - assume an oops not an ouch!


**7.Diversity: How will you accommodate different learning and working styles? Talk about your own styles and schedules for working and come to an agreement (3-6 sentences)**
We all like to meet in the mornings before classes, which works well
Sharon likes to use interview rooms which will work well for meeting locations in Heinz
We all will support each other in this project by ensuring that we are all on the same page of a question or area of the project before moving on to the next phase. 

# Sprint 3 - 90803
### Machine Learning Foundations with Python
#### Spring 2024

Project Title: Gender Difference Indicators and Share of female STEM graduates

Team Names & Emails: Sara Clemente (saraclem@andrew.cmu.edu), Sharon John (sharonjo@andrew.cmu.edu), Gracie Siu (gsiu@andew.cmu.edu)


Project Description: 
Why is this topic relevant?
Gender disparities persist in STEM fields worldwide, with women being underrepresented in these areas compared to men. Addressing these disparities is crucial for achieving gender equality and ensuring that all individuals have equal opportunities to pursue careers in high-demand fields.

Who does this topic affect? Where does it happen? When did it happen?
This topic affects various stakeholders, including individuals, communities, industries, and economies. For individuals, it impacts career opportunities, earning potential, and professional fulfillment. Communities benefit from diverse perspectives and solutions that arise from gender-inclusive STEM environments. Industries benefit from tapping into a broader talent pool, fostering innovation, and addressing skill shortages. Economies benefit from increased productivity, competitiveness, and economic growth when all segments of the population are fully engaged in STEM fields.

The scope: Gender disparities happen in STEM worldwide, although the extent of these disparities may vary across regions and countries.While some countries have made significant strides in promoting gender diversity in STEM, others continue to face significant challenges. This issue is not limited to a specific geographic location but rather spans across continents and cultures.

Timeline:
Gender disparities in STEM have historical roots, stemming from systemic biases, social norms, and cultural expectations. While progress has been made in recent decades to address these disparities, significant gaps persist. Understanding the historical context of gender inequalities in STEM is essential for designing effective interventions and policies to promote diversity and inclusion.


What are your motivations for addressing this topic?
As three women in STEM we know the beauty but also challenges in this field. Addressing gender disparities in STEM is not only a matter of social justice but also an economic imperative. By ensuring equal access and opportunities for all individuals in STEM fields, societies can unlock the full potential of their human capital, drive innovation, and build a more equitable and prosperous future for everyone.

Datasets:
Gender data: https://genderdata.worldbank.org/
Format: CSV
Metadata: 
The Gender Data Portal is more than just a database of sex-disaggregated data and gender statistics. Data sources include United Nations, UNESCAP, Eurosat, World Economic Forum, WHO, IMF, Institute for Democracy and Electoral Assistance, and more (World Bank). 

Variables: Multiple indicators representing gender differences by Country, Year. Indicators span assets, legal rights, education rights and completion, employment, life expectancy, GDP. 

Share of female STEM graduates: https://genderdata.worldbank.org/indicators/se-ter-grad-fe-zs/?fieldOfStudy=Science%2C%20Technology%2C%20Engineering%20and%20Mathematics%20%28STEM%29
Format: CSV
Metadata: 
For aggregate data, each economy is classified based on the classification of World Bank Group's fiscal year 2020 (July 1, 2019-June 30, 2020) (Worldbank)
Statistical concept and methodology: Percentage of female graduates by field of study in tertiary education is calculated by dividing the number of female graduates in a given field of education from tertiary education by the total number of graduates in the same field, and multiplying by 100. Data on education are collected by the UNESCO Institute for Statistics from official responses to its annual education survey. All the data are mapped to the International Standard Classification of Education (ISCED) to ensure the comparability of education programs at the international level. The current version was formally adopted by UNESCO Member States in 2011. The reference years reflect the school year for which the data are presented. In some countries the school year spans two calendar years (for example, from September 2010 to June 2011); in these cases the reference year refers to the year in which the school year ended (2011 in the example). Source: UNESCO Institute for Statistics (http://uis.unesco.org/). Data as of March 2020.
Variables: Share of graduates by field, female (%). Broken down by Country, Year. 

Project Questions:
In the coming years, are women in certain countries more likely to graduate with a STEM major than others? 
Target variable(s) from data set: ‘Share of STEM Graduates’, ‘Country Name’
Task type: prediction
What factor(s) influence women’s access to STEM fields?
Target variable(s) from data set: Feature(s) in prediction model
Task type: prediction
Can we expect the proportion of women entering STEM fields to grow in the future? If yes, what factors will influence this growth?
Target variable(s) from data set: ‘Share of STEM Graduates’, ‘Year’, ‘Country Name’
Task type: prediction

How to run the file: 
All the information for our sprint is in one notebook. Reading the CSV, cleaning the datasets, merging and 3 visualizations
Correlation Matrix
Box plots
Line plot

References:
- https://pandas.pydata.org/docs/reference/api/pandas.melt.html
- Lab 2 from EDA
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.pivot_table.html
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.astype.html
- https://genderdata.worldbank.org/resources/?tab=gender-data-portals

 Submission
Include your Jupyter Notebook/s in the repo
Add your dataset to your .gitignore if you are working on it in your local repo, but make sure to provide an exact link for us to download your dataset/s
Modify the second half of your README from Sprint 2 to include your project description, questions, etc. Here's a sample: Sprint3_README_Sample-1.md
Download Sprint3_README_Sample-1.md
Push everything to the same repo you had from Sprint 2 before Thursday, February 29th at 11:59 PM


NOTES:


Gender data:
https://genderdata.worldbank.org/

Share of female STEM graduates:
https://genderdata.worldbank.org/indicators/se-ter-grad-fe-zs/?fieldOfStudy=Science%2C%20Technology%2C%20Engineering%20and%20Mathematics%20%28STEM%29





