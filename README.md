# zmags-hackernews-challenge

To run this application clone or download the repo and run 'npm start' from the terminal, while inside the application directory. This command starts a simple Express server I have included to statically serve the build file created via webpack. Navigate to localhost:3000 and you will see the application. No dependencies need to be installed to run the application this way.

By default, the articles presented are sorted by story score. However, you also have the option to sort by timestamp and to sort by author karma.

I built this application using React. Tests are included and can be run via 'npm test' from the terminal, while inside the application directory. 

While 'npm start' statically serves a webpack build of the application, I have also included the development files (in the folder 'js', which also includes the test files). 

You can run the application using the webpack development server by running 'npm run dev-watch' from the terminal, while inside the application directory. You can create a new bundle by running 'npm run build-prod' from the terminal, while inside the application directory. However, to run these commands you will first have to install the necessary dependencies by running 'npm install' from the terminal, while inside the application directory.
