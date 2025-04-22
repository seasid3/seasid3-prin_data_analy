# Project Title: Principles of Data Analytics Assessment Tasks

## *Author:*   
Orla Woods

## *Description:*
The Tasks assignment was assigned by Dr. Ian McLoughlin at the start of the Principles of Data Analytics module of the Higher Diploma in Science in Computing in Data Analytics, running from January to April 2025. Submission date: 04 May 2025.

## *Tasks:*
The aim of this assignment is to allow us to demonstrate our learnings from the module. Specifically, the assigned tasks are:

*Task 1: Source the dataset*
- Prior to starting any work, import the modules required for the task (see Requirements below)
- 1.1 Import the Iris dataset from the sklearn.datasets module
- 1.2 Explain what the load_iris() function returns (own words)

*Task 2: Explore the data structure*  
- Print and explain each of the following:
- 2.1 The shape of the dataset
- 2.2 The first 5 rows of the data
- 2.3 The last 5 rows of the data
- 2.4 The feature names
- 2.5 The target classes

*Task 3: Summarize the data*  
- For each feature in the dataset, calculate and display:
- 3.1 Mean
- 3.2 Minimum
- 3.3 Maximum
- 3.4 Standard deviation
- 3.5 Median

*Task 4: Vizualize features*
- 4.1 Plot histograms for each feature using matplotlib
- 4.2 Add appropriate titles and axis labels
- Although I had plotted all three histograms separately, as required, I wanted to see all three histograms on the same axes, so I plotted this also

*Task 5: Investigate relationships*
- 5.1 Create a scatterplot of any two features from the dataset
- 5.2 Color-code the three different classes of the scatter point plots

*Task 6: Analyze relationship*
- 6.1 Using numpy.polyfit, fit a regression line to the scatterplot

*Task 7: Analyze class distributions*
- 7.1 Create box-plots of the petal lengths for each of the three classes (one plot for each species/class)
- 7.2 I also created a box-plot showing the petal lengths of all three classes on the same axes.  
- There appears to be a distinct advantage to plotting the three classes on the same axes as this allows easy comparison of petal lengths between the three classes/species of Iris. 

*Task 8: Compute correlations*
- 8.1 Calculate the correlation coefficients between the two features
- 8.2 Display the results as a heatmap using matplotlib

*Task 9: Fit a simple linear regression*
- 9.1 Calculate the coefficient of determination $R^2$ the two features in Task 5 
- 9.2 Re-creating the plot from Task 6 and annotate with the $R^2$ value

*Task 10: Too many features*
- 10.1 Create a pairplot of the dataset using seaborn
- 10.2 Explain what the pairplot depicts (own words)

## *Technologies:*
- Python
- Git
- GitHub
- Codespaces
- Jupyter

## *Requirements:*
The followong are required for the code files to run:
- numpy 
- matplotlib 
- scikit-learn 
- scipy 
- pandas 
- seaborn

## *References:*
As well as writing the source references into each task's Jupyter notebook markdown cells, they are listed below. Please note that ChatGPT links can take several attempts to load. 

Module imports:  
* https://numpy.org/doc/stable/   
* https://matplotlib.org/stable/index.html  
* https://scikit-learn.org/stable/user_guide.html  
* https://docs.scipy.org/doc/scipy/reference/  
* https://pandas.pydata.org/  
* https://seaborn.pydata.org/tutorial/introduction.html  

Task 1:  
* https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html  

Task 2:  
* https://numpy.org/devdocs/reference/generated/numpy.shape.html  
* https://numpy.org/devdocs/user/absolute_beginners.html  
* https://www.w3schools.com/python/NumPy/numpy_array_slicing.asp  

Task 3:  
* https://numpy.org/doc/2.2/reference/generated/numpy.mean.html  
* https://numpy.org/doc/2.2/reference/generated/numpy.min.html  
* https://numpy.org/doc/2.1/reference/generated/numpy.amax.html  
* https://numpy.org/doc/stable/reference/generated/numpy.std.html  
* https://numpy.org/doc/2.1/reference/generated/numpy.median.html  

Task 4:  
* https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.hist.html      
* https://www.w3schools.com/python/matplotlib_labels.asp  

Task 5:  
* https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html  
* https://www.w3schools.com/python/matplotlib_scatter.asp  

Task 6:  
* https://numpy.org/doc/stable/reference/generated/numpy.polyfit.html  
* https://python-graph-gallery.com/scatterplot-with-regression-fit-in-matplotlib/
* https://chatgpt.com/share/67fc1e05-b9bc-800d-8180-9b02d2e6962a  

Task 7:  
* https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.boxplot.html   
* https://chatgpt.com/share/67fc2bdb-17c0-800d-8655-b97bfcf787c6  
* https://www.kaggle.com/code/thabresh/unveiling-iris-flowers-classification-model
* https://chatgpt.com/share/67fc2810-3464-800d-8e04-b5a831a6b936
* https://chatgpt.com/c/67fc2ba9-bedc-800d-ab59-14259787117b  

Task 8:  
* https://en.wikipedia.org/wiki/Pearson_correlation_coefficient
* https://chatgpt.com/share/68015c80-7ad8-800d-a1c2-06c441cbcb1c
* https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.corr.html
* https://www.geeksforgeeks.org/python-pandas-dataframe-corr/
* https://statisticsbyjim.com/basics/correlations/
* https://matplotlib.org/stable/gallery/images_contours_and_fields/image_annotated_heatmap.html
* https://www.geeksforgeeks.org/how-to-draw-2d-heatmap-using-matplotlib-in-python/
* https://chatgpt.com/share/680163d1-ae7c-800d-98d4-d1aa795c964036
* https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.imshow.html

Task 9:
* https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html
* https://dzone.com/articles/python-f-strings-quick-guide
* https://statisticsbyjim.com/regression/interpret-r-squared-regression/  
* https://www.ncl.ac.uk/webtemplate/ask-assets/external/maths-resources/statistics/regression-and-correlation/coefficient-of-determination-r-squared.html
* https://python-graph-gallery.com/556-visualize-linear-regression/

Task 10:
* https://stackoverflow.com/questions/38105539/how-to-convert-a-scikit-learn-dataset-to-a-pandas-dataset
* https://seaborn.pydata.org/generated/seaborn.pairplot.html
* https://chatgpt.com/share/6802396e-8878-800d-ae90-599656b08eba
* https://builtin.com/articles/seaborn-pairplot#:~:text=Seaborn%20Pairplot%20is%20a%20Python%20library%20that%20allows%20you%20to,the%20figure%20size%20and%20styling

## *Acknowledgements:*
I would like to take this opportunity to thank Dr. Ian McLoughlin for a brilliant lecture series, it was very clear and interesting and I really learned alot. Really enjoying the prospect of bringing this into my work very soon. Really looking forward to the next modules. 

## END