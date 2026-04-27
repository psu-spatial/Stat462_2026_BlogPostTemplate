# STAT-462 Final Blog Post

## Before you begin

- Install the `distill` package in RStudio before trying to knit: `install.packages("distill")`

---

## Grading

This blog post is graded out of 110 points as Part 4 of your semester project.

---

## Style instructions

Imagine you are writing a case-report for STAT-462 Consulting. In general:

**STYLE**

- Remember to adjust the YAML code at the top. Your title and one sentence description should reflect the question your client is trying to answer.
- Please add more headings/subheadings! Your structure should be easy for the reader to use the table of contents to 'skim read'.
- You are welcome to include pictures, but remember they need to be in your project folder or they will disappear when they knit.
- The blog will auto "fold" your code when you knit — the code will look hidden until you click a button. So do not hide any code using `include=FALSE`.
- Make sure that things like library commands are together near the top with warnings & messages set to FALSE. This also works for the GGally/ggpairs code chunks.

**TONE & CONTENT**

- You are writing a summary for your client and any casual online readers. These want to see the statistics, but ALSO have an explanation of what they mean in clear language.
- There's a spell check button next to the save and knit buttons.
- Only include plots/code output that you talk about in the text.
- Please mainly use the code/commands/plots that we used in the lab instructions, tutorials and previous labs. I'm testing you on what you learned during this class. You're allowed to do extra work, but the basics must refer back to our class material.
- **Your writing/grammar is allowed to be poor!! I guarantee your unfiltered thoughts will get you a higher grade than meaningless chatgpt gloss.**

---

## Content requirements

### Background (200+ words, no upper limit)

Explain the background of your project and introduce your client and the statistical question(s) they want to answer.

Summarise everything the client needs to know about the study design and the origins of your dataset. You're allowed to use photos or anything else that explains the problem to a casual reader.

---

### Exploratory Data Analysis (200+ words, no upper limit)

Conduct any necessary quality-control/filtering/removing missing data that you found you needed from your lab-book and summarise what you did in the text so someone else could directly reproduce your work.

Summarise/Showcase the data for the client, so they understand the details of your dataset. This might include summary statistics, any potential issues (outliers, missing values you had to remove etc, or potential multicollinearity/confounding/spurious variables).

---

### Initial Model / SLR (200+ words, no upper limit)

Conduct a Simple Linear Regression analysis, which includes:

- The equation written in LaTeX (use tutorial 12, not ChatGPT!)
- An interpretation of results in context of the problem
- An exploration of model effect size, goodness of fit, model validity and outliers
- At least one relevant hypothesis test

You should include all relevant code, plots, LaTeX equations AND write everything up for your client to understand in full sentences. Fully write up any hypothesis tests as described in previous labs/classes.

If your LINE assumptions needed you to transform the data, also add a second follow-up model showing how it improved the results and validity.

---

### Final Model Selection Process (200+ words, no upper limit)

For MLR, you do **not** have to include every model you used in your log book. In fact you are only writing up your final model.

So here, explain the process of HOW you came up with your final model. E.g. what steps did you take to ensure that you have the best possible model to explain the variation in their response?

- Refer to your lab book for this! e.g. you might have transformed variables, you made your initial table of predictor selection characteristics, you did best-subsets. Talk the client through what you did.
- Remember there will be no perfect model. In fact there might be some variables you are torn over. Write about this to your client and why you are unsure (the recommendation here to the client no matter what your final choice will be "you need more data"). But at the end, you must still state and justify your final choice even if you are unsure.

**Note from Dr G:** you are welcome to run and include code & output from things like best-subsets, correlation matrices or other model outputs to explain your point, but you don't **have** to run/analyse every model in your lab book. I'm grading you here based on your arguments and the evidence you use to convince me that your final model is "best", especially based on what you learned in class.

---

### Final Model (200+ words, no upper limit)

Conduct a Multiple Linear Regression analysis on your FINAL MODEL, which includes:

- The model code and summary
- The equation written in LaTeX (use tutorial 12, not ChatGPT!)
- An interpretation of results and "how good" the model is
- An exploration of goodness of fit
- An exploration of model validity, multicollinearity and influential outliers
- At least one partial F-test

You should include all relevant code, plots, LaTeX equations AND write everything up for your client to understand in full sentences. Fully write up any hypothesis tests as described in previous labs/classes.

---

### Client Questions / FAQ (100+ words per question, no upper limit)

Imagine your client has handed you some FAQ questions. You need to write out their full question adding details as necessary (e.g. use your prediction questions from your lab book), your code/calculations and your answer.

**FAQ 1 — Prediction part 1:**
Your client has asked you to use your final model to make a prediction of a new object (use the one from your lab book). Replace the generic question with your client's specific question.

**FAQ 2 — Prediction part 2:**
Your client has asked you to use your final model to make a prediction of the AVERAGE RESPONSE for a given combination of predictors, and asked why this value looks different to FAQ 1. Replace the generic question with your client's specific question.

**FAQ 3 — Multicollinearity:**
Your client has asked you what "multicollinearity" and "confounding variables" are and whether you are worried about them in your model.

**FAQ 4 — Limitations:**
Your client has asked you what the potential biases in your results are (e.g. if you could collect data on new predictors, what would you find data on).

---

### Summary (200+ words, no upper limit)

Refer back to the client's request. What have you found out to help them answer their request? Generally summarise what your results show, what predictors explain the variation in their response, how that relates to your understanding of the problem (e.g. does this make sense causally?) and what do you recommend as the next steps.

---

## Before submitting

1. Make sure your `.Rmd` knits cleanly using only the files in this repository.
2. Make sure your dataset is in the repository alongside your `.Rmd`.
3. Make sure all instruction callout boxes have been deleted before you submit.
4. Make sure your name and email ID are in the YAML author field.
