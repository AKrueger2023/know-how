# teamsdashboard

 ## Prerequisites:
- Microsoft Developer Account incl. E5 Sandbox (tricky set up)
- VS Code Extension: Teams Toolkit
- node.js version 16,18
- ideally: able to sideload apps in Teams (depends on organization)

 ### Create a Dashboard App
- Tab > Dashboard > Typescript
- > creates boilerplate with one list widget and one chart widget


###Teams channel tab

some ideas:
- [Microsoft Teams Dev Docs] (https://learn.microsoft.com/de-de/microsoftteams/platform/tabs/design/tabs)
- [Microsoft Teams Sample Tab with JS] (https://github.com/OfficeDev/Microsoft-Teams-Samples/blob/main/samples/tab-channel-group-quickstart/js/src/components/Tab.js)
- [Microsoft Teams Sample Tab with TS] (https://github.com/OfficeDev/Microsoft-Teams-Samples/blob/main/samples/tab-channel-group-quickstart/ts/README.md)

###Kanban board created with React beautiful Dnd & styled components
- recreated this [tutorial] (https://www.youtube.com/watch?v=SJTazZUQVDE)
- [Code](https://github.com/ksekwamote/kanbanBoard/blob/master/src/assets/components/Kanbanboard.jsx)
- this kanbanboard uses a fake REST API to create to-dos and tasks can´t be moved to backlog at the moment

- research is needed to figure out if React Beautiful DnD can be implemented inside the Teams Toolkit or if there is a more useful alternative

###Pomodoro Timer as a dashboard widget

- [Samples] (https://reactjsexample.com/tag/pomodoro-timer/)
  
