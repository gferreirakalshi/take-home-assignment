# THA

## General instructions

We want you to create a great structure and scalable project for maintenance that respects the tests scenarios and business rules.

We also want you to write a great README file in English. We want to understand the structure decisions you made. Think of it as a file that another software engineer will read before continuing the piece of art you created.


💡 **IMPORTANT**: you can only use flutter to implement this assignment.


## The challenge!

Kalshi is a regulated exchange & prediction market where you can trade on the outcome of real-world events. We are now developing a new feature at our app to help people to keep track of their financial situation.

In order to do that, users should register information regarding their financial situation in our app. Two key pieces of information are his **annual gross income** and **average monthly costs**.

## Development Instructions
### Business rules

Based on that information, the system should calculate a score to represent how healthy his financial life is, meaning:

- At the end of the year, the user has to pay 8% x over his annual gross income.
- If the user annual costs represents less than or is equal to 25% of his annual net compensation, his score is HEALTHY;
- If the user annual costs is greater than 25% and less than or equal 75% of his annual net compensation, his score is MEDIUM;
- If the user annual costs is greater than 75% of his annual net compensation, his score is LOW;

E.g

```
Annual Income = 1000 && Monthly Costs = 10 = HEALTHY

Annual Income = 1000 && Monthly Costs = 30 = MEDIUM

Annual Income = 1000 && Monthly Costs = 80 = LOW
```

### Presentation rules

You should create a form where the user will be able to inform his annual gross income and average monthly costs. When submitting the information, the user will be presented his financial wellness score.


🧑‍🎨 You should follow this [Figma File]([https://www.figma.com/file/eysSLDJFaEgGRWqHTFVehu/Take-Home-Assignment-v3?node-id=0%3A1](https://www.figma.com/design/VjioJW8BHtC6poQjJSJUmE/Take-Home-Assignment?node-id=0-1&t=aJye8WoiUMJGKIaF-1)) for building your screens


The form should validate:

- annual income is greater than zero;
- monthly costs are greater than zero;
- inputs should allow only numbers;
- inputs are required.

## Delivery Instructions

You can share your project via Github or send a package to us. If using Github, please, make sure we can access it by making it public.
