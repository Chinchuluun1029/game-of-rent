
## To continue moving on with the project more smoothly, we should each fork our own repositories out of Jaden's and develop and create pull requests. To do so, we can do:

## How to fork from Jaden's repo:
1. Fork using the 'Fork' button on the top right of jdnhix/game-of-rent repo.
2. Clone the forked repository to your local machine. (Just like how you regularly clone)
3. Redirect to the cloned repo on your machine in the terminal.
4. Run the following commands to set up upstream

```sh
git remote add upstream https://github.com/jdnhix/game-of-rent.git
git fetch upstream
git rebase upstream/master
git push origin master
```

You might need to --force on git push initially

## To check if you have upstream branch set up:

```sh
git branch -a
```


## To install ESLint initially: 
```sh
npm i -g eslint
```

## To run linter (when in game-of-rent directory): 
```sh
eslint --ext .js src/
```