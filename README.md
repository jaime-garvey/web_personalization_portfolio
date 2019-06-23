# Web Personalization: E-Commerce Online Page Recomendations

![Flask App Home Image](https://github.com/jaime-garvey/web_personalization_portfolio/blob/master/static/flask_app_home_image.png)

Table of Contents
=================

  * [Motivation](#Motivation)
  * [Target Question](#Target-Question)
  * [Data](#Data)
  * [Methodology](#Methodology)
  * [Web App (Flask)](#Web-App-Flask)
  * [Impact](#Impact)


## Motivation

Consider the role of a content or growth marketer, whose goal is to provide content for every stage of the buyer's journey. Some articles may promote awareness about your industry by answering high-level questions (e.g., What, How-type questions), while other content may appeal to the consideration phase (e.g., comparing solutions). 

The marketer ultimately has a goal to inspire some action (e.g., buying a product, downloading a white paper, booking a demo). However, the ideal path that is intended for the user to follow in their exploration of a product or service may be far different than their actual path. 

Consider these example page flows from the Google Merchandise Store to illustrate how similar exploratory paths can results in vasly different performance.

![Page Flow Example](https://jaime-garvey.github.io/images/portfolio/web/page_flow.gif)

## Target Question

How can we recommend relevant content to online visitors that maximizes business value (or in this case, page value)?

## Data

One million user sessions from the Google Merchandise Store acquired using Big Query and a Google Analytics demo account.

![Data Overview](https://jaime-garvey.github.io/images/portfolio/web/g_data.gif)

## Methodology

We can think of the model in two major steps: (1) building a classifier to predict the next web page a visitor is likely to land on (relevant pages) and (2) a reinforcement learning model to help us recommend the optimal next page (pages that maximize the probability of landing on high-value pages).

![Data Overview](https://jaime-garvey.github.io/images/portfolio/web/web_methods.gif)

## Web App (Flask)

Here is a preview into a web application that allows you to explore the GStore web page clusters as a network and visualize the optimal next-page recommendations.

[Click Here for Web App Demo](https://jaime-garvey.github.io/images/portfolio/web/web_app.gif)

## Impact 

Let's explore some of the impacts that these recommendations could have in terms of sales (page value) and engagement (time on page and bounce rate).

![Impact](https://jaime-garvey.github.io/images/portfolio/web/web_impact.gif)
