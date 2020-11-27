# React Context

This is an example for [React Context](https://reactjs.org/docs/context.html) from the Udemy Course "React - The Complete Guide" from Maximilian Schwarzmüller.

It shows the use of context instead of redux. The project is transformed during the course. It also mentions, that context ist not ment to be used instead of redux in every case because of performance issues.

Context ist ready to be used for low frequency updates and not highfrequency onces. Use for things that change rarely only, e.g. user authentication, theming

The example shown in this project is more on the highrequency side as there are changes rather often.
Whenever something changes in the context, every component that uses useContext will rerender no matter if its directly affected.

## Get started

`yarn install`

## Run the project

`yarn start`
