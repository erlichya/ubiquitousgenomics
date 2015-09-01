# Ubiquitous Genomics

This is the source repository for the Ubiquitous Genomics class of 2015
at Columbia University.

The website is available at <http://ubiquitousgenomics.teamerlich.org>.

The source is available at <https://github.com/erlichya/ubiquitousgenomics>.

### Testing/Building the website locally

Install Jekyll (for more details see <http://jekyllrb.com/>):

    gem install jekyll

Clone the repository:

    git clone https://github.com/erlichya/ubiquitousgenomics

Build the website with Jekyll:

    cd ubiquitousgenomics
	jekyll build

Serve (and monitor changes) with:

    $ jekyll serve
	...
    Server address: http://0.0.0.0:4000/
    Server running... press ctrl-c to stop.

Then view the website at <http://localhost:4000>.

### Sending updates/fixes

Fork the repository on Github (i.e. create your own clone of <https://github.com/erlichya/ubiquitousgenomics>).

Clone *your* repository to your local computer (replace USER with your github
user name):

    git clone https://github.com/USER/ubiquitousgenomics
	cd ubiquitousgenomics

Modify a file, test updates with local jekyll build (see more details above):

    jekyll serve

When the changes are acceptable, commit the updated files:

    git add FILE1
	git add FILE2
	git commit -m "short description of the changes"

Push changes back to Github:

    git push

Back on the GitHub website, you should see a green "create Pull Request" button
in your repository. Click the button to send the Pull-Request back to Yaniv's
repository. If your changes are accepted, they will be merged into the `master`
branch of he main repository.

