# Data Visualization in Python
## 1. Why Visualization? 
Data visualization is one of the key components in exploratory data analysis (EDA) in the data analytics process. EDA allows data scientists to have a quick overview of the data and inform the directions for further inferential or predictive analysis (e.g., regression, model design). Data visualization is an impactful way to do EDA, for example, it is much easier to observe trends from a line graph as compared to reading a series of numbers. However, data visualizations have to be done thoughtfully. From the choice of the graphs to the visual design elements (e.g., colours, fonts), these are all important decisions that data scientists have to make meaningfully. 
## 2. Data Visualization in Python
There are multiple graphing libraries in Python, the more popular ones include matplotlib, seaborn, ggplot (yes, the old friend from R), and plotly. While matplotlib is the simplest one to use, I found its default layout lack a little bit of lustre without putting in additional efforts. With my UX background, I understand how people are more drawn to visually pleasent graphs and they are more willing to spend time to read. Thus, my preferred libraries are seaborn and plotly express. In here, I chose to demonstrate a previous project from my graduate studies using Plotly Express. In addition to the more aesthetically appealing layout, Plotly Express allows one to build visualizations with tooltips without much addititional configuration, which is great for allowing the user to view individual data point with more details.
## 3. Chossing The Right Type of Visualization
To make the data visualization meaningful and not just eye candies, they need to be able to reflect the data represented by it accurately. To choose to right type of visual, we need to start with asking ourselves some questions: 
1. **What kind of data do you have?**
    1. Is it categorical or continuous?
    2. Is it a stand alone number (e.g., age/income) or part of a total (% of money saved in this bank)?
2. **What do you want to show?**
    1. A trend, a distribution, or differences among categories?
3. **What do the readers need to know?**
    1. Everything can be visualized but not all is useful. Choose a type of visualization that helps convey your message in the most effective way. 
## 4. A Bar, a Line, and a Box: The Simple Ones Go a Long Way
Visualizations come in multiple types (Check out this [Data Visualization Catalog](https://datavizcatalogue.com/)), but I think simplicity is sometimes undervalued in the process. Simpler charts reduce the mental load of the readers when consuming the charts, allowing people to graps the information a lot quicker. 90% of data could be visualized using either a bar plot, a line graph, or a box plot, and they are so many different variations on those. 
### 4.1: Bar Plots
Bar plots are great for visualizing counts of categorical data, such as the population (i.e., counts) by country (i.e., categories). It offers very clear visual cue in terms of who comes top and human eyes are very good at comparing the straight, rectangular shapes of bar plots. Standard barplots arrange the bar side by side, but you can also stacked them if you have subcategories (e.g., population by sex), or make them into stacked 100% to show share of total for each subcategory. 

For example, in the below barplot, by stacking the subcategory - Sex - readers can see the trend of the total across years and the distribution (in number) at the same time. 
![newplot (1)](https://github.com/teresalau/Data_Viz_in_Python/assets/113483358/ea926882-f019-4dd2-932a-17a0b9a407a2)
