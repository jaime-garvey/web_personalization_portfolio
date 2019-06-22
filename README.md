# Web Personalization: E-Commerce Online Page Recomendations

## Motivation

Consider the role of a content or growth marketer, whose goal is to provide content for every stage of the buyer's journey. Some articles may promote awareness about your industry by answering high-level questions (e.g., What, How-type questions), while other content may appeal to the consideration phase (e.g., comparing solutions). 

The marketer ultimately has a goal to inspire some action (e.g., buying a product, downloading a white paper, booking a demo). However, the ideal path that is intended for the user to follow in their exploration of a product or service may be far different than their actual path. 


![Page Flow Example](https://jaime-garvey.github.io/images/portfolio/web/page_flow.gif)

## Target Question

How can we recommend relevant content to online visitors that maximizes business value (or in this case, page value)?

## Data

One million user sessions from the Google Merchandise Store acquired using Big Query and a Google Analytics demo account.

## Methodology

We can think of the model in two major steps: (1) building a classifier to predict the next web page a visitor is likely to land on (relevant pages) and (2) a reinforcement learning model to help us recommend the optimal next page (pages that maximize the probability of landing on high-value pages).
