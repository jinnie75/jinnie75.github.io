---
layout: post
title: "Project: First Review Booster"
date: 2023-09-01
feature_image: images/frb/img_popup.png
tags: [product managment, business design]
---

We explored the respective needs of customers and sellers on the e-commerce platform, and created a solution that satisfies both. We learned that splitting a problem into smaller parts by groups with different needs can give direction into what can be done to solve them.

<!--more-->

***

## Background
- ABLY is a Korean fashion & style e-commerce platform. 
It works on a C2C model where sellers can open their shops on the platform, and individuals can purchase products from multiple shops and write reviews.
- Our team’s objective was to maximize the value of customer reviews in order to increase overall revenue.
    - Tapping into sellers’ needs to gain better customer reviews, our team successfully implemented a program where sellers could get detailed customer reviews in exchange for a sponsorship, to gain traction in their product sales ([Project: AblyReviewer](https://www.notion.so/Project-AblyReviewer-d3f6908919cb49b095f384e867b778e3?pvs=21)). Once sellers signed up for the program, we managed a 40% retention rate. However, the number of sellers that would sign up for the program for the first time hit a ceiling.

## Project Overview
- Duration: July - September 2023
- Role: Product Manager / Team Lead
- Team: 2 engineers, 1 product designer, 1 product manager

### Problem Definition
How might we provide a tool to help sellers gain better customer reviews, that more sellers will use?

## Preliminary Research
1. Survey
    - Our team conducted a survey on the sellers’ portal to find answers to the following questions:
        1. Why weren’t sellers signing up for the AblyReviewer Program? 
            - Awareness wasn’t a problem, because 90% of the repondents knew about this program, and the satisfaction level was also benign (80%).
            - However when we split up the responses according to the respondents’ market revenue, sellers in the median range (40~60 percentile) had a relatively lower awareness and satisfaction rate.
        2. Could it be that sellers don’t think of customer reviews as important in the first place? 
            - Sellers ranked customer reviews as one of the most important factors deciding a product’s sales.
            - However, the majority thought the sheer number of reviews was more important than the individual reviews’ content.
    - Conclusion: Raising review quality, which was AblyReviewer’s main value proposition, wasn’t appealing enough for sellers of low-to-medium revenue volumes to invest in, compared to other important factors such as increasing the sheer numbers of reviews written.
2. Competitive Research
    - Our team researched on what review-related tools other e-commerce platforms were providing. Most fell into those 3 categories:
        1. Sellers can run ‘Best Review Contests’ on their products: users write reviews, sellers pick their favorite ones and are rewarded a small prize
        2. Sellers can add comments to customer reviews: sellers thank users for helpful products, and sometimes offer additional rewards on their next purchases
        3. Sellers can award users who write customer reviews with bonus cashback points
    - What differentiated tools that were widely used from those that weren’t were not in how noticeable these measures were to customers (all three offered petty benefit on the customer’s end), but in how little effort the seller had to put into employing the tool.
        - The first 2 measures were the least effective in that sellers had to read all the reviews and manually pick out those to react to.
        - The conversion rate for the 3rd category differed per platform, depending on what process the seller had to go through to set the bonus reward points on each product. The shorter the process, the more sellers used this feature.
3. Takeaways
    - We need to work on a product that focuses on increasing the number of customer reviews, in a way that is cheaper than the current AblyReviewer program.
    - It should take the least amount of effort for the seller to set up.

## Testing

### Hypothesis 1 (The Customer Side)

> Will doubling the cashback reward for writing the first review speed up the pace of customer reviews gained?

- Users were already being rewarded cashback points for every review they wrote (aka review points - 15 cents per review, 40 cents if a photo is included)
- Keeping in mind that sellers consider the sheer number of customer reviews important, we wanted to test if doubling the review points (30-80 cents per review) could incentivize customers to write reviews faster.

#### MVP
- We named this feature the ‘First Review Booster’.
{% include image_caption.html imageurl="/images/frb/product side.png" title="First Review Booster Results" caption="How the First Review Booster Works"%}
- Sellers can pick products to apply the first review booster. They are charged upfront 10 cents per product. They don’t have to do anything afterwards - ABLY rewards the user who writes the first review with double review points.
- Experiment Design: Since we had no information on what sellers will sign up for this tool, we selected products at random to apply this feature and test our hypothesis.


#### Results
- The time it took until the first review was written was reduced by half. We decided to put this feature in production.

### Hypothesis 2 (The Seller Side)
> If we minimize the steps to apply this feature, will more sellers use it?

- Our MVP feature required the following steps to use:
    - log into the sellers portal → click on the ‘first review booster’ menu → select products to apply the first review booster on
- We hypothesized that there will be much more sellers willing to pay 10 cents per product to speed up customer reviews, they just don’t know about this product yet. We surmised that placing the application form in sellers’ routine workflows will increase the conversion rate without interfering with work that needed to be done.

#### Results
The conversion rate increased from 2% to 15%, without any decrease in other seller activities.
*(Product designs cannot be disclosed due to confidentiality issues)* 

{% include image_caption.html imageurl="/images/frb/results.png" title="results of first review booster" caption="blue: the number of products that registered for the First Review Booster / orange: the percentage of active markets that registered for the First Review Booster"%}

## Takeaways

- Splitting a problem into smaller parts by groups with different needs can give direction into what can be done to solve them.