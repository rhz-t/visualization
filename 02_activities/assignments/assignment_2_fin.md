# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
     
Good Example: Sea Turtle Sightings in Newfoundland and Labrador, Canada (Tableau Public)
https://public.tableau.com/app/profile/ikeda.tsutomu/viz/B2VBWEEK10SeaTurtleSightingsinNewfoundlandandLabradorCanada/1

Why I classified this visualization as good?
I classified this visualization as a good example of data visualization because it effectively communicates spatial and temporal patterns in sea turtle sightings while remaining clear, informative, and accessible. First, the map-based design is appropriate for the dataset because geographic location is central to understanding where sea turtle sightings occur. By plotting observations directly on a map of Newfoundland and Labrador, viewers can quickly identify clusters of sightings and understand their relationship to the coastline. Effective visualizations should match the visual format to the underlying data, and a geographic map is an intuitive choice for location-based information.
Second, the visualization demonstrates good visual hierarchy and simplicity. The map background is relatively uncluttered, allowing the data points to remain the primary focus. Colours and symbols are used consistently, making it easy for viewers to distinguish observations without being distracted by unnecessary decorative elements. This aligns with Tufte's principle of maximizing the data-to-ink ratio by reducing non-essential graphical features.
Third, the visualization supports user exploration through interactivity. Tableau allows users to zoom, filter, and inspect individual records, enabling deeper investigation of patterns within the data. Interactive features encourage engagement and allow users to answer their own questions about sea turtle distribution. This is particularly valuable because sea turtle sightings in Newfoundland and Labrador are relatively rare and geographically dispersed. The visualization helps reveal patterns that would be difficult to identify in a table of coordinates or records. The underlying dataset includes sightings, strandings, and entrapment records collected from Newfoundland and Labrador waters over many decades, making spatial visualization especially useful for understanding distribution patterns.
Overall, the visualization successfully communicates a conservation-related story using appropriate visual encodings, clear design choices, and interactive functionality.

How could this data visualization be improved?
Although the visualization is effective, several improvements could further strengthen it. First, adding annotations or explanatory text could help users understand important patterns in the data. For example, notes explaining why sightings are concentrated in certain coastal areas or seasons would provide valuable context. Leatherback sea turtles are commonly observed in Newfoundland and Labrador during summer and early fall while feeding on jellyfish, which could help explain spatial clusters shown on the map.
Second, accessibility could be improved by ensuring that all colours are distinguishable for users with colour-vision deficiencies. Providing a colour-blind friendly palette would make the visualization more inclusive and easier to interpret for a wider audience.
Third, adding summary statistics, such as total sightings by year or species, alongside the map would help users connect spatial patterns with broader temporal trends. Combining geographic and temporal information would strengthen the overall storytelling capacity of the visualization and provide additional insight into changes in sea turtle occurrence over time.

Bad Example: Pollution Pie Chart by Erin Otwell (Tableau Public)
https://public.tableau.com/app/profile/erin.otwell/viz/Pollutionpiechart-Tablet/PollutantPieChart-Tablet

Why I classified this visualization as bad?
I classified this visualization as a poor example of data visualization because the pie chart format makes it difficult to accurately compare the different pollution categories. While pie charts can be useful when displaying a small number of categories with large differences, they become less effective when viewers need to compare several similar proportions. Research on graphical perception suggests that humans are less accurate at comparing angles and areas than they are at comparing lengths along a common scale, such as in a bar chart.
First, the visualization relies on slices of a pie chart to communicate differences between pollutant categories. Because viewers must compare angles and areas rather than aligned bars, it is difficult to determine the exact magnitude of differences between categories. Tableau's own visualization guidance notes that pie charts are best suited for only a few categories with clear differences and are not ideal when users need to analyze precise values.
Second, the visualization limits the ability to rank categories quickly. In a bar chart, categories can be ordered from largest to smallest, allowing viewers to identify trends immediately. In contrast, pie charts require viewers to visually estimate slice sizes, increasing cognitive effort and reducing interpretability. Effective visualizations should minimize the mental effort required to extract meaning from the data.
Third, the visualization focuses on proportions while providing little context regarding the absolute magnitude of pollution. A category may represent a large percentage of the total but still correspond to a relatively small quantity. Without additional context, viewers may misinterpret the significance of the data.
Overall, the chart communicates basic proportions but does not support detailed comparison, accurate interpretation, or efficient understanding of pollution patterns.

How could this data visualization be improved?
First, the pie chart could be replaced with a horizontal bar chart. Bar charts allow viewers to compare values using a common baseline, which improves accuracy and makes differences between categories easier to perceive. Research by Cleveland and McGill found that position along a common scale is one of the most effective visual encodings for quantitative data.
Second, categories should be ordered from largest to smallest value. This would help viewers quickly identify the major contributors to pollution and support more efficient interpretation.
Third, the visualization could include exact values, percentages, and explanatory annotations. Adding contextual information would strengthen the story being communicated and help users understand the practical significance of each pollutant category.
Finally, a colour-blind friendly palette and clearer labels could improve accessibility and ensure the visualization can be interpreted by a wider audience.

References: 
Few S. Information Dashboard Design: Displaying Data for At-a-Glance Monitoring. 2nd ed. Burlingame (CA): Analytics Press; 2013.
Knaflic CN. Storytelling with Data: A Data Visualization Guide for Business Professionals. Hoboken (NJ): John Wiley & Sons; 2015.

- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
