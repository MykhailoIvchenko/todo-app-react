1. The project implements React application for tasks-management using Mate academy server api.
After first loading you'll see an input which allows to create new todo after pressing Enter key.
The application lets you to add todos (and saves them on server).
You also can filter todos (select all, completed and active). The number of completed todos are shown
by the application interface. There is a checkbox which allows to make all todos completed and vice versa.
It looks "active" if all todos are completed.
Clicking at each separate todo circle (input) makes it completed or active.
Any todo can be removed by clicking "x" which appears on hover.
There is an ability to clear completed todos - clicking on button "Clear completed" removes all completed items from the list.
The button is visible if there is at least 1 completed item in the list.
Everything except the input to add new todo are hidden if there are no todos. But not if todos are just filtered out.
There is an inline editing for the TODO item. Double click on the TODO title makes it editable.
Enter saves changes
Esc cancels editing
Todo title can't be empty! If you click Enter with empty todo editing input, this todo will be removed.
If you edit todo and move focus out of the current todo, changes would be saved.

2. Technologies stack: HTML5, CSS3, SASS (I was provided with ready markup and SCSS), JS, TS, React.

3. Preview link: https:/mykhailoivchenko.github.io/todo-app-react/

4. The prototype of the application is here: http://todomvc.com/examples/vanillajs/

5. Using this app you will operate with my todos. User is fetched from server in the application.
It is possible to make another application (or upgrade this one) for user adding to server.
Also it can be added a field, which allows to select user and operate with his/her todos.
But there is no such aim of this application, so be comfortable to explote my todos)))
To add todo just write it into the field at the top of application.

IMPORTANT! If there are some problem with server you may use the app with local storage.
The link is here: https:/mykhailoivchenko.github.io/todo-app-react-local-storage/
