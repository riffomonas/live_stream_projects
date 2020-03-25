---
layout: post
title: Trying to guess a person's age from their name
comments: true
blurb: "Hi, my name is Patrick. Based on that do you think you can figure out how old I am?"
---
<!--
<div style="float:right;width:45%;margin:10px 10px;padding:25px;background-color:#EEE;">
	<h4 style="color: #d64828;">Schedule</h4>
	<ol class="tutorials"  style="padding-left:20px;margin:0px;">
		<li>Monday, July 16: <a href="https://github.com/pschloss/baseball_wl_model_analysis/tree/c52937931f82712fee1ccd22af784bd94f61daa5">Validating 538's ELO model</a><a href="https://youtu.be/4gJ9qKEIYzA"><i class="fab fa-youtube"></i></a></li>
		<li>Tuesday, July 17: <a href="https://github.com/pschloss/baseball_wl_model_analysis/tree/916f252497c3f3bef216fe60d6a4d45248217ab6">Validating the winning probability model</a><a href="https://youtu.be/Dc-79fVLnkk"><i class="fab fa-youtube"></i></a></li>
		<li>Wednesday, July 18: <a href="https://github.com/pschloss/baseball_wl_model_analysis/tree/6222c49c1449a7b7055cbdccbe9bde66621d5587">Validating the moneyline model</a><a href="https://youtu.be/BaTGQVH7D50"><i class="fab fa-youtube"></i></a></li>
		<li>Thursday, July 19: <a href="https://github.com/pschloss/baseball_wl_model_analysis/tree/ace6e0ae9cc34ea18ae20345ff44060123ce14b8">How much money will we make by betting on the favorites?</a><a href="https://youtu.be/Ytzb956enO8"><i class="fab fa-youtube"></i></a></li>
	</ol>
</div> -->

Some names seem to be more associated with a time period than others. I can't tell you how many Sarah's I know between the ages of 25 and 45. Everyone seems to have a great-aunt Helen or Ruth that grew up in the Great Depression. Are these anecdotes or do the numbers back up these observations? The folks at Five Thirty Eight asked this question a few years ago - [based on a person's name, can we predict their age?](https://fivethirtyeight.com/features/how-to-tell-someones-age-when-all-you-know-is-her-name/).

When I read that article, I was left with a few questions.

* Can I replicate the analysis that was done in the article?
* I like to think that my wife and I selected "old-fashion" names for our kids - Mary, Patrick, Joseph, John, Ruth, Jacob, Peter, Martha (yes, we have a big N). How old-fashion are they, really?
* If I wanted to do a better job of picking names that were unique to the 1910s, what would be good choices?
* Can I generalize their analysis for any person or for their entire household?

I've worked with this data previously in a tutorial to [teach people how to use GNU Make to automate data analysis pipelines](http://www.riffomonas.org/reproducible_research/make/#1) (see the [video here](https://youtu.be/eWHE2RIGrWo)). That analysis was customized to my family and was done using so-called "base R". I'd like to revisit that analysis from the beginning to ask these broader questions.

Over the next few weeks, I'll be streaming my work on this project on our Riffomonas YouTube channel. Each session will last about an hour and while I'm streaming, you can ask questions or make comments that I'll do my best to respond to. Even if you can't follow the stream live, you'll be able to follow it later on YouTube. I'll be using git and GitHub to help with version control, so you can follow the code as it develops over on [GitHub](https://github.com/riffomonas/predicting_age_from_name.git). Feel free to file an issue or make a pull request!

I still haven't figured out when I'll be running these sessions. If you are interested in watching the stream live and have a preference, please let me know in the comments below!
