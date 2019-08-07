# gcp-movies-app

## What's inside the box

- data
  - `marvel.json` - contains mock data
- views
  - `index.pug` - template file used to display mock data to the user
- `index.js` - entry point

## Run locally

Run

```
npm install
npm start
```

and in your terminal you should see something like this

```
Serving function...
Function: marvelFilmAPI
URL: http://localhost:8080/
```

It means that the application is running and it's reachable at that URL.

Image here

Go to the URL and type

```
http://localhost:8080/?film=2
```

where `?film=2` is the **query**. Now you should display another movie

Image here

In your terminal you will find some logs like

```
Movie Ref endpoint called - Query film: 0
Movie Ref endpoint called - Query film: 0
Movie Ref endpoint called - Query film: 2
Movie Ref endpoint called - Query film: 0
```

This means that the entry point is working properly getting the right movie from the JSON file we provided.
