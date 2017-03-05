# Jekyll powered website for projects & events

### To add a project:

For pagination to work, every new project has to be created as a "post". Therefore, every project should be created inside the <b>_posts</b> folder and respect the following guidelines:

- The file is written in markdown (.md)
- The name of the file is preceded by a date in the following format: year-month-day-. You can use the same date as another post. Although it has to be there, this date doesn't affect the rendering, so you could put 01-01-1959, it'd be fine.
- The name of the file will be used in the url, so keep it short and simple (and of course, no blank spaces, use - to separate words)
Documentation to come

**How to use these variables:**

- **layout:** should always be **post**
- **img:** the project's image has to be placed in the "/img/projets" folder. If the variable doesn't exist or if nothing is specified, an image will be created, basically a rectangle filled with a specific color pattern and the name of the project in the middle.
- **rep-img:** Has to be placed in the "/img/people" folder and should be **150x150 pixels**. If the variable doesn't exist or if nothing is specified, an auto-fill will be used: placehold.it/150x150.

- **socialmatter#:** will diplay social button(s) on the page. Simply use the official name of the social media. Ex: twitter, facebook, vimeo, youtube etc... For a website, the value should be set to **"home"**. You can specify **up to 6** social medias: socialmatter2, socialmatter3 and so on. The same goes for the sociallink(#) and socialtext(#) variables. **_IMPORTANT!_** no capital letters: instead of ~~Facebook~~ use facebook.
