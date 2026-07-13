---
title: "Bonus: Extending your Shiny App"
teaching: 20
exercises: 15
---



:::::::::::::::::::::::::::::::::::::: questions 

- How can we extend a Shiny app with additional inputs and outputs?
- How can we adapt an existing app to explore different data?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Add new input widgets to a Shiny app.
- Modify server logic to support additional app features.
- Extend an existing app to explore industry data.

::::::::::::::::::::::::::::::::::::::::::::::::

Now that we have built a complete Shiny app, it is time to start making it our own.

So far, we have focused on the core ideas behind Shiny: user interfaces, inputs, outputs, and reactive expressions. Many real-world Shiny apps build on exactly these same concepts by adding more inputs, more outputs, and more ways for users to explore data.

The dataset used in this lesson contains information about both occupations and industries. In this episode, we will extend our app by adding new controls and outputs, then apply what we have learned to create our own variations of the app.


## Guided transfer exercise

You've already built an **occupation** explorer.
Can you adapt it into an **industry** explorer?


:::::::::::::::::::::::::::::::::::::::  challenge

## Industry Explorer

Rather than building a new app from scratch, adapt the app you have already created by identifying the places where occupation-related variables are used and replacing them with their industry equivalents.

Your new app should:

1. Allow the user to select a region.
2. Display industry information.
3. Use a reactive expression to prepare the industry data.

Hint: Look for the columns `industry` and `industry_count_2041` in the dataset and follow the same pattern used previously for occupations.

:::::::::::::::  solution

Answers may vary.


:::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::::



::::::::::::::::::::::::::::::::::::: keypoints

- Shiny apps can be extended by modifying the same user interface, server, and reactive patterns used to build the original app.
- New app features often require changes in both the user interface and server code.
- Reactive expressions can be reused when adapting an app to work with different variables or datasets.
- Once you understand the basic structure of a Shiny app, it is often straightforward to adapt it to answer new questions.

::::::::::::::::::::::::::::::::::::::::::::::::
