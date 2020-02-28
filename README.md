# Backend Challenge

## Introduction

Fat Llama relies heavily on our search in order for users to be able to find the items they need from other users. Our search must return a list of items matching a given search term, as well as displaying certain information about the item owners (see example Item Card below).

On the production web & mobile app there are other factors that come into play such as lender rating, response time, categories, time since listing, and more. For this challenge though, we want you to focus only on the above.

## The Challenge

We want you to build a `GET /search` endpoint that will return the most appropriate 20 items given a `searchTerm`, e.g. `/search?searchTerm=camera`. The items returned must contain the owner's information so we can correctly display them in the Fat Llama frontend. You are not required to incorporate any complex fuzzy text matching.

The data returned should be sufficient for the frontend to construct the following item card:
![alt text](https://fat-lama-assets.s3-eu-west-1.amazonaws.com/itemCard.png "Item card")

You are provided with two csvs containing approximately 1000 items and 300 users. Its is up you how your API handles these.

When you are finished, write up a short summary of why you made the choices you did in terms of technology and design. This should be no more than 500 words.

## Things to think about:

- Think about points of failure and how your endpoint will perform under load.
- Language/frameworks: Node.js with Typescript is preferable, but if you haven't worked with Typescript, Node.js + Javascript is also acceptable.
- Testing: use whatever tools you prefer to test your code appropriately
- Try to implement appropriate [separation of concerns](https://effectivesoftwaredesign.com/2012/02/05/separation-of-concerns/) & modular code
- Think hard about naming of functions and variables. Your code must be readable
- Code style & file structure is up to you, but make sure it is consistent and easy to understand

## Checklist for Challenge

- [ ] Duplicate this repo (please do not fork it, see [instructions](https://help.github.com/articles/duplicating-a-repository/)). Github/Bitbucket offer free private repos if you don't want to use a public one. Please do not name your repo 'fat llama' or anything similar (we don't want future candidates copying your code).
- [ ] Build API endpoint for Fat Llama search with according to above specifications
- [ ] Ensure all code is sufficiently tested
- [ ] Write brief summary on the approach you took and the tools you used (max 500 words)
- [ ] Include instructions on how to build/ run your solution
- [ ] Send us a link to your new repo.
