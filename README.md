# Portfolio Showcase

I have created this to be an option when deciding how to create, update and display your portfolio.

This is a modified and preconfigured [Jekyll](https://jekyllrb.com/) / [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) setup.

To get it running all you need to do it is:
1. Clone the repo
2. Run these commands:
```ruby
bundle
bundle exec jekyll serve
```
It will be then be available to view at `http://127.0.0.1:4000/`

### Homescreen
![Homescreen](readme_images/homescreen.png)

### Evidence
![Evidence](readme_images/evidence.png)

It's possible to deploy this to something like [Netlify](https://www.netlify.com/), but due to the sensitivity of the evidence it would need to be approved first, and I don't think Info/App sec would be happy with that. (I need to see if it can be run privately on our infrastructure)

***

When writing evidence for your portfolio, you can create a new file in `_portfolio/`. 
The ordering on the home screen and using the next / previous buttons work based on the names on the files, so if you want a specific order, start the file names with numbers.
Images should be stored in `assets/images` then can be used in portfolio pieces.
In the top section of your portfolio evidence (the frontmatter), you can add the list of duties achieved with that piece of evidence. It is this data that powers the table on the front page.
You can also add the title and the summary here, this again populates the home screen and the title is used on the page itself.

***

In the `_config.yml`, there are a few bits to change, eg. `email:`, `github_username` and `author: name:`.
Everything else can be customised as well, have a look at the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) documentation to see what can be tweaked.
