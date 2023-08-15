# teamsdashboard

 ## Prerequisites:
- Microsoft Developer Account incl. E5 Sandbox (tricky set up)
- VS Code Extension: Teams Toolkit
- node.js version 16,18
- ideally: able to sideload apps in Teams (depends on organization)

 ### Create a Dashboard App
- Tab > Dashboard > Typescript
- > creates boilerplate with one list widget and one chart widget


### Teams channel tab

some ideas:
- [Microsoft Teams Dev Docs] (https://learn.microsoft.com/de-de/microsoftteams/platform/tabs/design/tabs)
- [Microsoft Teams Sample Tab with JS] (https://github.com/OfficeDev/Microsoft-Teams-Samples/blob/main/samples/tab-channel-group-quickstart/js/src/components/Tab.js)
- [Microsoft Teams Sample Tab with TS] (https://github.com/OfficeDev/Microsoft-Teams-Samples/blob/main/samples/tab-channel-group-quickstart/ts/README.md)

###Kanban board created with React beautiful Dnd & styled components
- recreated this [tutorial] (https://www.youtube.com/watch?v=SJTazZUQVDE)
- [Code](https://github.com/ksekwamote/kanbanBoard/blob/master/src/assets/components/Kanbanboard.jsx)
- this kanbanboard uses a fake REST API to create to-dos and tasks can´t be moved to backlog at the moment

- research is needed to figure out if React Beautiful DnD can be implemented inside the Teams Toolkit or if there is a more useful alternative

### Pomodoro Timer as a dashboard widget

- [Samples] (https://reactjsexample.com/tag/pomodoro-timer/)
- [Freshman Pomodoro Timer] (https://freshman.tech/pomodoro-timer/)

### Pomodoro Timer created as Basic Tab with Fluent UI components

- implement Pomodoro Widget as part of the Welcome.tsx file
- the pomodoro timer:   - consists of three phases (work phase = Pomodoro = 25 min; short break = 5 min; long break = 15 min)
                        - a short break follows after every Pomodoro; after every fourth Pomodoro phase follows a long break
                        - the screen shows the remaining time of the work interval or break as a countdown
                        - you need to be able to start the timer, stop it and skip to the next phase
  (optional):           - input field to write down the specific task you want to resole during the pomodoro interval


# Using Git in projects


- getting current version of project: `git checkout main` -> `git pull`
- create new branch you can work on +  directly switching to it: `git checkout -b <branch name>`
- checking on which branch I am currently on: `git status`
- the feature is ready for reviewing: `git add .` -> `git commit -m "commit message"` -> `git push`
- if the feature branch is created locally first, you need to set the remote branch as upstream branch: `git push --set-upstream origin <branch name>`
- (after that create pull request via github.com by directing to the project -> choosing/opening the feature branch -> create pull request (if applicable request particular person to review the code)) 

  
