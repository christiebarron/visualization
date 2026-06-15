# Data Visualization

## Assignment 2: Good and Bad Data Visualization

#### Good Visualization

The good visualization I used is an elegant dumbell plot shown in the python graph gallery:  https://python-graph-gallery.com/web-lollipop-plot-with-python-mario-kart-64-world-records/. https://github.com/holtzy/The-Python-Graph-Gallery/blob/master/static/graph/web-lollipop-plot-with-python-mario-kart-64-world-records.png?raw=true


    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
        The aesthetics are well-organized. "Chart junk" is mainly removed. Heavy gridlines, boxy frames, and unnecessary axis ticks, are removed. This aligns with Tuft's data-to-ink ratio idea. The visualization uses custom nintendo 64 like fonts. It also uses intentional color gradients (orange to show time saved, blue for the year).

        Using a dumbbell plot to connect the very first record to the newest one shows how times have improved over 24 years. Also, the detailed subtitle explains the most interesting takeaways (like massive shortcut discoveries) helping guide readers to the key findings.

        Human brains are great at judging distances along a horizontal line. Mapping the times to the x-axis makes the data easy to process readable. The long connecting lines between the first and most recent records clearly show how improvements have been made.

        However, the data is somewhat dense. Juggling two different color legends while reading the chart can be challenging for readers.

      ```
    - How could this data visualization have been improved?  
      ```
        Even though the Mario Kart 64 chart is great, it could be improved. The complexity could be improved. Right now, the reader has to juggle two entirely different color scales: an orange gradient showing how much time was saved, and a blue gradient showing what year the record was set. Having to constantly dart your eyes back and forth between the chart and two separate legends is pretty exhausting. A quick fix would be to just drop the blue year gradient altogether. If the main story is about time saves from shortcuts, we could keep the orange lines but maybe just use different shapes (like a circle versus a diamond) for old versus new records, or just drop a subtle text label for the year on the important ones.

        Another thing that could make an improvement is how the tracks are sorted. Right now, they’re ordered top-to-bottom by the absolute fastest completion time. I think the main point of interest in this data is the noteworthy shortcuts on tracks like Wario Stadium or Rainbow Road. If the chart were sorted by the size of the time gap instead—putting the longest orange lines right at the top—the impact of those shortcuts would hit you immediately without having to manually scan up and down the whole image.

        Also, because it's just a static picture, there are no tooltips or interactivity. Turning this into an interactive web graphic would allow for showing more granular information, select relevant filters, etc. The minimalist look could be maintained, but empowers users to hover over the dots to pop up a little tooltip showing the exact player name, date, and time down to the millisecond.

        Finally, just a quick accessibility tweak: relying purely on shades of orange to show the size of the time gap can be tough for people with color vision issues, or if the chart ever gets printed in black and white. If the lines actually got physically thicker as the time gap got larger it would be  easier for everyone to read at a glance without compromising the visualization.

        Also, ading images of each stadium to the right of the left of the stadium names might be a fun add-on. But would admittedly add more clutter to the chart.






      
      ```

#### Bad Visualization
- Radial chart: https://datavizproject.com/data-type/radical-line-graph/ and https://dribbble.com/shots/1646404-Dashboard-data-charts/attachments/258171 

    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      The radial graph I chose (shown in the bottom left corner of the second link and bottom left corner of the first link) is a radial chart to show the airport altitude above sea level (continuous variable) by airport in question. 

      The main concern with this plot is the lack of a common straight baseline point of comparison. In the image, the baseline is in the centre of the chart, and the distance away from the center of the chart shows the continuous measure. Unfortunately, the grid is circular. The reader has to manually rotate the 'grid' to compare categories. Comparing categories far away from each other is difficult wiith this chart. This is amplified by the inclusion of 12 categories. This would be more managable with only 14 categories.

      Additionally, the labels for each category are three letter acronyms that aren't described elsewhere. Perhaps the readers will have that knowledge, but using airport names instead of the three letter acronym may make it more intuitive to readers.

      While likely stylistic given its a dashboard, the lack of labels on the axis (height) prevents a clear understanding of what each value represents without using the hover tooltip.

      It is also unclear why the order of categories was chosen. This makes finding the two highest categories, or two lowest categories, more difficult than necessary. Sorting the categories by altitude would make it much easier to interpret differences between categories.


      ```
    - How could this data visualization have been improved?  
      ```
      First, changing the chart from radial to something with a comparable baseline would make it much clearer. The most elegant plot, using Tufte's principles of data-to-ink ratio, would probably be a cleaveland dot plot with airport as the X axis and meters (or kilometers) above sea level as the y axis; circles would be used as a point to show. A lollipop chart would work equally well, but would keep a vertical line to show the distance from sea level. 
      
      If airports from multiple countries or continents occurred, it might be interesting to group the results by those, ordering them by country/continent and adding vertical lines underneath the points to denote the mean or median for the higher order group (country/continent). Ideally, a clear title, clear subtitle, and clear x and y labels would be provided on the figure. Point labels would be beneficial if possible (perhaps the numbers could be put inside the dots). If point labels are too crowded, y axis gridlines would be helpful to clearly show values for each airport. 

      The airport labels may benefit from changing from three letter acronyms to a larger airport name. To adequately fit on the graph, these labels would likely need to be rorated to 45 degrees (if category is kept on the X axis). Alternatively, flipping the axes so have the labels on the Y axis may make them easier to read (the x axis would become altitude instead).

      The colour palette within the graph worked well, so that could be maintained.






      
      ```


### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  


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
- [x] Create a branch called `assignment-2`.
- [x] Ensure that the repository is public.
- [x] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [x] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
