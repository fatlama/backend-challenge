# Backend Challenge
## Introduction
Fat Lama relies heavily on our search in order for users to be able to find the items they need. The main two factors in the search are:
- **Text match**: the user types a word or phrase that they want to find, and the search returns items that match this.
- **Location**: the user indicates their location (through geolocation or through typing in the location search box) and the search returns items near the user

On the production web & mobile app there are other factors that come into play such as lender rating, response time, categories, time since listing, and more. For this challenge though, we want you to focus only on the two main factors given above.

## The Challenge
We want you to build a `GET /search` endpoint that will return the most appropriate 20 items given `searchTerm`, `lat` (latitude) and `lng` (longitude). e.g. `/search?searchTerm=camera&lat=51.948&lng=0.172943`. It is up to you to decide how to weight the two factors to return the most relevant results. We have provided you with a sqlite database containing just under 2000 items with the relevant fields.

When you are finished, write up a short summary of why you made the choices you did in terms of technology and design. This should be no more than 500 words.

## Things to think about:
- Think about points of failure and how your endpoint will perform under load.
- Testing: use whatever tools you prefer to test your code appropriately
- Try to implement appropriate [separation of concerns](https://effectivesoftwaredesign.com/2012/02/05/separation-of-concerns/) & modular code
- Think hard about naming of functions and variables. Your code must be readable
- Code style & file structure is up to you, but make sure it is consistent and easy to understand

## Checklist for Challenge
- [ ] Duplicate this repo (please do not fork it, see [instructions](https://help.github.com/articles/duplicating-a-repository/)). Bitbucket offers free private repos if you don't want to use a public one.
- [ ] Build API endpoint for Fat Lama search
- [ ] Ensure all code is sufficiently tested
- [ ] Write brief summary on the approach you took and the tools you used (max 500 words)
- [ ] Send us a link to your new repo.
