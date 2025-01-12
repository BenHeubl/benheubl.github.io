---
title: How does the education of your parents relate to that of your spouse?
header:
  teaser: 'https://farm5.staticflickr.com/4076/4940499208_b79b77fb0a_z.jpg'
categories:
  - analysis
tags:
  - update
---

**The Level of education plays a significant role in how we choose a partner. But how does the level of education of our parents relate to how Americans marry? It turns out that the gap of length of education between spouse and parents used to shrink and now seemed to have stopped further converge. Also the analysis shows that mothers used to attend school longer than fathers in the past, but the reverse is true today.**


![pic1]({{ site.url }}/images/gss1/A1.png)

Men and women tend to choose one another with [similar educational achievements in mind](http://www.jstor.org/pss/10.1086/660108). Yet, since educational achievements are many times supported - one could say “pushed” – by parents and their achievements, I was interested in how parents’ education compared with those of peoples’ spouses.


[The General Social Survey](http://gss.norc.org/) offers data that goes all the way back to the 1970ies and consists of 62,466 responses across various questions. Interesting for this piece is how respondents answered to the questions of how many years their father, their mother and their spouse went to school.


The average spouse in 2016 went to school 14.13 years, 2.2 years longer than his or her parents. 44 years ago, this difference was much larger. The assumption is that earlier generations had fewer opportunities. In 1972, people chose a spouse with a school career of 12 years on average. The gap between spouse and parents accounted for 3.15 years. The difference shrunk over the years, logical so, as  generations developed.


Slowly over time, both current and past generation could pursue the same opportunities in education. Yet, within the last ten year, this contracting trend seems to have come to a halt and flattened (note the polynomial trend line). The convergence stagnates at 2.25 years of schooling. Now, this could have multiple explanations, which require more research. But the fact that the trend slows, should be noticed.

![pic1]({{ site.url }}/images/gss1/A2.png)

A second observation concerns only the parents. It looks at the difference between fathers and mothers’ reported periods of schooling. The analysis revealed that mothers were reported to have spent longer at school on average until 2003. From 2004 onwards, the trend reverses and fathers have a longer schooling career.


Since 2004, fathers are reported to attend school 0.11 years longer than mothers. Note how the trend-line suggest a cooling, seemingly settling at the mark of 0.125 years or 45 days, fathers spend longer swotting than mothers. What does this mean? Email me, I am hooked to find out.








<!-- <figure>
  <a href="https://i.ytimg.com/vi/pzwT6lQ0sHE/maxresdefault.jpg">
  <img src="https://i.ytimg.com/vi/pzwT6lQ0sHE/maxresdefault.jpg">
</a>
  <figcaption><a href="https://i.ytimg.com/vi/pzwT6lQ0sHE/maxresdefault.jpg" title="Street League 2013: Nyjah Huston">Street League 2013: Nyjah Huston</a>.</figcaption>
</figure> -->

<!-- Skateboarding has had a bad reputation for many years before Louis Vuitton used [it in their ads](https://www.youtube.com/watch?v=GWydT-BNbQo). Today, skateboarding manages to get attention from all corners of the media landscape, and is now even only one step away to become an [Olympic discipline](http://theridechannel.com/news/2016/06/skateboarding-olympics-tokyo-2020). For decades, the typical competition format was that skaters were judged on their run, however Street league Skateboarding established a whole new data driven model to judge the performance of each street skater.

Instead of only being ranked on the run on the skate course, SLS introduced a real time rating system, single tricks evaluation, and a statistical evaluation of the scoring for each skater.

![pic1]({{ site.url }}/images/sls/skatetrick.gif)

# Sh.t is going down this weekend, at the Nike SB Super Crown World Championship

This Sunday, the biggest street skateboarding competition will take place in LA. SLS is the official street skateboarding world championship as recognized by the International Skateboarding Federation. At the recent Street League Skateboarding Nike SB World Tour in Newark, New Jersey, [Nyjah Huston](http://streetleague.com/pros/nyjah-huston/) won the game and is now defending the 2015 SLS Championship title. Could we yield some interesting findings that could support skaters with empirical evidence how to win it?

![pic1]({{ site.url }}/images/sls/super_crown.png)

Via a simple [EDA](https://en.wikipedia.org/wiki/Exploratory_data_analysis), we will try to establish a number of relevant patterns gained from previous SLS results.

# Relationships

We understand from the correlation plot that there is a negative relationship between best-trick and run scores (-0.5), and an interesting one between age of skater and number of sponsors for each skater. Number of sponsors also plays nicely with final results for 2015 championship points.

![pic1]({{ site.url }}/images/sls/plots/correlation2.png)

# Strategy

Loess line seems to draw a different picture, than the linear regression line. We will consider the structure later, when building a prediction model.

SLS's competition format requires a lot more strategic planning today, than in the previous single score run-based competitions. An analysis of run-section and best-trick scores across recent Street League contests suggests that if players do perform well on either one of the sections, they usually perform not not as well in the other one (although, the linear trend is more significant for the preliminaries).

![pic1]({{ site.url }}/images/sls/plots/B_2.png)

Chaz Ortiz and Shane O'Neill know how to perform well in the run section (mainly due to their vast experience in conventional skate contests), while Kevin Hoefler and Manny Santiago do well in the best-trick section. All-rounders such as Nyjah Huston and Luan Oliveira seem to do well in both sections for the finals. For the preliminaries, Shane and Nyjah leading the field, and are able to make it into the finals every single time.

# Street League's evolution

Launched in 2010, Street League Skateboarding is now an international competitive series in professional skateboarding. The SLS ISX, which is the core of the concept, is best described as a real time scoring system, allowing to include each trick independently. This stands in contrast to all other professional contests that judge on overall impression of a full run or series of tricks performed within a certain time frame. Because the outcome could change to the very last trick, the audience is kept in their seats. Transparency is high too. If the audience is able to understand how and why the skaters were judged the way they were, it adds an additional kick. To win, skaters are required to to have a strategy and be smart about how they play their skills and their endurance.

![pic1]({{ site.url }}/images/sls/plots/C.png)

Comparing 2015 with 2016, Nyjah Huston's run scores dropped slightly (this could be due to the fact that the scoring changed overall).

![pic1]({{ site.url }}/images/sls/plots/D.png)

While Shane O'Neill could not improve on his highest run scores (but on best trick scores)...

![pic1]({{ site.url }}/images/sls/plots/E.png)

...Paul Rodriguez kept performing well across both sections.

If a skater is strikingly good at the run section, but fails to succeed in the best trick section (or vice versa), he (or she, female Street League was introduced in 2015) is unlikely to win.

So what is the best strategy? To answer the question, it helps to look at statistical coefficients and relationships for data points for the previous events.

# Can you predict win probabilities after the run section?

Ok, we learned something from a basic exploratory data analysis. It's time to shift our attention to machine learning and use what we learned.

Every SLS game starts with the run section, and ends with the best trick category. We could use machine learning and train one or multiple models to yield win probabilities after the run section, but before the best trick section and announcement of a winner to predict the winner.

In the next part our goal is to build multiple models, the practice to statistically compare them, and to come up with one that allows us to predict mid-game, which skater has the best changes to win the upcoming SLS Nike SB Super Crown World Championship.

## Defining Independent and dependent variables

The outcome variable we will predict is a win or no-win. An variation to this is building a classification models on podium winners (1st, 2nd, 3rd). In different corner of the SLS website, we find information on the [pro skaters](http://streetleague.com/pros/), their previous performances and [event-specific results](http://streetleague.com/coverage/new-jersey-2016/).

From the [SLS website](http://streetleague.com/the-9-club/), we scrape the number of 9 club scores for each skater (9 Club tricks are the most extraordinary moments in Street League and represents the highest scores in previous contest). 9 club scores may also be an important predictor on how well the players did perform in the best trick section.

Run HST and Run Avg may be important predictors to our models. Championship Points allow new and established skaters to qualify into the SLS Nike SB Super Crown World Championship. Each skater's point score will be fed to our model.

We also throw in additional parameters. We have access to the age of some of the established pro skaters (the average age of pros is around 25, but outliers such as Cole may skew it), we know their stance (goofy or regular), and in the process of scraping and cleaning, I was able to count the number of sponsors.

# Model types

We will build logic regression classification models, and compare how well they are able to perform against each other.

## Logic Regression

We will build and test a [binomial logistic regression](https://en.wikipedia.org/wiki/Binomial_regression) (our outcome variable which can assume 2 values). The following variables will be used to fit a [GLM](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/glm.html) model in R:

```r
# Overview of variables:
glimpse(win)
```

In a hidden process, I have cleaned the data, and converted them to required class types. Categorical data are factor values, while numerical are encoded as numerical or as an integer class. The age variable has no missing values anymore ([removal of NA values in R](http://stackoverflow.com/questions/7706876/remove-na-values-from-a-vector)), and they have been replaced with the average age values. Similarly, I dealt with the values in the stance column (to what degree this is valid, needs to be evaluated, but for now, we don't care too much about stance - in theory, it shouldn't make a difference whether a brilliant skater is goofy or regular).

![pic1]({{ site.url }}/images/sls/plots/lr_overview.png)

```r
# randomize, sample training and test set:
set.seed(10)
win_r <- sample_n(win, 207)

train <- win_r[1:150,]
test <- win_r[151:207,]

# fit GLM model:
model <- glm(class_winner ~.,family=binomial(link='logit'),data=train)
summary(model)
```

![pic1]({{ site.url }}/images/sls/plots/lr_fitting.png)

We learn from the summary function that most of the variables are not statistically significant for our model. Run_HST is possibly the best predictor we can use at this stage. A positive coefficient for Run_HST suggests - if other variables are kept equal - that a unit increase in highest run section scores would increase the odds to win by 4.740e+00.

We run a function from the Anova package, to investigate the table of deviance:

```r
anova(model, test="Chisq")
```

![pic1]({{ site.url }}/images/sls/plots/lr_deviance.png)

This gives us an idea on how well our GLM model performs agains the null model. Here we see that not only Run_HST reduced the residual deviance, but also the variables age and champ_pts_2015\. For us it is important to see a significant decrease in deviance. Lets assess the model's fit via McFadden R-Squared measure:

```r
install.packages("pscl")
library(pscl)
pR2(model)

llh          llhNull     G2           McFadden    r2ML        r2CU
-14.2949557 -36.7395040  44.8890966   0.6109105   0.2586338   0.6678078
```

This yields a McFadden score of 0.611, which might be comparable to a linear regression's R-Squared metric.

```r
# Run on test data:
test_run<-test %>%
  select(-class_winner)

fitted.results <- predict(model,test_run, type='response')
fitted.results <- ifelse(fitted.results > 0.5,1,0)

misClasificError <- mean(fitted.results != test$class_winner)
misClasificError
print(paste('Accuracy',1-misClasificError))

#[1] "Accuracy 0.912280701754386"

#CrossTable:
CrossTable(fitted.results, test$class_winner,
prop.chisq = F, prop.t = F,
dnn = c("Predicted", "Actual"))
```

While we get an accuracy of 91%, this result is misleading. The model couldn't find who is going to win. Only who is not to win, which isn't really our problem at this stage, but one reason we get such high accuracy score.

![pic1]({{ site.url }}/images/sls/plots/lr_winner_poor.png)

```r
ctrl <- trainControl(method = "repeatedcv", number = 10, savePredictions = TRUE)
mod_fit <- train(class_winner ~.,  data=win_r, method="glm", family="binomial",
                 trControl = ctrl, tuneLength = 5)

pred = predict(mod_fit, newdata=test)
confusionMatrix(data=pred, test$class_winner)
```

We can confirm the accuracy result with K-Fold cross validation, a central model performance metric in machine learning. We apply one of the most common variation of cross validation, the 10-fold cross-validation and display the result via a confusion matrix. Now we get an even higher accuracy score of 95 percent. Still, the model couldn't find the winners.

![pic1]({{ site.url }}/images/sls/plots/ls_cross_validation.png)

## Predicting winning a medal:

The data only covers two years of the games. This makes it hard for a model like this to spot winners. What we could be doing instead is to tune down our standards, and only look for the lucky three winners who make it onto a podium. For that, we need to calculate an extra column, and add a "1", for all skaters who made it among the top three, and "0" for the ones that didn't. To test our new model, we will run it on the most recent game in New Jersey, after cleaning the training data.

```r

set.seed(10)
win_r <- sample_n(test <- win[c(1:68, 77:207),], 199)

train <- win_r
test <- win[69:76,] ##New-Jersey-2016

model <- glm(top_3_outcome ~.,family=binomial(link='logit'),data=train)

test_run<-test %>%
  select(-top_3_outcome)

fitted.results <- predict(model,test_run, type='response')
fitted.results <- ifelse(fitted.results > 0.5,1,0)

misClasificError <- mean(fitted.results != test$top_3_outcome)
print(paste('Accuracy',1-misClasificError))

#[1] "Accuracy 0.75"

#CrossTable:
CrossTable(fitted.results, test$top_3_outcome,
prop.chisq = F, prop.t = F,
dnn = c("Predicted", "Actual"))
```

![pic1]({{ site.url }}/images/sls/plots/jersey.png)

This model performs better. Except of 2 miss-classified instances, we got 2 out of 3 podium winners right. While it did well on the two winners - Nyjah Huston (1st), Chris Joslin (2nd), with 90% and 80% probability respectively - the model could not figure out the third place, that was labelled as "other" in our training data. Tommy Fynn was not included in the practice when I labelling the rank_skater column (skaters that will play Sunday's finals were labelled in the data). As good practice requires, we will look at is ROC curve to produce a visual representation for the AUC, a performance measurements for a binary classifier.

```r
install.packages("ROCR")
library(ROCR)
fitted.results <- predict(model,test_run, type='response')
fitted_for_ROCR <- prediction(fitted.results, test$top_3_outcome)
performance_ROCR <- performance(pr, measure = "tpr", x.measure = "fpr")

# plot:
plot(prf)

AUC <- performance(fitted.results, measure = "auc")
AUC <- auc@y.values[[1]]
#[1] 0.7333333
```

![pic1]({{ site.url }}/images/sls/plots/ROCR.png)

An AUC of 0.73 is not entirely pleasing, but it's a start. We could now look for which score each skater on Sunday would need to gain for decent win probability. For this, we could build a test-set with the skater names and run scores ranging from 1 to 10 (we already know that skater and Run_HST are powerful predictors for the podium medals).

```r
### probabilities for highest scores:
scores <- seq(1, 10, 0.1)

skaters <- c("NyjahHuston", "ShaneONeill", "PaulRodriguez",
             "LuanOliveira", "TomAsta", "RyanDecenzo", "CodyMcEntire",
             "ChrisJoslin")

df_skate <- NULL
for (skater in 1:length(skaters)) {
  for (s in 1:length(scores)) {
    df_skate <- rbind(df_skate, cbind(as.data.frame(scores[s]), as.data.frame(skaters[skater])))
  }
}

  names(df_skate)[1] <- "Run_HST"
  names(df_skate)[2] <- "rank_skater"

  fitted.results <- predict(model,df_skate, type='response') # with Run_HST and rank_skater as input variables

  ggplot(props, aes(Run_HST, fitted.results, group = rank_skater, col = rank_skater)) +
    geom_line() + theme_minimal()
```

![pic1]({{ site.url }}/images/sls/plots/props_skaters_lr.png)

Win probabilities chart for each skater from their highest run scores.

# Wrapping up

As we have seen, Nyjah Huston, Shane O'Neill and Paul Rodriguez do have best chances to make it on the podium. In which combination is unclear, but we will find out shortly. We have also learned how to apply a logistic regression on skateboarding, and how to compare the results across the various types of models we build. Two more models have been built. A neural network model and a random forrest model, both which didn't perform as well as the logistic regression. -->
