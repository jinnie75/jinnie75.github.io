---
layout: post
title: "6 Months in Customer Reviews"
date: 2023-10-28
feature_image: images/6mo review_img/6mo review_cover.png
tags: [product managment, team management, iterative problem-solving]
---

For 6 months, our team of 4 people worked on maximizing the quantity and quality of customer reviews in an e-commerce platform, to leverage them in increasing overall revenue. We learned: 
- Small changes in user interfaces, if designed well, can significantly change user behavior.
- Product discovery and improvement is a continuous, iterative process.

<!--more-->

***

> 🖋️ Please note that the following is a summary of the overall process of breaking down an ill-defined business problem into specific opportunities to tackle and iterating to create impact. For details on individual projects, please refer to the linked pages.

## Background

- ABLY is a Korean fashion & style e-commerce platform. 
It works on a C2C model where sellers can open their shops on the platform, and individuals can purchase products from multiple shops and write reviews.
- Senior management was determined that customer reviews were a crucial asset for purchase conversion and that more potential could be reaped from them. Consequently, our team was formed to maximize the volume and value of customer reviews.

## Project Overview
- Objective: Maximize the value of customer reviews in order to increase overall revenue.
- Duration: April - October 2023
- Role: Product Manager / Team Leader
- Team: 2 engineers, 1 product designer, 1 product manager
- Timeline
    - 3 phases, employing an iterative process of discovering - defining - developing - delivering, redefining problems and opportunities to tackle in order to achieve the objective.

{% include image_caption.html imageurl="/images/6mo review_img/our process.png" title="Our Process"%}

***

## Phase 1
{% include image_caption.html imageurl="/images/6mo review_img/our process_1.png" title="Our Process_Phase 1"%}

### Defining The Problem

#### Questions Asked

1. Who writes customer reviews, and why?
2. How do customer reviews contribute to revenue?
    - Are there some reviews more valuable than others? How so?
    - How do users make use of customer reviews in their purchase process?
3. What has worked in other similar situations?

#### Information Gathered
1. Data Analysis
    - Writing customer reviews: Customers who have made purchases were divided into two discrete groups - those who write reviews and those who never did.
    - Viewing customer reviews: The majority of customers checked customer reviews before making a purchase. We examined the average number of reviews users viewed per product view.
    - We defined the first few customer reviews as most impactful in increasing individual products’ purchase conversion via correlation analysis.
2. User Research
    - gathered qualitative data by directly asking questions in the customer community as an ‘undercover user’ on how they use customer reviews to help their purchase decisions
    - surveyed users on what information they gather from customer reviews, ranking their importance
3. Industry Research
    - researched successful incentives for customer reviews in other ecommerce platforms
    - narrowed down 2 effective incentives: cashback points, Amazon Vine Program
        - We already had a policy in place where users were rewarded cashback points for every review written (15 cents per review, 30 cents if a photo is included). So we considered making changes in the incentive system and implementing the Amazon Vine Program.

#### Defining How to Measure Progress
1. Quantity of customer reviews: Increase the % coverage of products with customer reviews.
2. Quality of customer reviews: Increase the % of reviews that are longer than 00 words and include product images.
3. Impact of customer reviews on revenue: Increase the purchase conversion rate of users who view customer reviews.

### Opportunities Explored

1. What should we do to successfully benchmark the Amazon Vine Program in our platform?
2. What other incentives can we provide in order to convince customers to write more helpful reviews?
    - product nudges - defaults, specific guidelines
    - social nudges - ‘recommend’ system (i.e. likes, comments, referrals), competition (i.e. ranking)

#### Product Design
{% include image_caption.html imageurl="/images/6mo review_img/pd1.png" title="Product Designs(1)" caption = "Nudges on the review writing screen doubled the volume of high-quality customer reviews."%}

### Results

1. A benchmark model of the Amazon Vine Program **was successfully implemented.** 
    - For more details on this project, check out [Project: AblyReviewer](https://www.notion.so/Project-AblyReviewer-d3f6908919cb49b095f384e867b778e3?pvs=21)
2. Social incentives only worked on a small group of highly-engaged users; carefully designed product nudges changed the behavior of the majority, writing more detailed product reviews and **doubling our Quality KPI(=% of detailed reviews) in 2 months.**

***

## Phase 2
{% include image_caption.html imageurl="/images/6mo review_img/our process_2.png" title="Our Process_Phase2"%}

### Redefining The Problem

#### Assessment

- Our team has successfully put measures in place for *those who were already writing reviews* to write better customer reviews. How can we convince *those who refrain from writing customer reviews in the first place* to start writing them?
- We’ve improved the quality of customer reviews by experimenting customers’ interactions with our platform - could there be ways to leverage sellers’ needs for customer reviews to create better reviews?

#### Questions Asked

1. For the user group who never writes reviews, what keeps them from writing reviews? 
2. What needs do sellers in ABLY or other e-commerce platforms have regarding customer reviews, and what efforts are they currently making to fulfill those needs?

### Opportunities Explored

1. How might we leverage product nudges to make it easier for unwilling users to start writing reviews for the first time?
2. How do we minimize the input on the seller’s side for them to gain customer reviews?

#### Product Design
- We reduced the depth in which user actions were required, and made a step-by step UI where you click one button at a time and nudges the user to write additional text to get cashback rewards.
{% include image_caption.html imageurl="/images/6mo review_img/pd2.png" title="Product Design(before)"%}
{% include image_caption.html imageurl="/images/6mo review_img/pd3.png" title="Product Design(after)"%}

### Results

1. Making the customer review writing prompt more visible and creating a step-by-step user flow **increased the number of reviews written per purchase by 48%**, without any increase in the incentive structure.
2. Created a customer review boosting product where over 10% of sellers employed to accelerate the speed of gaining customer reviews, with a **retention rate of 50%.**
    - For more details on this project, check out [Project: First Review Booster](https://www.notion.so/Project-First-Review-Booster-7579e21642d64780836dc89a71451c9c?pvs=21)

***

## Phase 3
{% include image_caption.html imageurl="/images/6mo review_img/our process_3.png" title="Our Process_Phase3"%}

### Redefining The Problem

#### Assessment
- Our team has made much progress in changing customers’ behavior in writing customer reviews, and providing sellers with more tools to improve their stores’ reviews.
- Could there be ways we could improve the process in which customers view and gather helpful information from customer reviews in their shopping journey?

### Opportunities Explored
- What blockers are users experiencing when they’re trying to view customer reviews?
- Are there more efficient ways to extract the information potential buyers are looking for in customer reviews?
- If the product the potential buyer is viewing lacks critical information for purchase decisions, are there ways we can provide substitute info using customer reviews?
- Will such opportunities have a positive impact on revenue?

#### Product Design
- We summarized the size information of users who wrote reviews and their evaluation on the ‘fit’ factor. This information was useful as most product pages did not provide detailed size information. Purchase conversion increased by 8%.
{% include image_caption.html imageurl="/images/6mo review_img/pd4.png" title="Product Design(3)"%}
- For products without any customer reviews, we provided substitute information with other reviews from the same store. Purchase conversion improved by 5%
{% include image_caption.html imageurl="/images/6mo review_img/pd5.png" title="Product Design(4)"%}

### Results

- We conducted multiple A/B tests on the interactions, to eliminate unnecessary steps or lags in users’ experience in viewing customer reviews. However, they made only incremental impact on purchase conversion.
- Features providing substitute information using customer reviews made meaningful impact on customer purchase conversion.


***

## Takeaways

- Small changes in user interfaces, if designed well, can significantly change user behavior.
- Product discovery and improvement is a continuous, iterative process.
