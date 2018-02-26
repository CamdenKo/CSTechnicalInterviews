# CS Technical Interview - Interviewers
## Forward
Congratulations on deciding to help give technical interviews to other students. This is a fantastic opportunity to both help you fellow student and to better understand the process inside and out. Even after I “figured out” technical interviews, I was absolutely astonished when I realized the sheer amount of insights I gained from role playing as an interviewer. You will feel the same after your first interview you give.

![Learning Pyramid](https://img.washingtonpost.com/wp-apps/imrs.php?src=https://img.washingtonpost.com/blogs/answer-sheet/files/2013/02/pyramid.png&w=1484)

Take a look at the learning pyramid. The absolutely best way to learn something is by teaching the content. Although the learning pyramid is under some heat lately for its validity, giving interviews most definitely is best learned through teaching.

## Why Technical Interviews?
The end goal of any hiring process is to find the best possible employee. A lot of people make the incorrect assumption that this means that companies like Google, Amazon, Microsoft or Apple (which I will reference as the “Big 4”) are simply looking for the “best coder”.

Let’s take a moment to reflect on what we think the “best coder” looks and acts like. In my mind the best coder is a “rockstar”. The kind of person who wears the same hoodie everyday and is able to glance at a problem on a sheet of paper and solve it. The person that you shouldn’t bother with mundane questions because they’re too damn busy figuring out the most complex coding questions.

![Post Malone](https://www.billboard.com/files/styles/article_main_image/public/media/Post-Malone-Sirius-XM-2016-interview-billboard-1548.jpg)

Now let’s talk about who the “best coder” actually looks and acts like. The best coder is warm and friendly. The best coder collaborates with their peers and helps bring them up with them. The best coder works through difficult problems not by themself in a corner, but by working with their team. The best coder is someone who constantly tries to better themselves by learning new technology, challenging themselves, and promoting the growth of their team members. Sure, they could be a “rockstar” coder, but they don’t need to act like one, they know that even if they could do everything themself, the end product and the team's dynamic would be made the best if the entire team worked on it.

So how do companies figure out which programmers are "rockstars" and which aren't? Resumes and cover letters definitely play a large role in the process, but interviews - both technical and behavioral interviews serve as the main information gathering tool for companies.

What's special about a technical interview is that this is the closest an interviewee will ever get to being in a real world situation. There are plenty of people out there who are cool as a cucumber when they are stress free, but under a strict deadline and faced with a difficult problem, will quickly crack and snap at their peers.

Facets tested for in technical interviews:
* Raw coding ability
* Funcitoning in a high stress environment
* Critical thinking/deductive reasoning skills
* Ability to articulate thought process
* Attitude

The ability to code well really is only one out of five different things tested for during an interview, and both interviewers and interviewees should act accordingly.

## Interviewer Attitude
Sometimes interviewers will be horrible. While that is something interviewees should prepare for (mentally), 9 times out of 10, top companies will have interviewers that are trained to test interviewees in the best environment possible.

Again, raw coding ability is only a small portion of the actual interview. This means that interviewers should promote critical thinking and clear blockers when needed. This means that if a student is struggling with a concept to the point where it is hindering the progress of the interview. Let them struggle for a bit. Watch them, observe them and keep in mind the face they make and the words they say. After you have a good idea of how a person struggles, there's no need to continue testing them. Help them, give them the solution if needed. There's a lot to test and not that much time.

It's common for students to view interviews as a battle. One side versus the other, "How do I beat the interview?" is a common question that's thrown around. While interviewees may feel this way, it's acutally quite the opposite. The biggest issues that most companies face is finding quality hires. Thus, interviewees are going to be helping interviewers as much as possible. They <i>want</i> to find good hires and they will do everything in their power to see if an interviewer is a strong candidate. You should act appropriately. Feel as if you want the interviewee to succeed. This comes across in both attitude and interview structure.

In short: be tough, but act as if it's in your best interest for them to do well. Only let them struggle to the point where you know how they behave whilst they struggle.

## The First 15 Minutes
It's hard to have a "real" conversation with a stranger. Especially if that stranger has to make a life-changing decision. A common strategy used to help interviewees open up is by talking about something that they already know plenty about.

The first topic to cover is the resume.

Go for a single deep dive rather than trying to cover every bullet point. If there is a projects section, ask the candidate to pick one of the projects and explain what they did. Try to get them into it. People love talking about themselves, so if you ask a couple leading vague questions, interviewees should open up and offer information themselves. If you do get stuck here are some questions you can ask to get them back on track.
* What was the motivation behind starting this project?
* Detail a technical difficulty you ran into on this project. How did you overcome it?
* If you were to restart this project what would you differently? What would you do the same

Now, if they don't have any projects on their resume you can go one of two paths.

1. Do the whole project shinding but with work experience / clubs
2. Focus on an inclass assignment (this is the worse option)

It can be hard to pull it out of students, but in this portion of the interview, you're really just looking for attitude and passion. If an interviewee is passionate, it should show. Take note about the confidence and clarity they discuss their topics. If a student can't articulate properly what their project entailed, that's definitely an issue that will translate to the workplace

#### Why Whiteboard
OK. This is getting into a huge debate that's ongoing in the field of computer science. If you only have 15/30 minutes to figure out if an applicant got the sauce, how the hell can you tell how they're going to be for 8 hours a day for the rest of their life?

For a short while there were the logic questions. These have mostly gone out of style. These are probably the ones you've heard of and subsequently went, "Dude! [insert_tech_companies_name] is insane!" Something along the lines of:
* How many golf balls fit in a bus?
* Why are manhole covers round?
* How many people in the US own cars?

These definitely will pop up every once in a while, but in general, these are no longer relevant. While there may be a <i>correlation</i> between figuring these out and being a good software engineer, it's a tenuous one - at best.

## The Last 15 Minutes
The interviewee should be warmed up and loose. Thus begins the dreaded <i>technical</i> part of the technical interview. For this, use one of the problems attached. Keep in mind to only allow the interviewee to struggle a productive amount. Feel free to answer many clarifying questions, when prompted with one, try to give an answer that fulfuills the question as long as it doesn't blatantly answer the question (unless they need it).

When they provide you with a solution the first thing you should check for is correctness of logic. Generally speaking, ignore syntax mistakes. If the logic looks sounds, look for problems with edge cases. If all of those seem sound ask for the Big O notation and ask them if they can see any ways to further optimize their solution.

In general, here are the steps for helping an interviewee along:
1. Hint that there may be a problem / what the problem may be
  * "Are you considering all the edge cases?"
  * "Have you considered the problems with the data structure you're using?"
2. Give examples of cases where the issue may arise
  * "What would happen if an empty array was passed in?"
  * "What are the advantages of using a stack vs a queue in this situation?"
3. Give them the correct answer, but ask them why that answer is correct
  * "If you pass in an empty array, you cannot access the first element of the array. How would you prevent this and why is this a problem?"
  * "If you use a stack you will be doing FIFO, but the problem would be best done with a LIFO solution. Why would you want to use a queue instead of a stack?"

The largest takeaway from this section is this: <b>ask questions.</b> Questions in the right direction are usually the best way to spur creativity and will allow you to further see their thought process as the attempt to come up with the correct answer.

##
