# Repo comparing Vue.js Component Libraries

This repo was created from the [Vue Adopt Pets](https://github.com/gwenf/vue-adopt-pets) tutorial code that I created with Bootstrap Vue. It is now being used to compare Vue Component libraries by building same Vue app with each diffrent library. Feel free to raise an issue or contribute.

This is still in the early stages and needs a lot more work.

## Table of Contents

1. [Project Details](#project-details)
1. [Running Locally](#running-locally)
1. [Mockups](#mockups)
1. [Routes](#routes)

## Project Details

Each folder in this repo represents a different UI component library for Vue.js.

### List of UI component compared

* Typography
* Form Elements
* Buttons
* Modals
* Toastr Notifications
* Tables

## Running Locally

1. Clone this repo.
1. Navigate into one of the directories in the parent folder (e.g. `cd inkline-vue/`).
1. Install dependencies: `npm install`
1. Run the Vue application: `npm run serve`
1. Go to http://localhost:8080 in your browser to see the live application

## Mockups

<img src="home_page.png" alt="home page mockup">

<img src="pet_type_modal.png" alt="pet type modal mockup">

<img src="pet_table.png" alt="pet table mockup">

<img src="pet_form.png" alt="pet form mockup">

<img src="saved_pet.png" alt="pet saved success mockup">

<img src="pet_info.png" alt="pet info mockup">

*apply for adoption section is coming soon*

## Routes

* / --> Home Page/Landing Page
* /cats
* /dogs
* /pet-form -> enter pet info to put up for adoption
* /cats/:id or /dogs/:id -> view single pet information

