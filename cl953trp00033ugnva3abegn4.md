# Engineering a way out of depression

# What is it about?

We have this course called Human Geography and Societal Needs, where we have to identify a problem in society and come up with a solution using our engineering domain knowledge.

# Brain haze

When our team got down to decide which problem domain to tackle, we initially decided to focus on some marginalized section of society. We couldn't settle on one particular issue, it seemed either too generalized, or something that is very difficult to be solved by engineering. Most societal issues require intervention from people with a humanities background, and changing the mentality of masses takes time.

![DALL·E 2022-10-11 16.11.40 - abstract image of brain haze with a capsule spewing fumes and a disturbing shadow of a person in the background.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665484909984/iegsWEoeG.png align="left")

# Why mental health?

The reason is very personal, tbh.  Speaking of mentality, a teammate suggested how about we do a project on mental health. At first, it seemed extremely off-topic, because mental health seems to fall squarely within the bounds of psychology and medicine.

But that's the problem, it is considered so far outside the technology domain that we don't even try to think about engineering solutions. But we like to innovate. So we took on this problem, it was a personal challenge, to come up with a useful and easy-to-use way of leveraging technology in the domain of mental health. We have friends, both on campus and off, who have struggled with depression, we wanted to help. This was our means to.

# So what are we gonna do?

We don't know. Currently it's all a haze. And this is intended. Instead of using a technology or a known piece of knowledge and asking which problem can it solve, I think it's way more innovative to start with a problem domain and think how to solve it.

One problem we found is the detection. Once depression is detected, it's often very late. Because once it is detected, we have a proper protocol to handle it, visits to a clinical psychiatrist, medication, etc. But the slip into depression isn't overnight. It happens slowly and gradually over a very long period of time.

What if we could make something to detect this fall into the grey void. Some mechanism that can us, or the user can use to see their behavioral trendlines.

# Probing further

> Do you ever look at someone and wonder, what's going on inside their head?

~ Joy, Inside Out

![DALL·E 2022-10-11 17.00.05 - a network of small white datapoints with a grey background, in one place the points are brushed aside and there's a silhouette of a sad person.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665487821252/cCtY0HrGV.png align="left")

If your close friend starts behaving abnormally, it's pretty obvious and noticeable. That's because you know them. Since you are aware of their baseline, it's easy to see when they divert from it. What if we can make something of this sort.

An observer, quietly noting down your daily activities, how you behave online and offline, present through all of your devices.

This idea sounds good. Given a continuous stream of datapoints of your behavior, we can start to analyze the data to see when you are deviating.

It's an interesting problem from an engineering perspective, what data points to collect, how to set a baseline, when do we say someone undergoing a long term change, how do we know it's not just a phase.

From a social problem, it opens up issues about potential breach of privacy. Why would anyone want to give such intimate data about themselves to us? It's creepy. Potential solutions involve:

* Using only a subset of signals or datapoints, which the user is willing to give, and then extrapolating on that to obtain the latent data.
* Use federated learning so that models are trained on device and the learnt parameters are uploaded to the cloud. This way, a user's data never leaves their device and there's no way to link learnt parameters to individual users.

There has to be other solutions too, but there's a lot of things to figure out. A lot of brainstorming is pending. We need to solve several problems encompassing technology, society, economics and psychology. This is a work in progress.

I'll keep things updated in upcoming posts in the same series.