# class5-homeworks
# Load, Organize, Compute and Visualize a dataset
#************************************************

1) Filename = Get a file from input

2) List = Load dataset from the file

#Import Pandas

   2.1) Print any row of List (pandas access data by row)
        
   2.2) Print any column of List (pandas access data by column)

   2.3) Print any value of List(pandas access data by value)

3) Compute Mean

   N = number of all List items in each column
   S = sum of all List items in each column 
   Mean = S / N


4) Compute Standard Deviation

   Sn  = sum((each List item in each column - Mean) ^ 2)
   Std = Sqrt( Sn / (N -1))
#**************************
Second solution for 3, 4:

#Import numpy lib

3') call mean()
4') call std() 
#**************************
#Import matplotlib.pyplot

5) Make the plot histogram 
   For each column in List 
       get values
       plot histogram
       save in a file
  
6) Make the plot scatter
   For each pair of columns
       get values
       plot scatter
       save in a file

7) Add header to the dataframe
       Columns = ['ID number',
                  'Diagnosis','Radius_M', 'Texture_M', 'Perimeter_M', 'Area_M','Smoothness_M', 'Compactness_M', 'Concavity_M', 'ConcavePoints_M', 'Symmetry_M', 'FractalDimension_M',
                  'Radius_SE', 'Texture_SE', 'Perimeter_SE', 'Area_SE','Smoothness_SE', 'Compactness_SE', 'Concavity_SE', 'ConcavePoints_SE', 'Symmetry_SE', 'FractalDimension_SE',	
                  'Radius_W', 'Texture_W', 'Perimeter_W', 'Area_W','Smoothness_W', 'Compactness_W', 'Concavity_W', 'ConcavePoints_W', 'Symmetry_W', 'FractalDimension_W']

8) Make a heatmap between Mean features and Diagnosis
       plot scatter
       save in a file
