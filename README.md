# Project 2: Analyzing Art Data
*Due December 2, 2019 @ 11:59pm through GitHub Classroom*

Projects may be submitted up to 3 days late, with a 10% penalty per day

<h1>Overview: </h1>
Visual art provides a rich source of data. We can study the composition of a work of art (e.g., the structure, contents, colors, sizes, etc) as well as more qualitative components of the work (e.g., the emotions it allows us to feel, our preference for a piece, etc.). While many components of composition can be extracted using computer vision, others require human expertise and experience to measure.
<br/>

Mohammad & Kiritchenko ran a large scale study to understand the emotions and preferences viewers have for different pieces of art using the WikiArt dataset (https://www.wikiart.org/). They asked people to provide different ratings about their subjective experiences with 4,105 pieces in this corpus and collected those experiences through a series of measures. More details of their experiment are at http://saifmohammad.com/WebPages/wikiartemotions.html.
<br/>

<h1>Our Goal</h1>
Our goal for this project was to create visualizations that illustrate interesting features of the dataset. We chose to go with option 1:

1. Create at least two interactive visualizations that let users explore the data in interesting ways.

<h2>
     CATEGORICAL SECTION:
</h2>
<h3>
     Folder 1: Angus_Keaton
</h3>
<h4>
     Authors:
</h4>
<ul>
     <li>Angus McDonald </li>
     <li>Keaton Whitehead</li>
</ul>
<h4>Sources: </h4>
<ul>
     <li>https://getbootstrap.com/docs/4.4/getting-started/introduction/</li>
     <li>https://colorswall.com/palette/3/</li>
     <li>http://bl.ocks.org/wayneminton/a12b563819b04a3555aa</li>
</ul>
<p>
     Data preprocessing/design: To take the data in from the Excel file, we process the data through a series of organizational steps: 1. Take in all desires data attributes row-by-row and store in an array of objects 2. Group the array of objects by artist name (the category is therefore the artists) 3. For each artist, calculate the average of six emotions: fear, anger, happiness, sadness, disgust, anticipation and store in an array of objects 4. Use a separate array ordered the same way as the array grouped by artists and format it to use for creating pie charts 5. With access to each of these arrays, displaying desires data became conveniently easy and simple, along with the ability to create the pie chart based on the user desired artist
</p>
<h4>
     Design Process: 
</h4>
     The back-end organization was decided upon during development based off what seemed to be most logical and simple. A new array was created for each step in the data processing so that the information could be utilized later on if needed or desired.

<h4>
     Above and Beyond:
</h4>
     Set up website with multiple interactive components that allows users to search artists, view their bios, click through their visualizations....

<h4>
     Team Roles:
</h4>
<ul>
     <li>Angus MacDonald: Back end developer for categorical visualization, processed data and set up code for the pie chart </li>
     <li>Keaton Whitehead: Front end developer </li>
<ul>
<h3>How to operate:</h3>
<ul>
     <li>Download code</li>
     <li>Set up local python http server</li>
     <li>Open the index.html file</li>
     <li>Once prompted with the prompt you can:</li>
     <ul>
          <li>Just submit the given artist name</li>
          <li>Enter an artist name spelled EXACTLY how it is in the data set</li>
     </ul>
     <li>You will be brought to a webpage containing all of the artworks from that artist along with a pie chart at the very bottom</li>
     <li>The pie chart at the bottom is calculated ratios of the average feelings a surveyed audience felt when looking at the given photos above</li>
     <li>Feel free to click on the buttons to navigate you to more information about the artist or painting</li>
     <li>Once you are satisfied with you browsing feel free to hit the button at the bottom to refresh the page so you can enter another artist or explore another randomly selected artist from the dataset</li>
</ul>



<h2>Folder 2: Jihoon_Anthony</h2>
<h3>Authors: Jihoon Jang, Anthony Camacci</h3>
<p>
     The purpose of the fear factor visualization is to identify the artist's work(s) who has created the
     emotion fear to the viewer. The visualization allows you to identify artists whose work creates
     the most fear and see the art that they have made. The user is allowed to select one or more
     artists from the bubble chart. That selection will cause the 3 other visualizations to be updated
     accordingly. This includes the list of artists and a picture of their art, a donut chart that breaks
     down their work by style of art, and the bar chart that has a chronological chart of the fear factor
     for those selected artists over time. The project is run by supplying the fear factor dashboard.
     The interaction is done on the dashboard titled which artists have scared us the most.
</p>
<p>
     We decided to focus on one emotion which is fear, because of how powerful of an emotion it is.
     We first wanted to get rid of artists whose work did not create fear. We created a calculated field
     to filter out feared work. After that we made it so that it would only show fear scores that were
     greater than 0 and implemented this into all of the visualizations. This also included filtering the
     artist into every visualization. For the first visualization We decided to build would show the
     biggest contributors to fear and be able to select them, with the biggest contributors being in the
     middle of the bubble chart and have the largest bubbles. This shows the artist and their fear
     factor score when the user hovers over them. The score is calculated by summing up the
     responses. After we made the bubble chart, we made it so that the other visualizations would
     change based on the artist(s) that were selected. Next we included a visualization that would
     include a list of their art and a url that the user can click on and view. This way the user can
     experience the art by looking at one or more of the works of art by the artist(s) that they have
     selected. We also provided a donut chart that broke down the art by style. We found this to be
     an interesting way to identify what style of art each painting fell into, which most of it seemed to
     fall into modern art. Finally, we created a chart to show when the art was created because there
     is a large span of time when art was created.
</p>
<p>
     The reason we chose these representations is because we found a way for the user to interact
     with it in a fun way and allows the user to look into the art further. It also provides different levels
     of information from detailed, categorical and quantitative. They are all related together and this
     allows them to tell more information because they build off of one another. We put these
     visualizations together to create an interactive dashboard with the art data.
     For above and beyond, not only did we have more than 2 visualizations, but we had
     representations that went beyond the typical bar chart and and scatterplot. We incorporated
     consistency into our visualizations by using the same data for each one. We integrated imagery
     by being able to click on the image urls in the dashboard.
</p>
