# README

## Introudction
Tokimon is an online game for trainer to train their Tokimons and battle with other trainers.

## UI mockup
[Click here for MI Mockup](https://github.com/lydiazheng/276_assign2/blob/master/cmpt276-A2%20UI%20Mockup.pdf).

## Contribution Guide
This project uses Ruby and Rails framework. To start contributing, clone or fork the repo and start with command `rails server`

## Features

**Explanation for basic features:**

### 1. Attributes for trainers:
+ Name: Users provided name with length limit of 50 characters.
+ Height: A integer value with maximum three digits represents the height in centimeters. 
+ Weight: A integer value with maximum three digits represents the weight in pounds.
+ Level: A user gains one level up by capturing three new Tokimons.
+ Address
+ Email: A valid email address agrees with the format of name@email.xxx.

### 2. Attributes for the Tokimons:
+ weight: A integer value with maximum three digits represents the weight in pounds.
+ height: A integer value with maximum three digits represents the height in centimeters.
+ special ability: An integer value between 0 and 100 represents a Tokimons' ablity including fly, fight, fire, water, electric, and ice.
+ total: The sum of all special ability value.

### 3. Bar chart
+ For displaying the data clearly, I add a bar chart for the trainer's level and add a bar chart for all Tokimons' total abilities

### 4. Message prompt
+ When you create, edit, or delete a trainer or tokimon, a message will pop up on the website.
+ If the value of the ability is out of the range (0, 100), an error message will pop up.

### 5. Animation
+ Home page has an animation with the link.

## Author
Lydia Zheng

