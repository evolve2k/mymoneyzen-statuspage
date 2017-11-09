Visit this site at https://evolve2k.github.io/mymoneyzen-statuspage/


How to open a new issue
-----------------------
1. Visit the project statuspage repo

    https://github.com/evolve2k/mymoneyzen-statuspage/issues

2. Create a new issue
Add a label for the relevant service affected: probably 'mymoneyzen.com'
Add a label for the severity eg 'Major Outage', 'Degraded Performance' etc.

Create a clear subject as the title
Explain in emotionally neutral highly professional terms what happened and what action you are currently taking. Avoid providing an estimated completion time (probably just do this privatley to the site owners in private channels)

3. Send an update request to statuspage
The free account requires this extra step.
From the terminal for the project.

statuspage update --name=mymoneyzen-statuspage --token=TOKENGOESHERE

How to update the status
------------------------
1. Leave a new comment in the issue

2. Send an update request to statuspage

statuspage update --name=mymoneyzen-statuspage --token=TOKENGOESHERE

How to close the issue
----------------------
1. Add a final updated status as a comment on the issue
2. Select to close the issue
3. Send an updated request to statuspage