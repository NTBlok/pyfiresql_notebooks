# pyfiresql-notebooks

This repository is a starter for Juptyer notebooks for querying Firebase using pyfiresql and a credentials.json file that should be added to .gitignore.

To run the notebooks, use the following command:

~~~
jupyter notebook --ip=localhost --port=8089 --no-browser --allow-root --NotebookApp.token=dev
~~~

To generate a credentials.json file, follow these steps:

1. Go to the Firebase Console (https://console.firebase.google.com/)
2. Select your project
3. Click on the gear icon (Settings) in the left sidebar
4. Click on the Service accounts tab
5. Click on the Generate new private key button
6. Save the JSON file as credentials.json and place it in the same directory as the notebooks

Remember to keep credentials.json out of version control (add it to .gitignore)