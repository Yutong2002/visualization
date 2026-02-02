# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Good Visualization source: “What is a good SAT score?” is a scatter plot on Tableau Public https://public.tableau.com/app/profile/mehras/viz/WhatisagoodSATscore/WhatisagoodSATscore

      Reason: 

      1. The author used an appropriate Chart Type. Scatter plot is used to display SAT results across dimensions like by region, demographic, or subscore, which utilized spatial position to show relationships.Scatter plots are excellent for showing correlations and distributions without misleading ordering or aggregation issues.This aligns with best-practice guidance that chart choice should match analytical intent

      2.The visualization uses axes, scale, and color encoding in a manner that supports interpretation rather than distracting from it. The axes are clearly defined, providing an explicit frame of reference for what constitutes low, average, and high SAT scores. Color is used to differentiate meaningful subgroups, enabling viewers to compare categories without overwhelming the display. Color is properly used to encode categorical information in interpretable and consistent manner.

      3. A Good visualization should always guides interpretation, not just displays data. This viz supports insight, such as which scores are above average or how scores vary among group. Effective narrative structure helps viewers interpret the key message effectively.  ￼


      Bad Visualization source: CANADA’s Exposure to U.S. Tariffs — A dashboard hosted on Tableau Public.https://public.tableau.com/app/profile/shangruff/viz/CANADAsEXPOSURETOU_S_TARIFFS/CANADAsEXPOSURETOU_S_TARIFFS

      Reason: 
      1. The visualiation is lack of clear story or Focus. A good visualization should guide the viewer to the key insights or decisions a user can make with the data. However, this visualization only presents a collection of charts without a clear narrative or logical flow, leaving the viewer to figure out meaning on their own. 

      2.The other issue of the visualization is the information Overload and Poor Visual Hierarchy. It included multiple components, charts, and metrics into one view without a clear hierarchy. Without visual cues that signal importance, viwers can’t quickly discern what matters most. Too many competing elements increase cognitive load and reduce clarity. 

      3. The visualization also has inconsistent or distracting design choices. The visualization contains mix chart types, colors, and fonts in inconsistent ways that don’t support interpretation. The color choices alsp does not align with meaning (e.g., bright colors that don’t correspond to categories) and legends/labels are unclear/ missing, which made interpretation difficult.
      
      ```
    - How could this data visualization have been improved?  
      ```
      For the bad visualization: 
      1. Establish a Clear Analytical Question and Narrative: The current visualization presents multiple charts and metrics without clearly answering a single, focused question. For instance, Which sectors are most exposed to tariffs? How large is the impact relative to others? I will define one primary message for the dashboard and use a headline or annotation to explicitly state the key takeaway as “Manufacturing accounts for the majority of Canada’s tariff exposure”; I will also organize charts to support a top-down narrative flow of overview to comparison to data detail.This aligns with narrative visualization principles, which emphasize guiding viewers toward interpretation rather than leaving meaning implicit.

      2. Reduce Visual Clutter and Cognitive Load: I will remove redundant charts or metrics that do not directly support the main message.Limit the number of colors, chart types, and annotations used. Increase whitespace to separate conceptual sections.

      3.Improve Visual Hierarchy and Layout:As currently, all components appear visually similar in size and prominence, making it unclear which information is most important. I suggest using size, placement, and contrast to create hierarchy: Most important chart should be placed center. Supporting charts smaller and secondary.Use consistent alignment and grouping to signal relationships between visuals.

      4. Improve Color Usage and Consistency: To increase the efficiency of using colors in the current visualizaiton, different color should only be used when it encodes meaning for instance, representing different sector, risk level. I will also apply a limited, consistent color palette to ensure sufficient contrast and visibility.

      ```
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
* Submission Due Date: `23:59 - 01/26/2026`
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
