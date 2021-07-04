# Pupster App

In this activity we will work to create an entire React application from scratch, complete with routing and AJAX requests to the [Dog Ceo API](https://dog.ceo/dog-api/): an API for dog images.

## Instructions

- Start by scaffolding out a new starter React app by running the following command in your terminal `create-react-app pupster`.

- cd into the `pupster` directory and run the following command to install React Router and Axios [read axios use](https://www.npmjs.com/package/axios)
- if you prefer using fetch. [Read on how to use fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch):

  ```
  npm install axios react-router-dom
  ```

- **Recommended:** Add the Bootstrap and Font Awesome CDNs to your application's `index.html` file:

  - [Link to Bootstrap CDN](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
  - [Link to Fontawesome CDN](https://cdnjs.com/libraries/font-awesome)

  Example:

  ```html
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
    crossorigin="anonymous"
  />
  <link
    rel="stylesheet"
    href="https://use.fontawesome.com/releases/v5.15.3/css/all.css"
    integrity="sha384-SZXxX4whJ79/gErwcOYf+zWLeJdY/qpuqC4cAa9rOGUstPomtqpuNWT9wdPEn2fk"
    crossorigin="anonymous"
  />
  ```

- Open [https://pupster.netlify.com/](https://pupster.netlify.com/) in your web browser and take a few moments to study the example application. You will be basing your Pupster app off of this example.
- In case if link is broken. Please let us know, so we can fix it.

  - This example contains 3 routes:

    1. `/about`: A static welcome screen for visitors to the application.

    2. `/discover`: This page displays a photo of a random dog retrieved from the [Dog Ceo API](https://dog.ceo/dog-api/). This page contains 2 clickable buttons: one for passing or **thumbs-downing** a dog, and one for picking or **thumbs-upping** a dog. When either button is clicked, a new dog image is loaded from the API. If you "thumbs up" a dog, there is a 1 in 5 chance that the dog likes you too, and the friends count goes up by 1.

    3. `/search`: This page allows you to search the [Dog Ceo API](https://dog.ceo/dog-api/) for all dogs by breed. After a search is made, a list of all of the results appears underneath.

- Your Pupster app should implement each of these three pages and their basic functionality, **don't spend much time styling your app until you have completed everything else.**

- Your Pupster app should display a navigation bar that is present on every route.

- Begin with **routing**. For each route, render a different component for each page **without worrying** about building in any behaviors yet. Then work on implementing the most basic functionality for each page, one piece at a time.

## Hints

- Don't worry about styling or making things fancy at first. Just use Bootstrap classes and get the basic functionality for each page working. Get the app to work first, then come back and make it awesome.

- Use the <https://dog.ceo/api/breeds/image/random> endpoint to get a random dog image.

- Use the <https://dog.ceo/api/breed/hound/images> endpoint (replace "hound" with your breed of choice) endpoint to get an array of all available dog images of the selected breed.

- See <https://dog.ceo/api/breeds/list> for a list of all available dog breeds. You can test the `/search` page by searching for any of the breeds returned by this endpoint.

- Don't worry about your folder structure at first. But by at most 80% way through start organizing your folders and files.

- Utilize documentation if you're still unsure about how anything works:

  - [Axios](https://github.com/mzabriskie/axios)

  - [React Router](https://reacttraining.com/react-router/web/guides/philosophy)

  - [React](https://facebook.github.io/react/docs/hello-world.html)

  - [Dog Ceo](https://dog.ceo/dog-api/)

- Ask for help if you get stuck!

## Stretch Challenge (Bonus)

- Once you complete all of the basic functionality for this activity, work on adding additional styles and making it look great.

# Feedback

Do you have feedback that you want to share ? Slack us directly or in general channels.