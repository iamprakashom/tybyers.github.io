---
layout: post
title:  "Storytelling: The Power to Influence in Data Science"
date:   2016-06-21 20:50:00 -0600
comments: True
---

*Note: This is a lightly edited excerpt from my recent [interview with Kaggle](http://blog.kaggle.com/2016/06/13/communicating-data-science-an-interview-with-a-storytelling-expert-tyler-byers/).*  
Humans are story-telling animals. We love a good story. Stories, whether in the form of movies, epics, songs, or myths: they capture us, they move us, they bind together generations, get us in touch with deeper messages. Everyone knows how to tell stories, at least a little bit. But, certainly some of us seem to have more storytelling talent than others. That group of five or six friends you hung out with in college: there was probably one person in that group that everyone loved to listen to.  They could tell stories for hours on end -- funny stories, stories that made you think, stories that made you cry, stories that changed your life.  This person, they didn't necessarily know more about the world than you.  But they knew how to craft their message in an interesting manner, and likely had an outsized influence on you and your circle of friends.  

As Data Scientists, we need to be able to influence. We have data and insights that can shape the direction of a business. But all our insights are for naught if we can't convince the leaders in our business to *act* on our insights.  Our Data Science peers might be interested in the details of our heroic data wrangling, or seeing how many models we ensembled, or how many features we engineered. Leaders of our business? Unless our work can save or generate dollars, they see nothing more than perhaps a grown-up version of a science fair project.  That's right, I'm comparing your sophisticated models that took you three months to build to a fifth-grader's [papier mâché volcano](http://www.wikihow.com/Make-a-Papier-M%C3%A2ch%C3%A9-Volcano).  Interesting and fun, but eventually just clutter in your bedroom that you throw out with the garbage.  Hopefully you had fun and learned something, even if you didn't win that ribbon!


<img class='figure' src='/assets/paper_mache_volcano.jpg'>

<div class='caption'>Not my volcano, but I made one like it in fifth grade.</div>
<br>

So, as Data Scientists, how can we influence? How can we convince our company leadership to act our insights?  I struggled with this when I began my current job. The five-minute morning standup meeting and occasional ggplot visualizations dropped into Slack chat weren't enough.  I was doing (what I thought was) cool work, but it wasn't affecting the direction of our product.  So I found my voice. I began telling my data's stories, and writing the stories down. Working hard on visualizations. Thinking about my audience's needs. Asking lots of questions -- finding out what my business needs were, not just what I found interesting in the data.  I began focusing on how I was *communicating* my insights.  And things began to change. It's still (and always will be) a work in progress, but I am having increasing influence as my communication and storytelling improve.  

### How I Communicate my Results

It starts with the blog.  Last September, I spent several days figuring out how to start a [Jekyll](https://jekyllrb.com/)-driven blog on our company's GitHub Enterprise install (of note, my [personal blog](http://datawrangl.com) is Jekyll as well).  At first I was worried that my time setting up the blog would be wasted -- these were a few days when I wasn't doing data work, after all.  But this has been one of my best decisions I have made.  I blog about two to three times a month, at various "stopping points" in whatever project I'm working on.  I love the blog because the words are mine, and I don't have to worry about sounding too formal.  I can easily cross-reference previous blog posts.  Writing helps me organize my thoughts, helps me record additional questions, and provides a repository of ready visualizations if I need to have a presentation ready quickly.  I forget what I worked on just two months ago. I forget what ideas I had two months ago. If I go to my blog, I get that refresher much better than I would had I left the results in an R Markdown file in a random directory on GitHub.  And I can easily share my blog links with company leadership. In fact, I've been shocked how many times I've been asked a question by company leadership, and I can say "oh yeah, I think I did a project on that 4 months ago...yep, here's the link!"  


<img class='figure' src='/assets/internal_comverge_blog.png'>

<div class='caption'>It won't win any style points, but my work blog is my best gift to my future self.</div>
<br>

On a short-term basis, I still share day-to-day findings with my team in the morning standup meeting, but I try to limit what I share to just a couple sentences, unless someone asks me to elaborate.  I might still drop a ggplot visualization or two in our [Slack](https://slack.com/) chat every couple weeks.  These are nice to keep a conversation going, or to maybe get a question answered, but are easily forgotten and not very influential.

Finally, I'll occasionally give presentations to customers or potential customers, usually with leaders from my business in attendance. These can be high-stress, because business and dollars rely on the outcomes!  But, since I frequently write on my blog, I find delivering the content of the presentations to be rather easy. I know the material, have done my best to explain it in my blog, and rarely do I get very technical questions that I can't answer.  The presentations are more about showing pretty pictures and telling how our way is an improvement on the old way (and it's not very hard showing that Machine Learning is an improvement compared to analysis from Excel spreadsheets!).

### Adding Value to my Work, Beyond the Numbers

Effective reporting, detailed analysis, and visualization is what gives my "core" work any value at all.  My core work is developing machine learning software.  So it's similar to a [Kaggle competition](https://www.kaggle.com/competitions), where I develop a model, test it against a metric, and iterate to improve the model.  Once I get to a good "stopping point" with my model, I'll write production-level code to integrate with the rest of our application.  

But, as any good Kaggler knows, in the course of creating my model, I've created a beast!  In particular, I've come up with several new features that must be engineered.  But I don't do the engineering for the production systems! I write code in R! My team writes code in Ruby!  Their engineering pipelines feed my models.  How do we get on the same page?   

I've just spent two months creating this new, better model.  Now comes the arguably more difficult work.  The work of influence. The work of convincing my team lead that it's worth his effort to write new [Pivotal](https://www.pivotaltracker.com/) stories, point them up, and assign them to team members.  Maybe push our product deadline back by a few weeks to accommodate the new work I've created.  Why and how is my new model better?  Why should they care?

Fortunately, I've been blogging about my new model all along.  Creating visualizations showing the improvements against the test metric.  Admitting in my blog when a new feature that I thought would improve the model actually made it worse. Ordering my changes in terms of priority, should we not be able to implement all of my recommendations.  

My analysis must be extremely detailed. I need to anticipate questions.  I need to have had conversations with my team lead all along, to try to figure out what changes might be feasible, and which ones I should leave until the next version of our app.  

I've found that visualizations are even more effective than my words.  I can write for five pages trying to explain my argument.  But a good visualization or two captures the mind, captures the imagination, and I've found can ultimately be the influencing factor in convincing my team to take my suggestions.  

<img class='figure' src='/assets/visualization_storytelling.png'>

<div class='caption'>Source: <a href='http://www.forbes.com/sites/brentdykes/2016/03/31/data-storytelling-the-essential-data-science-skill-everyone-needs/#52d15943f0c8'>Forbes.com: Data Storytelling</a></div>
<br>

### Six Ways to Improve Your Storytelling Skills

Every person has the ability to tell a story.  Clearly, some people seem to have more talent than others, but storytelling is ultimately a *skill*, and skills can be improved with intentional practice. Technical people in particular can really struggle telling a story.  I don't know if it's the whole left-brain versus right-brain thing, but clearly crafting a story is a creative process.  People with technical skills often tend to bogged down in the details.  Effective storytelling is more about keeping an eye on the big picture -- where you want to start, the waypoints you need to hit, and where you want to end -- while giving enough details to fill in the gaps in the big picture.  Here are some of my tips for becoming a better storyteller:  

  * **Read as much as possible.**  Fiction, non-fiction, technical books, blog posts, magazines, newspapers.  If you're only reading material in Data Science, or in technology, most people will find you boring.  You won't be able to connect with many people. Human connection is critical to effective storytelling.  Writers who get paid to write are essentially paid storytellers.  Learn from them!  I love reading National Geographic magazine in particular. The photographs are the story, and the essays surrounding the photographs add in the color and context.  If you must read data-related stories (and you should!), I think [FiveThirtyEight](http://fivethirtyeight.com/) sets the standard. Take inspiration!

      > "You have to read widely, constantly refining (and redefining) your own work as you do so. It’s hard for me to believe that people who read very little (or not at all in some cases) should presume to write and expect people to like what they have written, but I know it’s true." - Stephen King

  * **Write as much as possible.** Writing provides clarity to your thoughts.  You will ask better questions.  You will be able to provide better answers when asked about your work. A well-written blog post or report can give you significantly more influence than you may think!  But you must practice. [Do the Work](https://taylorpearson.me/dothework/).
  * **Find your voice.**  You won't be influential if your reports are boring or overly academic.  Leave the academic work for academia. That's its place, and it works there. You are in business now! Find your voice.  Don't be afraid of saying "I" in your blog posts.  Make people want to read your work.  Make people want to act on what you say.  This may be especially hard for people with PhDs, who have written academically for years. But once you get past this, it is extremely freeing.  
  * **Visualizations First:** When writing or giving a presentation in Data Science, before you write a word, add in your visualizations.  *Your visualizations should be your story.*  The words you write or say should be meant to add context to your visualizations.  
  * **Listen to Stand-up Comedy.**  Comedians have a special gift for noticing absurdities in the world around us.  But listen to the best stand-up comedians.  Are they standing up there telling one-liners?  Knock-knock jokes?  No! They are communicating the absurd via stories, often very elaborate stories.  Listen to how they craft these stories.  You don't want to necessarily emulate a stand-up comedian when you are giving a Data Science presentation (I highly recommend against it), but you can learn a lot through their use of story as a communication tool, and can take cues from their cadence and inflection. 

<img class='figure' src='/assets/jim-gaffigan.jpg'>

  * **Know your Audience:** This is key to connecting, and thus influencing.  If your audience is the decision-makers of a potential client, they aren't going to care about the details of your five-model ensemble, or what features you had to create.  They have business pain; how is your model solving it?  Who do you expect to read your reports?  Target their needs. Sure, you might need to write up a technical document for your future self or future teammates (or your replacement when you leave).  But then write another version of that report that your third-line manager can understand and act on.  If you don't know your audience's needs, you won't connect with them; if you don't connect, you won't influence; if you can't influence, then hopefully your work has been interesting to you, because it's likely useless to your business.

<hr>
Thank you for reading my post.  Do you have any examples of how storytelling has helped you in your career, in data science or otherwise?  Any additional tips for how to improve as a storyteller?