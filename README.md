# Project Freedom
## Final Project for Linear Algebra for Data Science

Joint effort between Chris Bloodsworth and Jonathan Levy.

Implementation of a simple neural network in numpy, without the aid of traditional libraries (keras, pytorch, etc.)

## Workflow

For now, the workflow goes something like this:

- Make changes to your own branch, push to it. I want to keep it simple with
    just developer-specific branches for now, though we can transition to
    feature branches if the need arises.
- Try to make sure it adheres to black formatting - if not, it'll get 
    auto-formatted on pull request.
- When you've made your changes and are ready, make the pull request to main. 
    The auto-formatter will run and reformat your code if necessary. You will
    need the other developer's approval to merge into main.
- After the pull request is merged, **make sure to run `git pull` on your
    own branch.** If the formatter made some changes, you'll need to pull
    those on your local repo.
