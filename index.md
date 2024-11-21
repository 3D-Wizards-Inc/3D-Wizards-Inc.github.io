
## Overview

3D-Wizards Inc. is a business that develops and sells 3D printed products. The web application for the online store is currently under development, but the final application will allows users to browse items, make orders, and get in contact with the business owners.

The Problem: For the past year we have been a popular staple of physical marketplaces like the Aloha Stadium Swap Meet, the Lineup at Wai Kai, and the Pearlridge Center just to name a few. However we have a disappointingly finite stock and variety of options. In theory we should be able to quickly turn around custom orders, especially custom colors of products we already produce, due to the nature of 3D printers. However we're so focused on having enough normal stock for our locations that we don't have time to check and respond to instagram DM's or emails with lucrative custom orders. People also are unclear about their options when it comes to what we regularly make and how to order in bulk.

The Solution: We want to build my company a website where prospective customers can easily put in orders, with an admittedly overwhelming number of custom options, in a welming user-interface. 

Our team contract with all of the member's signatures can be found [here](https://docs.google.com/document/d/1khLUqeU3P_N2-VMSdp-ibR_amM5T2jIwDZtIPfz1X4s/edit?tab=t.0).

## Approaches

There's many customer service processes in our company that I think could be streamlined, improved, or introduced with this website. Here are a few of my goals and hopes as well as their implementation.

### Online Store

- Potential customers should be able to browse a wide variety of our products.
- Customers should be able to add items to their cart and checkout.
- Even just sending us the requests this way would drastically improve productivity but a stretch goal would be to actually process payments through the web application instead of in person on delivery.
- In-Store pick-up and Shipping will be options which will have different check out prompts.

### Custom Orders

- We will design a graphical interface to choose specific custom colors/filament materials for different parts of the 3D model.
- There will also be another option to upload a 3D file of the customer's choosing along with material instructions as a requisition.
- There should be a cost and wait time estimator even if it's not entirely accurate at first before proper implementation.

### Business Collaboration

- We will also create a request form for businesses to reach out for a more involved partnership and longer-term business deal.
- Should allow for uploading images and a proposition.

## Mockup page ideas

- Home Page
- Signin/Signup/Account(Purchase History)
- Product List Page
- Custom Order Request Page
- Buisness Proposition Page
- Checkout Page

## Use Cases

- We have had people approach me to print all the individual pieces for an Iron Man suit or a knight's armor, the custom project page would be perfect for this.
- Many parents want to buy a specific toy for each child in their life in their favorite color, the basic shop page would make this drastically easier.
- A business that wants to either start mass producing a product or even just get a prototype could take advantage of this webapp.

## Current State of the Project

We have completed milestone M1, which consists of the landing page and the mockups of four other pages: store, custom order, about us, and business inquiries. Much of the functionality of the pages have already been implemented as part of our [M1 project](https://github.com/orgs/3D-Wizards-Inc/projects/1), which displays the full list of issues completed in M1. To view the repositories and source code of our project, our [github organization can be viewed here](https://github.com/3D-Wizards-Inc).

### Landing Page

![](https://cdn.discordapp.com/attachments/1305379341588496424/1306528528141123656/image.png?ex=6736ff03&is=6735ad83&hm=6f1b6e31a35d7c322c73a3fea228d5fea4d27d1c0a580928fe4cb2e541893274&)

### Store Page

![](https://cdn.discordapp.com/attachments/721939404226297860/1308982018968916029/1fc35a00e811ee5c2f98b4cdd419f380.png?ex=673fec01&is=673e9a81&hm=86309771bccf4f81cfef1fb8e7ca1fe7a487fd69ad257ac41d3be11413b4f548&)

Customers are able to browse the full catalog of items as well as use the left column to filter items by categories, colors, and size. A search bar is also included.

### Custom Order Page

![](https://cdn.discordapp.com/attachments/721939404226297860/1308984069995892817/1ec1166273d206540aebe7c06cb82686.png?ex=673fedea&is=673e9c6a&hm=76e3f0510aea963405403105c9369ef0c17a8807e5b4a73ccc8c8e8946422321&)

Customers are also able to put in their own custom order by first choosing a product, then specifying the colors, size, and quantity of their order. Submitting an order adds and entry to the prisma database, which will be able to be viewed in an eventual "cart" implementation.

### About Us Page

![](https://cdn.discordapp.com/attachments/721939404226297860/1309108560889643118/586d020677b8cddd8467f0e2b22b536f.png?ex=674061da&is=673f105a&hm=9caa424774858db3fe0a9beb00018be525f9df6091242cf0372946cc39ea9591&)

### Business Inquiries Page

![](https://cdn.discordapp.com/attachments/721939404226297860/1309115727332114554/46e7611650eb9d7ec8ae791c4c78e180.png?ex=67406887&is=673f1707&hm=15d18e910c67f32348bc15ad5706d4b359783deb878932beecbb6411780c6301&)

### Deployment

The current website deployed on vercel can be accessed [here](https://3-d-wizards-inc.vercel.app/).

## The Next Steps

Our current goal is the [M2 project](https://github.com/orgs/3D-Wizards-Inc/projects/2), which furthur expands on the mockup pages and functionalities created in M1. <!--Some key features that are planned to be implemented in this milestone are:-->
