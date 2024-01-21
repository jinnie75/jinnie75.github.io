---
layout: post
title: "Project: AblyReviewer"
date: 2023-07-01
feature_image: images/Project AblyReviewer/ablyreviewer cover.png
tags: [product managment, business design]
---

We benchmarked a preexisting successful solution and customized it to achieve our goals. We learned that in order to replicate someone else’s success, a careful analysis and reenactment of ‘why’ it worked is crucial.

<!--more-->

***

## Background
- ABLY is a Korean fashion & style e-commerce platform. It works on a C2C model where sellers can open their shops on the platform, and individuals can purchase products from multiple shops and write reviews.
- Our team’s objective was to maximize the value of customer reviews in order to increase overall revenue.
    - The current incentive structure we already had in place was cashback reward points for each review written. We researched for other options e-commerce services had employed to gain helpful customer reviews, and among those we came across the Coupang Reviewer Sponsorship Program, an adaptation of the Amazon Vine Program. (Coupang is the #1 e-commerce platform in Korea.)

## Project Overview
- Duration: April - July 2023
- Role: Product Manager / Team Lead
- Team: 2 engineers, 1 product designer, 1 product manager

## Preliminary Research
Our team defined the Coupang Reviewer Sponsorship Program as a success because:
1. It was a tried-and-true model that worked in 2 distinct e-commerce platforms (Amazon, Coupang). We could save time in achieving our goal by not reinventing the wheel.
2. The average Coupang customer review differed in the amount of information they held, compared to other platforms.

{% include image_caption.html imageurl="/images/Project AblyReviewer/compare.png" title="coupang v naver shopping" caption="customer reviews for the same product in Coupang vs. Naver Shopping (#1, #2 e-commerce platforms in Korea respectively)"%}

### Why did it work for them?        
Based on secondary information we gathered on the Coupang Reviewer (e.g. blog posts sharing ‘tips’ on the Coupang Reviewer Sponsorship Program) we defined the following as factors that drove the program to success: 
    
1. **Invitation based**, as opposed to opt-in based
    - Most platforms did have similar review sponsorship programs, but users had to pay constant attention to sign up for each product every time new products were added, and wait helplessly to be selected, among other applicants. This limited participants to the persistent few and random curious passersby.
    - Coupang’s program differed in that it invited a limited number of users, all eligible to get free products based on their track record of writing detailed customer reviews. Presenting the invitations as a ‘reward’ for the users’ actions increased the engagement of the program.
2. The **Competition** Factor
    - Users were ranked based on their efforts to write helpful customer reviews and the rankings were made visible. Users learned that invitations were granted exclusively to highly ranked users.
    - Once invited, users were motivated to step up their review-writing game to maintain or get more opportunities for free products.
    - This competition factor created voluntary *organic* high-quality customer reviews, in addition to paid reviews.
3. **Value Proposition**
    - for Customers: Coupang was already a platform often used to buy daily necessities. Writing a few lines of customer reviews for things you had to buy anyways, and getting free goods in return was a lot less effort compared to other side gigs of similar return size.
    - for Sellers: customer reviews are crucial in gaining early sales traction, and selecting users according to review rankings guaranteed the quality of customer reviews they’ll receive in exchange for the investment they make when they provide their products for free.

{% include image_caption.html imageurl="/images/Project AblyReviewer/ablyreviewer cover.png" title="hypothesis" caption="The true effect the competition factor has in customer reviews."%}            

### Will it work for us?

- How will we make the competition factor work in ABLY and gain more high-quality reviews than the actual number of reviews with sponsored products?
- Will the free products be enough incentive to write many high quality reviews, even though products sold in ABLY are not daily necessities like those sold in Coupang?

## Solution

> 📎 We named our adaptation of the Coupang Reviewer Trial program the ‘Ablyreviewer’ program.

1. a review scoring system & ranking
2. information page to motivate potential & current participants to keep writing reviews 
3. program page - users with invitations can get the products of their choice for free
4. reviewer sponsorship registration - seller admin page (undisclosed)

### Product Design
{% include image_caption.html imageurl="/images/Project AblyReviewer/compare.png" title="coupang v naver shopping" caption="customer reviews for the same product in Coupang vs. Naver Shopping (#1, #2 e-commerce platforms in Korea respectively)"%}
{% include image_caption.html imageurl="/images/Project AblyReviewer/compare.png" title="coupang v naver shopping" caption="Customer reviews for the same product in Coupang vs. Naver Shopping (#1, #2 e-commerce platforms in Korea respectively)"%}

### Additional Challenges

- Legal constraints: recipients of rewards worth over 50,000KRW are required to file income-tax returns. We had to explain the process to the users and collect necessary personal information.
- Challenges in customer communication: there were users trying to cheat the system in order to get free goods. We needed to implement measures to prevent such abuse.
- Challenges in seller communication:
    - there were sellers who would change their minds halfway and withdraw from free product provision, which led to a dissatisfactory customer experience participating in the program
    - raising seller awareness of the program and its benefits so that more products can be sponsored and more users had the opportunity to participate in the program

## Result

1. The competition factor worked: per every product provided, it created approximately 2 more organic high-quality reviews.
2. Our team raised the awareness of the program to the sellers and made the application process easier, leading to a 3X increase in goods sponsored and more than 40% returned to register for more review sponsorships
3. Higher performance (awareness of the program, quality of reviews) compared to direct competitors that employed similar review sponsorship programs.
{% include image_caption.html imageurl="/images/Project AblyReviewer/results.png" title="socials" caption="MUSINSA (direct competitor): #1 fashion e-commerce platform. MAU 8M. / ABLY - MAU 4M"%}    

## Takeaways

- To replicate someone else’s success, a careful analysis and reenactment of ‘why’ it worked is crucial.