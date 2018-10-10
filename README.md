# Wiki 2018
## Setting up for local development
1. Download and install Github Desktop from [here](https://desktop.github.com/).
2. Open Github Desktop and sign in with your github account.
3. Click "Clone a Repository". From the list select `marcusrettig/wiki2018`. Select a directory to store the project in. Hit "Clone".
4. Download and install NodeJS from [here](https://nodejs.org/en/download/current/).
5. **(Windows)** Open "Command Prompt" and open the project directory by typing `cd C:\Users\Marcus\Documents\wiki2018` replacing `C:\...` with the path to the directory you chose in step 3.
5. **(Mac)** Open "Terminal" and open the project directory by typing `cd /Users/marcus/Documents/wiki2018` replacing `/Users/...` with the path to the directory you chose in step 3.
6. Enter `npm install` to install project dependencies.

## Running the website locally
7. Do step 5 above and enter `npm start`. This should build the website and open int in the browser.
8. Now make changes to the files in `app/`. Every time you change a file the website will rebuild and reload automatically.
9. When you want to publish your changes, in Github Desktop enter short message describing what you've done and press "Commit to master". After that you have to press "Push origin" to make your changes available to everyone else.

## Editing files

You can use whatever text editor you'd like. I recommend [VSCode](https://code.visualstudio.com/).

## Publishing to Wiki

1. Publish styles [http://2018.igem.org/Team:Lund/styles/wrapper](http://2018.igem.org/wiki/index.php?title=Team:Lund/styles/wrapper&action=edit)
2. In template bump style cache param [http://2018.igem.org/Template:Lund](http://2018.igem.org/wiki/index.php?title=Template:Lund&action=edit)
3. Publish page
