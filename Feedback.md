Feedback that I received and how I weighed whether to use it.
Topics for Semester Project:

Hey everyone, here are my  topics for the semester project, do you mind giving me feedback on them?
1)Stats on Pokemon characters.  How do  the heights and weights of Pokemon male, female, and other genders compare?  Are there correlations, are the heights and weights normally distributed?
2)How does Utah’s crime rate over time compare to the national crime rate over time? I would want to analyze the reasons behind any variations which could be affected by local policies, social and economic factors and other influences.
3)When is the best time and season to get a campground at a national park?  How does weather data and other restrictions affect camping availability?

Feedback for Topics
kylieclinton — 11/06/2023 1:26 PM
I really like your second two options! All of them will be interesting, I think your last one will be very useful and provide good data and conclusions for people to use in real life

Justin Ross — 11/07/2023 2:30 PM
Hey Rebekah, all of your topics sound like a lot of fun (especially the Pokemon one!). I think the second one is very original and would be a great topic for an EDA, but so are your other two topics. Ultimately I would go for whichever topic has data that meets the requirements for the tier you are doing.

Davis Dowdle — 11/14/2023 9:32 PM
Sorry I'm getting to yours late as well Rebekah. I like the second one the most because the conclusions might be useful to policymakers, philanthropists or activists. I like the last one as well because it's something normal people could use regularly to improve their quality of life.

I appreciated all the feedback and decided to go with the third topic for camping.  I couldn't do the original question once I obtained my data because unfortunately there wasn't any sort of a visitors log in the camping data I got from the NPS but I did have a cost column and was able to come up with a question of what are the average costs for camping by region?

Feedback for Blog 1 and 2, and Streamlit:

Samantha MacDonald
Student 1: Rebekah Webb

1.     Blog Post 1: I think that this project idea is unique and well-executed! You explained why you chose the topic, how you found your source, and what the process of reading the data in was concisely. My only suggestion would be to read back through and make sure all the text blurbs are formatted correctly. There are some places where there aren’t spaces between words and minor things like that.

2.     Blog Post 2: This is a great blog post. I especially like the section where you’re checking if your data is scale free or not – I haven’t really seen that before! The visuals that you included are really helpful and address your question very well.

3.     Streamlit App: This app is so cool! I really like the map element of it. The only feedback I have here is that module 3, which is supposed to show filtered data for the parks, isn’t visible. It may be an issue on my end, but I thought that I’d mention it here just in case! 

Brandon Wegrowski — Yesterday at 10:42 AM
Great topic Rebekah! Here's my feedback:

Blog Post 1:
I would put your code in python blocks (```python ```) instead of generic code blocks (```code ```) so that it will color some of the text and make it more readable.
It looks like your images in this blog post are screenshots instead of actually images (I can see the blue resize borders around them), so, if you're able, I would recommend inserting the pictures directly.

Blog Post 2:
Same suggestions as blog post 1: I would put your code in python blocks to make it more readable.
All your images, except your first, are half the width of the text; I would make them full-width if you can (they are great graphs, just difficult to see at half size).

kylieclinton — Yesterday at 11:15 AM
Rebekah great job on your posts! Here is some of the feedback I have for you:
1st blog: 
I love the introduction
the cover photo and end photo shows the blue outline a bit
I couldn't find your EDA questions easily when looking through. Maybe state them clearly through bullet points or something? I think we need 4-5 questions for Tier 1
I like your organization of the process you used to clean the data
Tier 1 also requires a discussion of the ethics you considered in your EDA and I didn't see a section for it.
don't forget links to your data and repository!
2nd blog:
A couple sentences seemed like run-ons and could use some general revision
the mean cost by region plot is causing some funky formatting
I love the personal story touches!

Streamlit:
the scatterplot graph might work better as a bar plot. it would be great if on your campground cost viz you could order the costs in ascending order, right now they are pretty random and hard to find. 
it feels a bit odd having only one filter in the sidebar, if you use st.multiselect you can use the same option you have there without the need for the sidebar.
the viz options you have are very thorough and great for looking at campsites at parks! Very interesting stuff and very well done!

Justin Ross — Today at 12:05 PM
Hey Rebekah, I really enjoyed looking over your work! Here’s my feedback for you:

Data Collection
Overall the blog looks great! I agree with what someone else said, I think if you put ‘’’python ‘’’ at the top of your code chunks it will color the code like python normally does, and that would help the overall appearance.
I really like that you used headers to make your post skimmable. However, to me, it seems like some of the headers could be consolidated. To be specific, I think you could combine your “Organizing data columns” section with “Cleaning the data and renaming columns”, and “Saving data to csv file…”. If you want to keep those headers, I would suggest making them a little bit smaller and putting them under a larger header like “Data Cleaning”
In your “Saving data to CSV…” section, it looks like you have some text inside your code block. I would suggest moving this sentence out of the code block: “Next I examined the different statistics of my data by performing a describe function.”

EDA
I really like all of your graphs, this blog was a very entertaining read. Similar to the previous post, I think the code would look a little bit more digestible if it was colored, which you can change by putting python at the top of the code block like this: ‘’’python ‘’’.
Im not sure that we even need to have our code in this post. If you want to have it in there I think that’s totally fine, but I was just looking over the instructions and I don’t think we need to show our code in this post
A lot of your graphs seem pretty small, which makes them hard to read. If there’s any way you could make these graphs look a little bit bigger, I think that would have a big impact.

Blog 1 feedback I implemented in my first blog post.  I made sure to fix the camp pictures to get rid of the blue outlines.  I changed the formatting so that I didn't have so many bold titles and instead made them regular text when it made more sense to organize it that way.  Some of my headings were abrupt in appearance and the headings I kept made my sections more organized.  I changed the code chunks to python to make it more colorful the way python code is and I really like how it looks.  I also added the questions that data answers to the end of my first blog in a bulleted list. This was to set up my second blog post where I will go into more detail with the questions in the title along with the visualizations. I also added a link to my github repository that has my code for both blog posts, my nps_camp.csv and my streamlit py app.

Blog 2 feedback I implemented in my second blog post.  I enlarged my pictures and got rid of the code since it will be in my repository and it looks cleaner to just have the questions in the heading and subheadings with the graphs.  I edited to get rid of any run on sentences and organize my blog better.  After looking at some other blogs that I provided feedback for, I decided to talk about future data analyses that this project has sparked me brainstorming for.

Streamlit feedback I implented in my Streamlit app.  This was a part that I had to weigh the opportunity cost with the time that it would take to implement the changes.  I did have a chance to play around with the graph options for the first part of Kylie's feedback that was given verbally to me about a week ago.  The scatter plot was a much better graph to display the individual dots of camp costs vs. the thick bar plot that covered some of the cost data in one big chunk.  I agree that the cost drop down option by zip code would look better ordered from low to high but it is also a place that you can enter your own cost and doesn't necessarily require order.  I agree that the drop down menu to the left is a little awkward to, I tried to tie the filtered drop down of Pork Codes with the filtered table by writing a note in the subtitle that the drop down was to the left and on the Park Code that the filtered columns were lat, long, and cost columns.  I know the same module 3 was confusing for Samantha too so it's not perfect but it is still fun, and interactive.