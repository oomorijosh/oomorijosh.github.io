---
layout: essay
type: essay
title: "Final Project Proposal"
date: 2025-11-04
labels:
  - Software Engineering
  - Next.js
---

## Overview

### The Problem
You just finished eating your lunch, maybe a musubi from 7-11 or a bento from across the street. However, there is a problem: you don’t know where a trash can is. The easiest course of action might seem to be leaving the trash on the side of the street. Unfortunately, this lack of awareness about nearby trash cans often leads to littering. Over time, this behavior contributes to unclean public areas, environmental harm, and pollution of the air and water we depend on.

### The Solution
To combat this issue, I propose an app that helps users locate the nearest trash can. By making it easy for people to dispose of trash properly, we can reduce littering and promote cleaner communities. To encourage engagement, the app will include a **leaderboard** and **point system** that rewards users for disposing of trash responsibly and discovering new trash can locations.

---

## Names of the Proposers
- Joshua Omori

---

## Mockup Page Ideas

The initial version of the app will focus on the **UH Mānoa** area.

### User Roles
- **Non-Signed-In Users** – Can view the map of trash cans, check the leaderboard, and sign in or sign up.  
- **Signed-In Users** – Have all the same privileges as non-signed-in users, but can also report new trash cans and earn points for verified trash can usage.  
- **Admins** – Can verify newly submitted trash cans, manage user reports, and delete accounts that submit false information.

### Mockup Pages
- Main Map Page  
- Submit Trash Can Page  
- Leaderboard Page  
- Sign-In Page  
- Sign-Up Page  
- Admin Dashboard  

---

## Use Case Ideas

- **New Users**
  - Can view the main map to see nearby trash cans.  
  - Clicking on a trash can displays information about who discovered or claimed it.  
  - Can view the leaderboard, sign in, or sign up.  
  - Attempting to submit a trash can redirects them to the sign-in page.

- **Signed-In Users**
  - Can report new trash cans and gain points when disposing of trash properly.  
  - When submitting a new trash can, users are prompted to specify if it’s inside a building. If so, they’ll be reminded not to submit it unless it’s located on the first floor.

- **Admin Users**
  - Can verify the accuracy of reported trash cans.  
  - Have the authority to delete users who repeatedly submit false information.

---

## Beyond the Basics

- Implement a **verification system** that allows users to confirm whether a reported trash can actually exists. Accounts that report too many fake locations can be flagged or banned.  
- Allow users to **upload photos** of trash cans, providing visual confirmation and helping others recognize them easily (similar to Yelp’s photo feature).  
- Integrate a **location-based algorithm** that dynamically finds and displays the nearest trash can based on the user’s GPS position.  
- Optionally, add **gamification elements** such as badges, streaks, or achievements for consistent positive behavior.

---
