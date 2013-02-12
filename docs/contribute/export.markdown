# Contributing to the Import/Export Script Collection

OpenPhoto strives to be a decentralized service for users who want to maintain ownership of their photos and media. Part of this mission includes a collection of export scripts from various photo services, along with an import script to import those photos to OpenPhoto.

## Our current collection of scripts
Our currently available scripts are written in Python and can serve as examples for any new scripts you write. You can improve an existing script or write a script to export from another site.

* <a href="https://github.com/photo/export-flickr">Flickr exporter</a>
* <a href-"https://github.com/photo/import">Import script</a>

We also have export scripts for Facebook and Instagram, which should be available on Github soon.

## Deciding what to fix or create
Each script gets its own repository and issue tracker on Github. If a photo hosting site has an API, then you can write an export script for it.

* <a href="https://github.com/photo/export-flickr/issues">Flickr exporter issues</a>
* <a href="https://github.com/photo/import/issues">Importer issues</a>

If you're interested in building an exporter for a new site, contact us and we can start a new repository.

## Things to consider while you code
Here's what your code should adhere to:

* Spacing matters: four spaces, no tabs
* Commits should ideally reference an issue number (more on that below)
* Comment your code so future developers can tell what's going on

All in all, we recognize that everyone has a different style and level of experience, and we welcome all pull requests.

## Committing your code

When committing your code it's important to reference the GitHub issue you're fixing. You can do it by adding a _#_ followed by the issue number.

    # To simply reference an issue with a commit do this
    git commit -m 'Addressing the foobar component but not yet finished. #123'
    
    # To commit and close an issue do this
    git commit -m 'Fixing the most annoying bug ever. Closes #123'

This won't always be the case if you're building an entirely new exporter. That's okay. Be descriptive, though; it helps a ton. Once you've committed your code it's time to push it to GitHub.

    git push origin master

## Getting your change into the OpenPhoto branch

To get your change merged into the official OpenPhoto branch, submit a pull request to the respective export branch. <a href="http://help.github.com/send-pull-requests/">GitHub's tutorial</a> is better than anything we could do so we'll link to it. If your export script doesn't have its own repository yet, contact us and we can fix that.

The important thing is that we get your changes and your awesomeness can be merged into everyone else's awesomeness.

### Help! I'm stuck and I have questions!
If you have questions we're always around to help. We've got several contact options listed on the <a href="http://theopenphotoproject.org/contribute">contribute</a> page.
