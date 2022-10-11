# GitColab

Smart GitHub. 

Organization GitHub equivalent is called a group. It's also a group of members with differents rights access.
But with GitColab your whole organization is organized like a filesystem. Repositories are just folders among all others. 
The GitColab web applcation allows you to easily broswe and modify this filesystem. GitColal is designed to natively works with Git but can be expanded for SVN. So you can rename, move, copy, edit and delete in one click. User can directly choose when he wants to commit these modifications.

An editor is fully integrated in the app and designed for each kind of file. Users can write and publish an extension to read other kind of file that are not natively supported.
User can choose one or more file (with mutual dependencies) of code to run together. Notebooks file are also interpreted and can be ran or edited like with Google Colaboratory.

Any program that will be ran from the browser application will be executed in a WebAssembly environment. Which makes that the client run the code on its machine. It allows him to have a better user experience as the the program run faster and also offline. For the users with a low RAM the code will be executed on the server into a Docker container.
