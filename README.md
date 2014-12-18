github-push-start
=================

Getting new members started with github a la https://codeforkansascity.github.io/meeting-notes/github/2014/11/04/github-push-start.html


GitHub Push Start

Nov 4, 2014

In this exercise, you will add your name to a website hosted on GitHub, using only your browser. The current list is at http://codeforkansascity.github.io/meeting-notes/coders.html

This workflow is used by many open source projects to allow multiple people to contribute to one project.
Login to your github.com account

If you don’t already have a GitHub account you will need to create one at http://github.com
Fork the KC Brigade Website

When you are editing a page, always work in a repository forked to your account. Whenever you fork a repository you will do it from the repositories page.

  1. Go to the KC Brigade Notes repository page by browsing to https://github.com/codeforkansascity/meeting-notes
  2. Click the Fork Button in the upper right hand corner of the page. If you are a member of more than one organization, you will be asked where to fork it to. There may be a small delay as it forks the repository. When the page refreshes you should be at your fork of the repository.
  3. Take a look around your copy of the repository.

View your fork in a browser

codeforkc.org uses GitHub Pages to host its site. When you forked the code over to your account, that setup came with it.

To view your version, just go to http://username.github.io/meeting-notes/coders.html, replacing username with your GitHub login.

NOTE: It may take up to 10 muniutes for GitHub to setup the site.

If you are interested in hosting pages on GitHub go to https://pages.github.com/.
Add your name to the list of coders

To see the current page go to http://username.github.io/codeforkc.org/coders.html.

To add your name to coders.html:

  1. Go to your fork of the site if you are not already there :  https://github.com/username/meeting-notes
  2. Find coders.html in the list of files and click coders.html. The code screen appears.
    Click the pencil just above the upper right of the code. The edit screen appears.

    Add a line below the last ending </li> tag and type a new beginning <li> tag. The ending tag appears automatically.

    Type your name between the list tags.

    <li>Your Name</li>

    To see the changes, click the Preview Changes tab at the top of the edit box.

    If you need to fix something, click the Edit File tab at the top of the edit box, and make the change.

Commit your changes

    Commit your changes so you can see them in your browser by filling out the Commit Changes section of the page below the Edit box.

    Replace Update coders.html with Added your name to coders.html

    Then press the Commit Changes button

    To see your name on the coders.html page browse to http://username.github.io/meeting-notes/coders.html

Issue a Pull Request

A pull request asks the owners of originating repository to review and merge your changes into the repository, in this case http://codeforkc.org

    Navigate back to the list of files in the repository. This should be at https://github.com/username/meeting-notes

    Click the green button above the list of files to the left. This is a pull request link. The Create Pull Request page appears.

    Enter a title and description. An example title for this would be “Added Your Name to the coders list.” There is no need to fill in the description.

    Click the Create Pull Request button.

    If you are at a meeting, inform one of the captains of the pull request.

