<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRs547Zn_Tx7c9xcEV-fJLHIKPNQ_HbxqoUqYWpOZ0u0nhZdaNxnqcUdA6FLPoLBYra-A&usqp=CAU" width="20%" height="20%">
This is a web application built using Next.js. The application uses React as the frontend library, Node.js as the backend, and various other libraries and technologies.

## Getting Started
To get started, follow the steps below:

Clone this repository to your local machine using git clone
```sh
git clone https://github.com/ferzap/promptopia.git
```
Navigate to the project directory using 
```sh
cd promptopia
```
Install the dependencies using 
```sh
npm install.
```
Start the development server using 
```sh
npm run dev.
```
Open http://localhost:3000 in your web browser to view the application.

## Folder Structure
The project is organized into various folders and files. The main folders are:
- **components** : This folder contains all the React components used in the application.
- **app** : This folder contains all the pages of the application, which are automatically routed by Next.js.
- **public**: This folder contains all the static assets of the application, such as images and fonts.
- **styles**: This folder contains all the CSS files used in the application.

## Dependencies
The project uses various dependencies, including:

1. **next**: The main Next.js library.
2. **react**: The main React library.
4. **dotenv**: A library used for managing environment variables.
5. **tailwindcss**: A library used for styling the React components.

## Environment Variables
The application uses environment variables to store sensitive information, such as API keys and database credentials. These variables are stored in a .env file in the root directory of the project. An example of this file is provided in .env.example. To use the application, you will need to create a new .env file and fill in the necessary variables.

## Building and Deploying
To build the application, use the command npm run build. This will create a production-ready version of the application in the out folder. To deploy the application, copy the contents of the out folder to your web server or hosting service.
