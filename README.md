# Cliff Effects Tool UI

How to work on the tool on your local machine:

1. Make sure you have [Node.js](https://nodejs.org/en/) installed (I used v6.11.1).
2. Open the node command prompt and change into the directory that you want to clone the app to.
3. Clone the repo to your local machine with `git clone https://github.com/adanaher/cliff-effects.git`.
4. Change into the new app directory with `cd cliff-effects`.
5. Change to the master branch with `git checkout master`.
6. Install all necessary node packages with `npm install`. This might take a few minutes.
7. Type `npm start` to run the app in your browser in dev mode. It is set up for live updating if you make changes to the code.
I would also recommend getting the [React Developer Tools](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=4&cad=rja&uact=8&ved=0ahUKEwiZ__6Vg_jVAhWQ14MKHczrDtoQFgg4MAM&url=https%3A%2F%2Fchrome.google.com%2Fwebstore%2Fdetail%2Freact-developer-tools%2Ffmkadmapgofadopljbjfkapdkoienihi%3Fhl%3Den&usg=AFQjCNEv0udXgBoaukzJa59I_vufhScUbQ) extension for Chrome.
8. Type `Ctrl-C` to stop the app from running.
9. Type `npm build` to build a production version of the app.

Note that I also have it set up to deploy automatically to github pages with the command `npm deploy`.
