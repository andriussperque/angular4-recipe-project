# angular4-recipe-project

<b>Plan your project with Angular using Components</b>   

1 - The First thing it is needed to be done when we start developing an angular web-app single-page is to decide the structure of the app considering the main components it will have:

which Features?
which components?
Which are the components of the features?
which models are we going to use in our application?


2 - Main concepts to take in consideration:
ViewEncapsulation
DataBinding
Single-page
Local References.
Local References using ViewChild.
NgContent hook --  [todo][review]
Ng onInit

3 - What not to do!:
Do not write in the DOM using the ViewChild.


<b>Main console commands:</b>

npm install npm@latest -g --- install latest version of npm


npm install -g @angular/cli --- install latest version of angular-cli


ng new recipe-app  --- create a new project 


npm install -save bootstrap  --- add bootstrap to the project and json package
.angular-cli.json => Styles =>  Add: "../node_modules/bootstrap/dist/css/bootstrap.css",


ng g c ComponentName --spec=false  --- create a new component without test specification


npm start  --- start server.

