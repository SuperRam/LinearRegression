# LinearRegression
Description about linear regression using R for machine learning relation ship between calories and weight gain
data("mtcars")
View(mtcars)
attach(mtcars)
mean(mpg)
b <- read.csv(file.choose())
head(b)
tail(b)
cor(b$Weight.gained..grams.,b$Calories.Consumed)#we are seeing Corelation 
model <- lm(b$Weight.gained..grams.~b$Calories.Consumed)# linera regression model lm
summary(model)
