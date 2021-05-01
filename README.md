# The-Spark-Foundation-
This Task is based on a simple regression model.
Linear Regression is a model that predicts the relationship between two variables ie, Independent Variable and 
Dependend Variable.


The simple maths behind Linear Regression is 
# y = m*x + c
Where y is dependent variable, x is independent variable


Change in x values changes y values 


The model tries to predict slope and intercept values tht best fits the data.
Using this we Visualize data and predict the best.

The data in student_scores can be visualized by the following commands



Before fitting the data, we get the following graph...

### df.plot(x = 'Hours',y = 'Scores', c= 'b',alpha=1,style= 'o')
### plt.title('hours utilized VS Scores obtained')
### plt.xlabel('Hours used for study')
### plt.ylabel('Scores obtained')
### plt.show()

![bf_fit](https://user-images.githubusercontent.com/61930484/116783806-793cef00-aaae-11eb-9ff8-1d6984a0f5c2.png)



### import plotnine as p
### dff = p.ggplot(data=df, mapping=p.aes(x=df['Hours'], y='Scores')) 
### dff + p.geom_line()
![line1](https://user-images.githubusercontent.com/61930484/116783781-53174f00-aaae-11eb-8166-91a05030b1e6.png)


After fitting the data we get a line like this below


![line_lr](https://user-images.githubusercontent.com/61930484/116783904-fb2d1800-aaae-11eb-8c69-4184f2367417.png)


