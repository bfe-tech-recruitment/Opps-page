# Opportunities Listing

## Add a posting

1. Create a new file in the `_posts` folder in this GitHub repository. Name it as `YYYY-MM-DD-somename.md`, replacing `YYYY-MM-DD` with the date of creation and `somename` as the title of the role (this will only show in the url so you can use shortcut). 

2. Copy and paste the following code:
```
---
title: "[Project] DevOps Unit Test Design"
smallprint: "Project Length: 6 hrs/week for 2-3 weeks. Experience Required: Medium."
summary: "some one-paragraph summary" # this will be visible on platforms like LinkedIn when sharing
categories: [Global, Technology]
---
``` 
Then,
- replace "\[Project\]" with "\[Role\]" or "\[Internship\]" if needed, and replacing "DevOps Unit Test Design" with the corresponding title.
- replace smallprint with some short info to display. It is recommended to specify Project Length / Commitment Level, and/or Experience Required / Difficulty Level here. Do not make it too long.
- replace summary with some one-paragraph information. Note that this will appear with the url when you share the post on social media, so write something succinct and compelling.
- replace categories with one or more of the following options so that filtering and similar opening recommendations can work properly. Always capitalise the words and keep the space in between.
    - Consulting, Finance Advisory, Legal Advisory, Technical Advisory, Communications, Startup Recruitment, Growth Partnerships, Internal Technology
    - Incubation, Outreach, Operations, Impact Research, Technology
    - Global, Cambridge, New York, Rotterdam, Singapore, Vancouver
  Note that you must include one word each from the last two categories for the role to appear under the corresponding pages. In general, try to use at least one phrase from each category if possible, and feel free to include those that may be relevant.
  
  For example, Technology and Incubation can be used together for a Technical Advisory role. This allows someone applying to other tech roles to see TA as a "similar opening", and vice versa.

3. For the actual content, copy the template from `_posts/_archived/YYYY-MM-DD-Template.md` and fill in the details. You can also use markdown to format the document, such as bolding texts. See [here](https://guides.github.com/features/mastering-markdown/) for a reference.

4. If you need to insert a photo, name it as `POSTNAME_NUM.EXT`, where `POSTNAME` is the name of the file (i.e. `YYYY-MM-DD-somename.md`) that you used before, `NUM` is the index of the image related to this post (starting from 1), and `EXT` is the image extension such as `jpg` or `png`. Then, upload the image under `/assets/img/`. Use it in your post by writing `![img](/assets/img/POSTNAME_NUM.EXT)`.

5. Once you are done, visit [this url](https://github.com/Bridges-for-Enterprise/Bridges-for-Enterprise.github.io/deployments/activity_log?environment=github-pages). If you see a new deployment that happened within the past few seconds, that means your changes have been updated, and you can click `View Deployment` to see the website live. 

6. *Why do I not see my changes despite successful deployment?* Your browser automatically caches the website if you have visited it before, and you have to either wait for the browser to cache the new copy again, or manually clear the cache if you want to see the changes immediately. If you are using Chrome, you can do this by right-clicking on the webpage and click "Inspect", which will open the developer's mode. Then, **right-click** on the refresh button, and click "empty cache and hard reload". Alternatively, you can just open your browser in incognito mode and visit the url.

## Edit file
Just navigate to the file in `_posts` and edit.
## Accidentally deleted some content
Don't worry. Use GitHub's [commit history](https://docs.github.com/en/github/committing-changes-to-your-project/differences-between-commit-views) functionality to view previous versions of the file and retrieve information from there.
## Remove a posting
Put your post into `_posts\archived`.
## Original template

[Here](https://docs.unbound.studio/guia-jekyll-helpdesk-theme/).
