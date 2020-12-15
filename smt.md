![Social Media Toggle by Eric Schmiel logo](https://eschmiel.github.io/smt-logo.png)

## A web app built with React, Node.js, Express.js, Passport and PostgreSQL

---
[Web App](https://studioschmiel.com/socialMediaToggle.html) | [Github Repo](https://github.com/eschmiel/smtBackendPublic)

## What is it?

The Social Media Toggle was initially conceived as a tool for live streamers. Live streamers commonly post on social media platforms like Twitter to let their audience know when they're live streaming, however;
when the streamer is finished, it is often good practice to delete their going live notification afterwards. Followers who click a live streaming link only to find a dead stream are more likely to ignore these notices in the future
and if the live streamer isn't an organic user of the platform, it's easy for their social media profiles to become cluttered with nothing but dead going live notifications. This may give potential followers the impression that
the profile is just going to spam them and they'll avoid following the streamer.

Additionally, streaming sessions can be quite long and encompass many different kinds of content. Some streamers may do some graphic design work for the first hour of a stream, switch to playing a game for another hour and then wrap
up a session by doing some commentary. Managing your social media mid-stream to keep the broader audience updated on what kind of content you're providing can be tedious and upset the general flow of the stream. The Social Media Toggle
was built to address these problems.

The Social Media Toggle allows users to manage their profiles in a quick and convenient way. By creating pre-written tweets before they start streaming, users can quickly update their going live notices on Twitter by toggling
outdated notices off and toggling new tweets that represent the current state of the stream on with the click of a button. Once they're finished streaming, they can simply toggle their dead streaming notices off.

<br/>

[![gif showing off the MVP of the SMT](https://eschmiel.github.io/smt-mvp.gif)](https://eschmiel.github.io/smt-mvp.gif)

<br/>

---

## Use Case diagram and documents

<br/>

[![Use Case Diagram](https://eschmiel.github.io/SMT-use-case.svg)](https://eschmiel.github.io/SMT-use-case.svg)

<br/>

[![Create Account Use Case](https://eschmiel.github.io/use-case-create-account.png)](https://eschmiel.github.io/use-case-create-account.png)

[Use Case documents](https://drive.google.com/drive/folders/1E_K8H-9OMsDODiz7Er63GX56ch23hH9I?usp=sharing)

---

## The Database

- PostgreSQL
- Deployed on AWS

<br/>

[![SMT Database diagram](https://eschmiel.github.io/SMT-Database.svg)](https://eschmiel.github.io/SMT-Database.svg)

---

## The Backend

- Node.js
- Express.js
- A RESTful API
- Invokes external REST services (Twitter)
- Handles Oauth authorization
- User account system with user sessions and authentication (built with Passport.js)
- Implements CRUD operations through API
- Has a SQL manager

<br/>

[![SMT backend logical diagram](https://eschmiel.github.io/SMT-logical-diagram.svg)](https://eschmiel.github.io/SMT-logical-diagram.svg)


<br/>

[![SMT services diagram](https://eschmiel.github.io/SMT-services.svg)](https://eschmiel.github.io/SMT-services.svg)

<br/>

[![SMT tweet DAL](https://eschmiel.github.io/SMT-tweets.svg)](https://eschmiel.github.io/SMT-tweets.svg)

[![SMT accounts DAL](https://eschmiel.github.io/SMT-accounts-DAL.svg)](https://eschmiel.github.io/SMT-accounts-DAL.svg)

<br/> 

---

## The Frontend

- React
- UI populated through API calls
- Frontend user sessions in sync with backend user sessions through a session id cookie
- Manipulates database information and engages with Twitter through backend API calls

<br/>

[![gif showing off the UI of the SMT](https://eschmiel.github.io/SMT-UI-Demo.gif)](https://eschmiel.github.io/SMT-UI-Demo.gif)

![SMT UI Mockups](https://eschmiel.github.io/SMT-UI-Mockups.svg)

[![SMT UI diagram](https://eschmiel.github.io/SMT-UI.svg)](https://eschmiel.github.io/SMT-UI.svg)

---

[Home](https://eschmiel.github.io/)