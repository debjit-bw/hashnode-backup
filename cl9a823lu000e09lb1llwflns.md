# Incentivizing them to give us their data

# First things first

This is going to be a short update post. An in-depth analysis is coming up soon.

# The problem with our solution

Our generation is impatient, and also eerily privacy focused. Pretty unrelated, I know. But hear me out.

In the last post, I described how we want to gain access to several data points about a person and try to understand the trendlines, with respect to their moods.

## Our target audience

We could have tried to do it for everyone, but for that we would need opinions of many other people as our perspective and outlook will definitely be different than of a 50 year old person. That's why we are narrowing it down to just to teens and young adults. That's because we personally relate to them, and we understand their unique concerns and issues.

### Quick Stimulus

The first problem that arises with this segment of society is the acutely impaired attention span. We want the world and it's physical stimuli to replicate that of social media, giving us instant hits of happiness. That's why we can't expect them to take time to fill a detailed questionnaire that would do them no benefit and that doesn't align with their self-interest.

### Beautiful Data

Second is the privacy issues that surround it. Why do you give YouTube data about your search history? Because you want better recommendations. Google? Better ads. Instagram? Better reels. Looking at all these, fair to say that people wish to give data only when they can get something out of it. Specifically, they want to be served relevant information with the data they hand over.

This means that whatever we do, if we want people to give us their data, we need to give them back something inferred from their data.

# Our sources of data

![DALL·E 2022-10-15 23.26.39 - a network of small white datapoints with a grey background, in one place the points are brushed aside and there's a silhouette of a sad person.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665856622299/N6Rib9D_P.png align="left")

We have to make a toy. In order for people to come forward and give us their data, we need to make something fun, we need to analyze their data and send them a report about what we figured out from it, much like [Spotify Wrapped](https://www.spotify.com/us/wrapped/). And it needs to be data-source that people usually consider fun.

For that, we set out to make a list of data we think (being members of our target market) that can act as a proxy of our mood. Requirements: fun and unconventional. These are what we got till now:

* Spotify listening history
* Food order history
* Social Media usage hours
* Fitness tracker data
* More conventional sources like web search and stream history

These have been chosen because we felt our responses in these domains change when our mood does. For example, I start listening to specific categories of songs when I'm blue. Similarly, a team member said they start neglecting their fitness and activity when they are going through somethings. Another member started describing how they start ordering excessive amounts of desserts during their bad days.

Detecting hard changes in such data can lead to many false positives. We still have to figure out how to combine some or all of this data to give coherent results. What score should we observe the trends of. This list hasn't been finalized. It's a work in progress. But right now, we can say from this we can somewhat understand what our fellow participant is feeling.

# What next?

We aren't going to dive into all of them at once. We are going to start with Spotify listening history, see how we can extract useful information from the songs our users listened to. We need to think of how to derive insights from them which are fun enough for the user to see it, as well as helps us get our study done. How to gamify the system for mutual benefit.

The next in this series will most probably be a technical post on how we use Spotify's API and audio features to determine someone's mood. Keep checking for more!