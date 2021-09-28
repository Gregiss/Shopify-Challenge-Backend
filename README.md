# Shopify-Image-Repository App

This project was inspired from the Fall 2021 Shopify Intern Chanllenge(https://docs.google.com/document/d/1eg3sJTOwtyFhDopKedRD6142CFkDfWp1QvRKXNTPIOc/edit)

## Challenge Description
Build an image repository.

You can tackle this challenge using any technology you want. This is an open-ended task.

Please provide brief instructions on how to use your application. We are a test driven environment, so ensure your challenge includes tests. Provide brief instructions on how to use your application, so that someone could use your application and understand how it works. 

## Project App Description
I built this image repository as the idea of collections of flower pictures name 'search garden'. The frontend is built via ReactJS and Material UI library; the database is hosted on firebase,with documents and images are stored in firebase store and firebase storage, respectively. Web app is hosted on firebase as well. Each document in firebase store has 3 attributes: "image name", "description", and "url".

Two features are implemented for this POC product:

(1) Search images. Clients can filter the images by image name.\
(2) Add images. Clients can upload images from local drive to firebase to this image repository.

## Run Scripts

To run this project, in your local terminal, do:
```
$ git clone https://github.com/Gregiss/Shopify-Challenge-Backend.git
$ yarn install
```
Now the web app is install to your local machine.

### `yarn run start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner as App.test.js in the root directory in the interactive watch mode.\
In App.test.js, three categories of tests are conducted:\
(1) Test the rendering of Home.js Component.\
(2) Test the the rendering and functionality of SearchBar.js.\
(3) Test the rendering of UploadButton.js.

