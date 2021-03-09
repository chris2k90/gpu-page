# Contributing

## How to add support for you language

if you open up `graphics.page` you'll see `Title=` or `Title[language_code]=` a bunch of times, and to add a new language is pretty simple, you just need to:

- fork this repository
- create a branch with `git checkout -b your-branch-name`
- make your changes to `graphics.page`, adding `Title[your_language_code]=translation` after the last `Title[**]`
- commit your changes
- push your changes with `git push origin your-branch-name`

now if you go to your repository on github, you'll see a `Compare & pull request` button, click on that button and submit a pull request.

if you don't know which language code your language is, don't worry, after the pull request i can help you with that :)
