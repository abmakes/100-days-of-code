# 100-days-of-code
During the next 100 days I will focus on improving my frontend skills through building several single page sites using React and several web services, learning new CSS animation and design skills, and working towards building a portfolio website as well as two larger projects.

## Completed project:
- [100daysofcodeblog](https://adriaanb.herokuapp.com/)


## Day1 - Design and deploy blog

...and we're off.

Today started off a bit slowly with me fumbling through attempts to create a blog as quickly as I can. Tried github pages with Jekyll, but I didn't want to install Ruby. Tried Gatsby, but I'm not proficient enough with react yet and attempting to modifying themes was tedious. Last chance to pull it off, go back to what you know. I built this siprogress.htmlmple page using Django, HTML and CSS. Attempted deployment, but I need to sort out some Heroku authentication issues. Will finish tomorrow

Tomorrow, I will also work on fetching blog posts from github using the github api, maybe try add some finess to the page. I am not looking to make this site too complex. I just want a place to share my thoughts and document my journey.

## Day2 - Deployed website and linked github

Today I finally managed the deploy as Heroku had changed some authentication issues. I also worked on a post about the intitial Django to deploy steps. I managed to create a quick javascript fucntion to fetch commits to this document and display them as posts on the blog. Using the django backend would have been easier but I want every blog to show on my github activity. This method allows me to do that. Here is a link to the blog https://adriaanb.herokuapp.com/.

## Day3 - Finalized blog, learned some new CSS

Today I finalized the blog setup & workflow to make it easy and managable. It is not optimized or super user friendly, but this is just a minimum viable product so I can focus on the other projects I want to work on. I might make some changes down the line, but for now it will work. I learned some new CSS techniques that I will need for upcoming projects including modifying range sliders and dark/light mode. Added the light and dark mode to my blog depending on your browser color preference.

I also picked up this monster of a VScode modification, go to Preferences > Keyboard Shortcuts and add the Alt+W shortcut to quickly wrap text in a tag:

```{
"key": "alt+w",
"command": "editor.emmet.action.wrapWithAbbreviation",
"when": "editorHasSelection && editorTextFocus"
}
```

An emmet widow will open and you can enter the tag abdreviation eg. make aselection of some text > press Alt+W > write "p" and press Enter. Text will be wrapped in a paragraph tag. BOOM! MAGIC :)

## Day 4&5 - React tutorials

Weekends are my busiest time, so 1 hour of tutorials is what I'll be aiming for every weekend. Worked through some of FreeCodeCamps tutorials, but find the process when you are stuck a bit tedious. However, I will still finish it no matter what.

## Day 6 - Scrimba React Course
Today I started with the Scrimba React course. I had hoped to be building my own React projects by now, but I will take a few more days to review the basics. I managed to finish the first section. The videos and practice excercies have a nicer progression than the ones on FreeCodeCamp, in my opinion, but I still want to do the FCC projects. I will do the scrimba digital business card skills test project tomorrow.

## Day7&8 - More React on Scrimba

This course is great, really feel like concepts are hitting home and being reinforced. Here are the two solo projects from section 1&2:

- [A digital business card](https://scrimba.com/scrim/c9zWGpCZ)
- [A travel journal](https://scrimba.com/scrim/cod0944519b723483f05f0e04)


Next, I might try build something of my own with react and deploy it on Netlify before I move on with this course.

## Day 9&10 - Portfolio design and netlify

Spent a lot of time in Figma working on my portfolio design. Trying to make it my own resulted in a lot of pizza on the page. Created a quick React App and learned to deploy on Netlify. The app is terrible, not responsive and basically a static page. But I'm excited to add some functionality in the next week. Also worked on some CSS animation techniques for text reveals, see this [codepen](https://codepen.io/abmakes/pen/bGLRrjG).

## Day 11, 12 and 13 - More SCRIMBA React Basics

Weekends are for coursework, did an hour of react course on both Saturday and Sunday. Got really stuck in on Monday and almost finished the third section. This course is addictive, just want to keep pushing on. Some of the concepts covered in the last 3 days.

 - Event listeners, state, conditional rendering, forms, side effects, working with local storage, passing paramaters down through functions, lazy loading.
 - Also some javascript methods, array.filter(), spread, event destructuring.

## Day 14 - React Projects

Finished scrimba meme generator and notes app. Started my own react app Save Dave, an expense tracker. Will share more about it in the coming days.

## Day 15-17 - Save Dave
Started building my ideal expense tracker, added a chartJS doughnut chart and deployed it on netlify. Linked github to netlify and worked on an MVP for the app.

Worked on Neobrutalist design and using sliders to manage values in state. There is still a lot to do, especially with expense storage and responsive design, but the current version is live at [save-dave.netlify.app](https://save-dave.netlify.app/).
