# iOS Demo Day

## Requirements

1. Fork and clone the repository
2. **Add your presentation content**
    1. Slide deck (4 required slides)
    2. Links
    3. Answer all questions 
    4. YouTube demo video (1-2 min max)
3. Polish your Github Code repository
    1. Add screenshots and an overview to your GitHub Code Repository
    2. You should make that repository the "Public Portfolio" for your project
    3. Look at [John Sundell's Splash project](https://github.com/JohnSundell/Splash) for inspiration (code, images, GIFs)
4. Create a pull request (PR) and **tag your TL and Instructor**

## Links

* Github Code: `https://github.com/froggomad/iOS-Build-Sprint-1`
* Github Proposal: `https://github.com/froggomad/ios-build-sprint-project-proposal`
* Trello/Github Project Kanban: `https://trello.com/b/zkBeOwrE/lunchly`
* Test Flight Signup (Recommended): `<insert beta signup link here>`
* YouTube demo video (Recommended): `<insert video url here>`

## Hero Image
### placeit.com is down
`https://ibb.co/gPKQhc4`

## Questions (Answer indented below)

1. What was your favorite feature to implement? Why?

    `I liked implementing the meetup feature a lot. It gave me a chance to practice a lot of different fundamentals, as well as some new challenges.`

2. What was your #1 obstacle or bug that you fixed? How did you fix it?

    `I had a mysterious bug crop up Thursday where an Alert that was crucial to an MVP feature was dismissing itself before it could be used. I used completion blocks to work around it, but still don't understand why it cropped up.`
  
3. Share a chunk of code (or file) you're proud of and explain why.

    `This little beast right here, this tiny chunk of code, along with a small amount of logic, saved me from having to write several functions that would sort a dictionary of type [Restaurant:Int] used to tally votes (another MVP feature). I spent hours trying to figure out a way to make that all work, and this was the keystone. I just used the struct to store all of the dictionary values, put the values in an array, and sorted the array.`

```Swift
struct Vote: Codable, Equatable {
    var restaurant: Restaurant
    var votes: Int
}
```
  
4. What is your elevator pitch? (30 second description your Grandma or a 5-year old would understand)

    `Have you ever gotten in an argument with someone over where to go to eat? In today's fickle dating environment, relationships are ended over meager disputes over food. 

"Italian or Pizza babe?"
"Idk... you decide"
"Your lack of commitment is ruining our relationship, I'm done!"
Ok, so maybe this doesn't happen.

How about that group of coworkers you go out to lunch with every Friday? Ever have a hard time deciding where to go? I bet you have...

Lunchly can help!

With Lunchly, you can pick several restaurants, and one or more friends to go with you. Lunchly will trigger a vote that ends 30 minutes before your meetup time. If the vote is tied, Lunchly chooses for you! Simple!

`
  
5. What is your #1 feature?

    `It's hard to call the meetup feature a #1 feature because it's really several features rolled into one... but that's precisely what makes it the #1 feature. Sorry friendly alerts, and timely notifications. Sorry groups and restaurants - you're all key components, but the meetup feature steals the show!`
  
6. What are you future goals?

    `I'm considering making this a full-featured app on the app store. It needs to have Firebase or some sort of backend integrated, and some minor tweaks and bug fixes, but it's a solid app.`

## Required Slides (Add your Keynote to your PR)

1. App Name / Team Slide
2. Elevator Pitch
3. Your #1 Feature (Customer facing — what can I do with your app?)
4. Future Goals

## Slide Requirements

1. 50 pt font minimum
2. Be concise — don't write sentences/paragraphs (put these in your slide notes for speaking)
3. 3-6 bullets maximum per slide
4. Do the squint test (can you read the text if you squint, if so, make the font bigger)
6. Images are always welcome
7. Do the Grandma Test (Would your Grandma understand you?)

### Optional Slides

1. Blooper: What's a funny bug or blooper? (screenshots/GIFs please)
2. Revenue Model: If the app was your sole source of income, how would you monetize it?

## Presentation Format

**7 minutes/team**

* 4 minute presentation (5 minute hard cap)
* 3 minutes of questions

We have ~12 teams presenting today — please practice your presentation with a timer (as a team), and make sure you fit within the time limit.

Plan on having one person present the slides and live demo. Please practice your presentation in front of a mirror or with your team 2-5 times. Have the app running and visible (Simulator or QuickTime) so you can quickly transition between slides and live demo.

* App Name / Team Slide (30 seconds)
* Elevator Pitch Slide (30 seconds)
* Your #1 Feature (30 seconds)
* Live Demo (2 minutes)
* Future Goals (30 seconds)
* Questions (3 minutes)
