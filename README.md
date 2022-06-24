Timeline-HN is a repository hosting all files needed to run a branched off TimelineJS3. Continue reading this README.md to learn how to use the project, and watch the included video for a step-by-step on how to create your Timeline JSON files.

# How do I use it?
Timeline-HN is building upon [Timeline.JS](https://timeline.knightlab.com/), it holds a CSS file that, when appended onto a timeline URL, changes the theme to a more legibal color scheme. 

## Creating Events

To create events for your timeline, take your Timeline Spreadsheet and use the Export Sheet Data export tool to transfer your spreadsheet to json. There is a tutorial on how to do this at https://github.com/Emmetion/sheets-to-json

# Example (Javascript)
When putting TimelineJS3 into your website, you will add these lines of code to your javascript: 


    <!-- Creating a Timeline javascript element-->

    <!-- First, a link to the timeline stylesheet.-->
    <link title="timeline-styles" rel="stylesheet" href="https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN/timeline.css">

    <!-- Second, download the javascript library -->
    <script src="https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN/timeline.js"></script>

    <div id='timeline-embed' style="width: 100%; height: 400px"></div>

    <!-- Finally, build the Timeline -->
    <script type="text/javascript">
        timeline = new TL.Timeline('timeline-embed',
        'source-to-events');
    </script>``

    ``https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN@master/timeline.js``
    ``https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN@master/timeline.css``
    ``https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN@master/embed.html``
    
 # Example (Iframe)
 Hosting an iframe on your website is the easiest way to create a timeline in your webpage. Use this example below. Changing the source URL to your events JSON file will update the timeline with those events.
 ``<iframe src="https://emmetion.github.io/Timeline-HN/src/embed/embed.html?source=https://emmetion.github.ioTimeline-HN/timelines/srp-events.json' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>`` <-- a single quote bugged this entire embed.
 
 ``<iframe src="https://emmetion.github.io/Timeline-HN/src/embed/embed.html?source=https://emmetion.github.io/Timeline-HN/timelines/example-events.json" width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>`` <-- working one
