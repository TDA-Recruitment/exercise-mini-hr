# Home Exercise

This is a frontend exercise that will give you the chance to see what kind of things we build at TripleTech!

We'd like to build a mini-version of TripleTech - (mostly on the Company / Employee management side of TripleTech).

Here's the mock for what we'd like to see ideally:

![mock_1](https://github.com/tda-soft/react-hr-exercise/master/mock_1.png)

![mock_2](https://github.com/tda-soft/react-hr-exercise/master/mock_2.png)

## Objective
1. Implement an API to fetch list of companies & employees from [here](http://www.filltext.com/?rows=5&id={index}&name={lastName}~{businessType}&number={numberRange|505002010,519000000}&phone={phone}&fax={phone}&@employees={rows=!*id={numberRange|500,1500}*number={numberRange|304001050,315000000}*first_name={firstName}*last_name={lastName}*email={email}*birth_date={date|01-01-1950,01-12-2000}}).
1. See the list of all companies.
1. Allow adding a new company.
1. Allow editing the attributes of the selected company.
1. Allow deleting the company.
1. See all attributes of the selected company.
1. See all employees of the selected company.
1. See all attributes of a selected employee.
1. Allow editing the attributes of the selected employee.
1. Allow deleting an employee.

_Ideally, this should take around a day to finish, but let us know how much time you spent so we can calibrate our expectations!_

## Hints / Tips
- Ideally, you'll use something like `redux` to store all the companies & employees, but the exact implementation is up to you!
- You can use react router instead of modal approach if you want.
- It doesn't have to look pixel perfect with amazing animations, but we do care a lot about UX and usability.
  - Ideally your components would fit the grid, to make layout easy for your users.
  - Pick any UI toolkit (Bootstrap, Material, etc.), but try to make everything look consistent.
  - Handle the UX edge-cases! For example, what happens when a user resizes the screen to be smaller? Ideally a user would still be able to access all the components they placed. 

## Getting Started
- Clone or download the repository - do not fork!
- Run `npm install` & `npm start` Your browser should open up a skeleton React app. You can edit any file in `./src` and in most cases the website will hot-reload.
- You can use [Font Awesome](https://fontawesome.com/) for the icons.
- When ready submit your result in one of the following methods:
  - Create a new repository under your own account and send us link
  - Email us a zip file with the source code

For more info, you can check out https://github.com/facebook/create-react-app

## Requirements
- The code must compile with no errors.
- There should be no errors in the browser console.
- It should work smoothly with Google Chrome.

## Bonus
- Create input validation for the attributes (email, numeric input for phone & fax, name is required, etc...).
- Can't create company with number already exists.
- Can't create employee to the same company with number already exists.

## Questions?

Don't hestitate to reach out to us if you have any q's :)
