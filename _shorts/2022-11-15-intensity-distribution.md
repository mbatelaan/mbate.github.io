---
layout: post
title:  "Intensity distributions"
date:   2022-11-15 00:00:00
tags: [cycling, health, data]
---

Strava has a neat little API which allows you to access data on all your activities in an easy manner. Since I have been reading a lot about the science behind endurance training and metabolic fitness recently, I thought this would be a good opportunity to see whethere I could tease some information from my own activity data. [Here is a decent guide](https://medium.com/analytics-vidhya/accessing-user-data-via-the-strava-api-using-stravalib-d5bee7fdde17) on how to set up the API in Python.

Firstly I scraped the heartrate data from all of my activities in the year until this November [^1]. Then, combining these heart rate values I calculated a histogram of the them, setting the bin size to 2bpm. The result is shown below.

![histogram](/docs/intensity_distribution/last_year_hr_hist.png)
Looking at this plot I would say that my training is definitely not polarized, I spend a lot of time in the middle region around 140 bpm. However, these activitiesare a mix of running and cycling, and there is a difference between the two sports in terms of intensity profile.
In the next figure I split the histogram into those two sports, we can see that the distribution for cycling is somewhat polarized, this is easily explained by the races I do, they contribute most of the high intensity peak aroun 180 bpm.
![histogram2](/docs/intensity_distribution/last_year_hr_hist_split.png)
My running distribution is not polarized at all but I also barely do any high intensity running.
Overall, I think my training could benefit from some more polarization in the intensity distributions.
For me this would mainly involve doing more activities at a low intensity (120-140 bpm) and the racing plus an occasional HIT session will provide the high intensity part of the polarization.

Another interesting plot I made shows the average heart rate of each activity on a time scale. The size of the points is proportional to the lenghth of the activity. This is also a good way to visualize the polarization of my training, however it will be a bit skewed for longer rides due to the average washing out some details.
![figure](/docs/intensity_distribution/last_year_avg_hr.png)

[^1]: The Strava API is rate-limited to 100 accesses per 15 minutes and 1000 per day, so I broke this up into chunks and ran them spaced out.