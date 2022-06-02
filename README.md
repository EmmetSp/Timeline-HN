Timeline-HN is a repository hosting all files needed to run a branched off TimelineJS3. In this project you fill find 

# How do I use it?
Timeline-HN is building upon [Timeline.JS](https://timeline.knightlab.com/), it holds a CSS file that, when appended onto a timeline URL, it changes the theme to a more legibal color scheme. 

To get access to Event Types, you must add a column labeled "Event Types" matched with caps.

# Example (Javascript)
When putting TimelineJS3 into your website, you will add these lines of code to your javascript: 


    <!-- Creating a  -->

    <!-- First, a link to the timeline stylesheet.-->
    <link title="timeline-styles" rel="stylesheet" href="https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN/timeline.css">

    <!-- Second, download the javascript library -->
    <script src="https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN/timeline.js"></script>

    <div id='timeline-embed' style="width: 100%; height: 400px"></div>

    <!-- Finally, build the Timeline -->
    <script type="text/javascript">
        timeline = new TL.Timeline('timeline-embed',
        '');
    </script>``

    ``https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN@master/timeline.js``
    ``https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN@master/timeline.css``
    ``https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN@master/embed.html``
    
 # Example (Iframe)
 
 ``<iframe src="https://emmetsp.github.io/Timeline-HN/src/embed/embed.html?soutce=https://cdn.jsdelivr.net/gh/EmmetSp/Timeline-HN@latest/events.json?></iframe>
