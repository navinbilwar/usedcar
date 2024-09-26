<b>Data Source:</b>
1. Used Car dataset on Kaggle
2. Scope: Original dataset: 3M used cars; a subset of 426k cars is in scope for this analysis

<b>Link to notebook:</b> https://github.com/navinbilwar/usedcar/blob/main/prompt_II.ipynb

<b>Business Objectives:</b>
1. Analyze the dataset to determine the top features and their corresponding weightage
that contribute to a used car price
2. Use data pre-processing, data modeling, and model evaluation methodologies to make clear 
recommendations to the used car dealership on what features consumers value most in a used car

<b>Conclusion:</b><br>
Most influential factors valued by consumers for a better car price:
1. Newer cars (i.e. less car age)
2. Better car condition
3. More # of cylinders
4. Gas cars with more # of cylinders
5. Sedan gas cars in general fetch higher price compared to coupe
6. Car brands: Chevrolet/Ford with higher # of cylinders, Toyota/GMC with higher # of cylinders

Most influential factors contributing to lower car price: 
1. Older cars
2. Gas cars with higher mileage
3. Car brands: Ford gas cars, Dodge gas cars, Volvo gas cars, Chevrolet gas cars with lower # of cylinders
4. Pickup trucks with higher # of cylinders

<b>Next steps & recommendations for better modeling</b>
1. Revisit data preprocessing to include more # of features and more # of sample data by 
   substituting more feature null values with appropriately derived values from the existing 
   dataset
2. Do more data analysis/data substitution to remove inaccurate data
3. Remove more data outliers to avoid model skewing
4. Revisit more data transformation techniques in addition to HotEncoder during preprocessing
5. Incorporate more data visualization to better understand feature correlatation
6. Revisit modeling with more choices of hyperparameter values and higher degrees of polynomial    feature transformation
