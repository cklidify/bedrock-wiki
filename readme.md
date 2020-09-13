<p align="center">
    <h1 align="center">Bedrock Wiki</h1>
    <p align="center">The Bedrock Wiki is a wnowledge-sharing website for Technical Bedrock, containing documentation, tutorials, and general how-to information.<br>Here, you can contribute to this amazing, open-source resource!</p>
    <p align="center"><strong><a href="https://wiki.bedrock.dev/">Visit the website!</a></strong></p>
    <br><br><br>
</p>

# Welcome!

This is the code-base for the technical bedrock wiki. If you haven't checked out the website version yet, you can do so [here](https://wiki.bedrock.dev/).

This wiki is community written and maintained. If you want to contribute, you have found the right place!

# Contributing

## Communication

You should probably join the [discord](https://discord.gg/XjV87YN), which is where all wiki-communication takes place. While small changes and new articles do not need permission, large-scale changes should go through community review.

## Issue Tracking

Issues are not currently tracked very well, since a large portion of the community does not use GitHub. I try to add issues as people report them though, and I highly encourage anyone to tackle them.

## Using GitHub

It is beyond the scope of this readme to teach the proper use of Git and GitHub, but you can always reach out personally for help. Some steps to get you started though (google steps if unsure):
 - `make github account`
 - `fork the repository`
 - `make changes, commit changes, push changes`
 - `create pull requests`

## Commits and Pulls

Please provide proper commit messages when contributing, this will make it much easier to approve pull requests. Don't change anything in the config unless you really need to.

## Contributing without GitHub

Want to submit an article, but can't be bothered to learn Git, or GitHub? You can send me markdown articles directly, and I will add them manually.

## Testing
You can locally test the website by [installing Jekyll](https://jekyllrb.com/docs/installation/#guides) and then running  `bundle install` and `bundle exec jekyll serve`.

Assuming the Ruby dependencies installed correctly, the local server will run and you should see `http://127.0.0.1:4000`
printed out.

You can now make changes to any of the markdown files and you'll see the changes reflected at that URL in your browser! Note the site can take several seconds to rebuild, so have an eye on your terminal window
