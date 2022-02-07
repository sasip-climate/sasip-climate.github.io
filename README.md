# SASIP Website Source

![github pages](https://github.com/sasip-climate/sasip-climate.github.io/actions/workflows/build-and-deploy.yaml/badge.svg)


Visit the resulting website here : https://sasip-climate.github.io

This repo contains the source code for the SASIP website.
The site uses the [Hugo](https://gohugo.io/) framework.
The source files are written in markdown.
A [GitHub workflow](https://github.com/sasip-climate/sasip-climate.github.io/blob/master/.github/workflows/build-and-deploy.yaml) is configured to automatically build and deploy the website to <https://sasip-climate.github.io/> whenever the `master` branch of this repo is updated.

## Instructions for updating this site

To update the site, you need to change the source files on the `master` branch of this repository.
There are two ways to do this.

### Easy Way: Edit on GitHub

You can edit the source files directly on GitHub from your browser.
To do this, navigate to the `content` folder and click the edit button (little pencil symbol).
Make your changes in the editor.
When you are done, you can either "Commit directly to the `master` branch" or "Create a new branch for this commit and start a pull request".
A direct commit is appropriate for a minor change.
A pull request is best if you want your changes to be reviewed and approved by the rest of the team.
This method only allows you to update one page at a time.

### More specifically
 
- If you want to modify informations on people (https://sasip-climate.github.io/team/) :
  - modify or duplicate a md file in https://github.com/sasip-climate/sasip-climate.github.io/tree/master/content/team  
  - modify :
    - title : First Name Last Name
    - image : 'images/team/namefilephoto'
    - jobtitle : Job Title
    - weight : the rank at which the person must appear on the team page (after the WP leaders and managers, the order is alphabetical, see [this doc](https://docs.google.com/spreadsheets/d/1w82EaZQmBjFyVzfjqaY7-1bz1y92GWeop9Sr6i5NhjM/edit?usp=sharing) to get the rank and reorder the list when adding a new person)
    - after the --- Name of the Institution then ```*keywords, separated, by commas*```

  - upload the photo in [static/images/team](https://github.com/sasip-climate/sasip-climate.github.io/tree/master/static/images/team)

- If you want to modify the description of a work package (https://sasip-climate.github.io/research/) :
  - modify the corresponding md file in https://github.com/sasip-climate/sasip-climate.github.io/tree/master/content/research

- If you want to add a job position (https://sasip-climate.github.io/jobs/) :
  - create a md file that will look like https://github.com/sasip-climate/sasip-climate.github.io/blob/master/content/jobs/ponts.md, it will be added automatically to the list

After every modifications, have a look at https://github.com/sasip-climate/sasip-climate.github.io/actions to see if the workflow is complete (some extra time is needed for the modifications to appear on the website), we want a green light !


### Hard Way: Edit Locally

You can also clone this repository, make local changes, and then push them.
This is better for larger changes that involve multiple files and may need debugging.

Basic git workflow
```bash
git clone git@github.com:sasip-climate/sasip-climate.github.io.git
cd sasip-climate.github.io
# edit files with your text editor
git add [new or modified files]
git commit -m '<your commit message>'
git push origin master
```

If you want to make a large change, it may be best to discuss it first via pull request.
In that case you would want to create a new branch, push your branch to GitHub, and open a PR.
The GitHub docs on [creating a pull request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) are a useful reference here.

You can also build the website locally on your own computer.
This can be useful for debugging.
To do this, you need to first [Install Hugo](https://gohugo.io/getting-started/quick-start/).
You can then use the Hugo command line tools to do stuff like
```bash
hugo new content/<name of your page>.md # create a new page
hugo server -D # serve the website on http://localhost:1313/.
```
