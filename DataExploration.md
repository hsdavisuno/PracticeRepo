# Data Exploration

# Variable Scatterplots
**General Location and Age**

![image of a scatterplot with general_location as the y-axis and age as the x-axis](https://github.com/hsdavisuno/ISQA-8600-Heather-Davis-Individual-Assignments/blob/main/1AgeandGeneralLocationScatterplot.png "Scatterplot 1")

    Code: ggplot(data = HFS.Service.Data) + geom_point(mapping = aes(x = age, y = general_location))

**Age and Gender Identity**

![image of a scatterplot with age as the y-axis and gender_identity as the x- axis](https://github.com/hsdavisuno/ISQA-8600-Heather-Davis-Individual-Assignments/blob/main/2AgeandGenderIDScatterPlot.png "Scatterplot 2")

    Code: ggplot(data = HFS.Service.Data) + geom_point(mapping = aes(x = age, y = gender_identity))

# Scatterplot with Three Variables

![image of a scatterplot with general_location as the y-axis and age as the x-axis and a legend with general location](https://github.com/hsdavisuno/ISQA-8600-Heather-Davis-Individual-Assignments/blob/main/3AgeGenderandGeneralLocationScatterPlot.png "Scatterplot 3")

    Code: ggplot(data = HFS.Service.Data) + geom_point(mapping = aes(x = age, y = gender, color = general_location))

# Scatterplot with Two Variables and Trendline

![image of a scatterplot with total duration_num as the y-axis and age as the x-axis](https://github.com/hsdavisuno/ISQA-8600-Heather-Davis-Individual-Assignments/blob/main/4TwoVariableswithLine.png "Scatterplot 4")

    Code: ggplot(data = HFS.Service.Data) + geom_smooth(mapping = aes(x = age, y = total_duration_num))

# Faceted Plot with Two Variables

![image of a scatterplot with gender_identity as the y-axis and age as the x-axis](https://github.com/hsdavisuno/ISQA-8600-Heather-Davis-Individual-Assignments/blob/main/5TwoVariableFacetGrid.png "Scatterplot 5")

    Code: ggplot(data = HFS.Service.Data) + geom_point(mapping = aes(x = age, y = gender_identity)) + facet_grid(. ~ gender_identity)

# Bar Chart

![image of a scatterplot with count as the y-axis and age as the x-axis](https://github.com/hsdavisuno/ISQA-8600-Heather-Davis-Individual-Assignments/blob/main/6CountofAgeBarChart.png "Scatterplot 6")

    Code: ggplot(data = HFS.Service.Data) + geom_bar(mapping = aes(x = age))