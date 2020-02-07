# fitbit_clockface_se
Special Edition Clockface for fitbit

## References
- [OSS Respository for Clockfaces and Apps](https://github.com/Fitbit/ossapps)
- [Fitbit organization](https://github.com/Fitbit)
- [Medium - develop fitbit clockface](https://medium.com/@jeremiecorpinot/beginner-guide-overview-develop-a-fitbit-clock-face-283ec7acd756)

## Guides
- [Getting Started Guide](https://dev.fitbit.com/getting-started/)
- [Guide for Fitbit devs](https://dev.fitbit.com/build/guides/)
- [Step-by-step creating fitbit clockface/app using node](https://dev.fitbit.com/build/guides/command-line-interface/)
- [Fitbit Studio for running and debugging apps in browser](https://studio.fitbit.com/projects)
- [Gallery App Manager (GAM) for publishing fitbit apps](https://gam.fitbit.com/apps)

## Setup Instructions
### prerequites 
1. 'node.js' needs to be installed on machine
2. download and install the simulator for [Windows](https://simulator-updates.fitbit.com/download/latest/win)

### steps
1. create a new github repo - "fitbit_clockface_se" with gitignore, readme and license (MIT license in my case) files.
2. while you are in new repo location, open CMD and run `npx create-fitbit-app <project-name>` command to create a fitbit app from scratch and follow the instructions asked in CMD. Please note fitbit will not accept app name with capital letters.
3. in case above command have created a new folder inside the repo, please copy and paste the folder and files outside of the new folder.
4. build your app using `npx fitbit-build` 
5. now its time to install your application on simulator and for that we need to enter into shell using `npx fitbit` this command will open new tab on browser and ask your credentails if you are not logged in. once login process completes, please close the browser tab.
6. once your login process completes, go back to cmd and you will find yourself logged into fitbit shell.
7. run `install` command in fitbit shell to install your application in simulator.
8. for progressive build and install you can run `bi` in shell 'bi -shortform for build and install'
