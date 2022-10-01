<p align="center">
<a href="https://www.hibatapp.com" target="_blank">
<img src="https://www.hibatapp.com/logo.png" width="400">
</a>
</p>

<p align="center">
<a href="https://github.com/HibatApp/hibat-backend/pulls">
<img src="https://img.shields.io/github/issues-pr/HibatApp/hibat-backend" alt="Pull requests">
</a>
<a href="https://github.com/HibatApp/hibat-backend/blob/master/LICENSE.md">
<img src="https://img.shields.io/github/license/HibatApp/hibat-backend" alt="License">
</a>
</p>
<br />
<br />

## About Hibat Platform

This project is made to build a p2p charity platform to give away the extra or not needed stuff's who everyone has to those who need it.

## Project MindMap

<p align="center">
<a href="https://coggle.it/diagram/YV5X0o8N-09ZyNIG/t/stuff-donation-p2p/e025acfd67834e0ec97792bf97fc095feee1be29d45a34b2af29ce161d30effb" target="_blank">
<img src="https://www.hibatapp.com/mindmap.png" width="100%">
</a>
</p>

## Links

-   Community
    -   [Telegram Channel](https://t.me/hibatApp)
    -   [Telegram Group](https://t.me/hibatAppGroup)
    -   [Website](https://www.hibatapp.com)
    -   [Trello](https://trello.com/hibatapp)
    -   [GitHub](https://github.com/HibatApp)
-   Repo's
    -   [Backend](https://github.com/HibatApp/hibat-backend)
-   Boards
    -   [Design tasks](https://trello.com/b/5kVdKkRu/hibat-backend)
    -   [Backend tasks](https://trello.com/b/meDFoyZr/hibat-design)
    -   [DevOps tasks](https://trello.com/b/0Or88rGX/hibat-devops)
-   Documentations
    -   [Project MindMap](https://coggle.it/diagram/YV5X0o8N-09ZyNIG/t/-/e025acfd67834e0ec97792bf97fc095feee1be29d45a34b2af29ce161d30effb)
    -   [Project Description](https://docs.google.com/document/d/1VMg3Wb8KCBJfmt14IMkx7FtYDIkq3-QOg5L-Ejh564w/edit?usp=sharing)
    -   [API Spec's Sheet](http://apidocs.architweb.com/?url=hibat-backend/apis.yaml)
    -   [Database ERD](https://dbdiagram.io/d/6337f5ea7b3d2034fffebf3b)

## Who can join the projects

The project is open for all, anyone can contribute.

## Contributing

Thank you for considering contributing to Hibat Platform.
To start you can follow this steps:

-   fork the repo (by clicking on the fork button on the Repo page)
-   clone your repo to your device
-   pick a task from [Trello board](https://trello.com/hibatapp) or one issue on [gitHub issues](https://github.com/HibatApp/hibat-backend/issues)
-   write your code, test, commit and push
-   create a pull request to main Repo, someone should review and approve or give you feedback how to improve your code

## API Spec's contributing guideline

-   Use [Petstore example](https://editor.swagger.io/) From swagger as reference (convert it to openApi 3 from Edit menu)
-   Download OpenApi extension for your IDE, ex [OpenAPI (Swagger) Editor](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi) which give you: error highlights, auto fixing, live view, security audit and **code score**.
-   The end point should be POST, GET, PATCH, PUT /user, not /signin /signup /getUserInfo /updateUser
-   It would be easier for Frontend developers if we used **requestBody** content as `application/x-www-form-urlencoded` instead of `application/json`, you can then test it using form inputs
-   please use camelCase, like fullName instead of full_name, as in [Petstore example](https://editor.swagger.io/)
-   please add the main details about properties, like maxlength or pattern, depending on property type, in vs code you can use CTL + . to quick fix it, you need openApi extension to be installed first
-   it would be better to use 400 instead of "400" for http response code
-   after finish, try to format the code (Alt+Shift+f in vscode)
-   before submit your pull request, make an audit test, using the openApi extension (click on purple icon to the top right), keep the code score over 50 out of 100 😊

## Contributors

This project exists thanks to all the people who contribute.

<a href="https://github.com/HibatApp/hibat-backend/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=HibatApp/hibat-backend" />
</a>

## License

Hibat Platform is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
