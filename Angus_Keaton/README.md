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
