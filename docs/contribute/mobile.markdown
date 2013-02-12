### Contributing to the OpenPhoto Mobile Apps

So what do you need to start contributing to the OpenPhoto mobile apps? First, decide whether you want to contribute to the iOS or Android app, as each app has a different development environment. 

If you're looking to use the apps, you can install them from <a href="http://itunes.com/apps/theopenphotoapp">the App Store (iOS)</a> or <a href="https://play.google.com/store/apps/details?id=me.openphoto.android.app">the Play Store (Android)</a>.

### Deciding what to fix
We track all the issues to be fixed on Github.

* <a href="http://github.com/photo/mobile-ios/issues">iOS app issues</a>
* <a href="http://github.com/photo/mobile-android/issues">Android app issues</a>

### Things to consider while you code
Here's what your code should adhere to:

* Commits should reference an issue number (more on that below)
* Comment your code so future developers can tell what's going on

All in all, we recognize that everyone has a different style and level of experience, and we welcome all pull requests.

### Testing that your change didn't break anything

### Committing your code

When committing your code it's important to reference the GitHub issue you're fixing. You can do it by adding a _#_ followed by the issue number.

    # To simply reference an issue with a commit do this
    git commit -m 'Addressing the foobar component but not yet finished. #123'
    
    # To commit and close an issue do this
    git commit -m 'Fixing the most annoying bug ever. Closes #123'

Be descriptive, it helps a ton. Once you've committed your code it's time to push it to GitHub.

    git push origin master

### Getting your change into the OpenPhoto branch

To get your change merged into the official OpenPhoto branch, submit a pull request to the respective mobile-ios or mobile-android branch. <a href="http://help.github.com/send-pull-requests/">GitHub's tutorial</a> is better than anything we could do so we'll link to it.

The important thing is we get your changes and your awesomeness can be merged into everyone else's awesomeness.

### Help! I'm stuck and I have questions!
If you have questions we're always around to help. We've got several contact options listed on the <a href="http://theopenphotoproject.org/contribute">contribute</a> page.
