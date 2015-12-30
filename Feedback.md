#FEEDBACK

### v1

	ucaiadoForum Mentor32m
	Hi @t0mkaka,

	You chose an interesting way to encode the all this information. This way I can easily see what social class and gender most survived. On another side, I'm not sure about the age. Maybe if you include some filters will make it clear. Also, as a suggestion, you could create a dashboard with other charts summarizing the information filtered.

	Uirá

	Jay TeguhYesterday 11:57 PM


	 
	That first class tickets are expensive for a reason!﻿

	Jay TeguhYesterday 11:59 PM


	 
	 
	It's a bit hard to differentiate the ages, possible to use distribution histogram for them perhaps?﻿

	Marcin Zadroga12:54 AM


	 
	 
	In my opinion, age is not readable... Another thing, have you considered to take into account the PARCH or SIBSP variables?﻿

	shmuel naaman1:04 AM


	 
	 
	I think that you could use one axis for the continues feature (age) that will be more clear than the size. That will also allow you to use a chart type that will reduce the overplotting ( box plot?, lil histograms ) . 
	﻿
	Read more

	Matthew Versaggi2:43 AM



	Nice work! ﻿


	===========================================================================
	Feedback for v2
	===========================================================================

	michael_807478Forum Mentor5h
Hi t0mkaka,

This is easier for me to interpret and I think it is an improvement. Here are my thoughts.

I think your original choice of color to represent passengers that did not survive, grey, was actually better than orange. It is more contrasting and more readily associated with its meaning which is, after all, death.

I think your choice of splitting out the passenger classes into the further subdivision of age is technically impressive and more easily interpreted. It also makes the age-size mapping largely redundant, no? Even confusing when it is left in concurrently with the location mapping. Why not just drop it? You will need a legend on the age subdivisions but I think it would be worth it.

Now, I am still wondering about how many people are in data set and how many people each circle represents. At the very least the mapping should be in a legend somewhere on the chart, no?

I think if we go back to first principles and ask what are we really trying to convey with this chart I think that the answer would be the probability of surviving given a passenger's age and class. If so, the proportion of survives in each subclass of the data is more important than the absolute number, no? What about horizontal bar graphs? Position is always the strongest way to convey information. Why not mapping the probability of survival within each class-age subclass of the data to the length of the bar on the x-axis? If you still wanted to convey the absolute numbers within each subdivision of the data you could map that to the 'width' of the bars (their height in this case, since they are lying on their side)?

Just my thoughts. I think you have demonstrated good technical mastery of the subject with this visualization.

Good luck. Please post if you decide to make any more changes. I would love to see them.





Sheng_KungUdacity Coach2h    t0mkaka
I'm not sure that overlapping has been completely removed from the plot, since I see plenty of points where there are concentric green circles on orange or vice versa. The main assumption that someone looking at this plot will make is that each dot represents a single person, and that the persons in each passenger class-gender group are sorted by age in rows. However, I see that there are places where larger circles are to the left of smaller circles, and that there are different levels of opacity and gaps between circles. Clarity of how individuals are distributed by age will need to be refined a bit further from where it is now.

Otherwise, the visualization is coming together quite well. The increased structure in the arrangement of points makes it clear that there is a large association between survivability and all three of your features plotted: passenger class, gender, and age. Once you've figured out a good way to organize or represent the number of individuals, you should be well on your way towards a project submission.



==============================================================
google plus feedback
==============================================================
yvonne wambui's profile photo
yvonne wambui

Hi Ashutosh , this is an improvement. I have questions i wish to ask.
Is there a different way you can represent the ages, maybe something very distinct like different shapes? 
Also on the legend for ages, are the ages  ranges or actual age?
8h
shmuel naaman's profile photo
shmuel naaman
Since age is already represented by the position of the circle, Do you really want to represent it also by the size? In addition, the overplotting make it difficult to appreciate the distribution of the ages. 
