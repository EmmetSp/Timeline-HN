# Timeline-HN

Timeline-HN is a repository hosting all files needed to run a branched off TimelineJS3. In this project you fill find 

### How do I use it?
Timeline-HN is building upon [Timeline.JS](https://timeline.knightlab.com/), it holds a CSS file that, when appended onto a timeline URL, it changes the theme to a more legibal color scheme. 

### Example
When putting TimelineJS3 into your website, you will add these lines of code to your javascript: 
``
        <link title="timeline-styles" rel="stylesheet" 
              href="https://cdn.knightlab.com/libs/timeline3/latest/css/timeline.css">

        <!-- 2 -->
        <script src="https://cdn.knightlab.com/libs/timeline3/latest/js/timeline.js"></script>

        <div id='timeline-embed' style="width: 100%; height: 600px"></div>

        <!-- 3 -->
        <script type="text/javascript">
            timeline = new TL.Timeline('timeline-embed',
            '');
        </script>
    
``