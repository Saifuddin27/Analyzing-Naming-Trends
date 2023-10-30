# Analyzing-Naming-Trends

Project: Analyzing the naming trends using Python
Industry: General
Problem Statement:
The dataset is in Zipped format, we have to extract the dataset in the program, visualize the number of
male and female babies born in a particular year, and find out popular baby names.
Description: This project not only focusses on implementing data manipulation and data visualization
using Pandas library, but also tests your ability to deal with real word problem statements.
Dataset: Popular baby names data provided by Social Security Administration (SSA) of United States
How to download the dataset:
 Go to https://www.ssa.gov/oact/babynames/limits.html
 Click on ‘National data’
 Get the zipped file
Here’s what the zipped folder looks like,
Hints:
 First, use Pandas, zipfile, and BytesIO library to extract the data. Find out a way to extract only
files that consists useful data.
 Hint: pd.read_csv(BytesIO(z.read(file_name)), encoding='utf-8', engine='python', header=None)
 Then, visualize the number of male and female babies born in a particular year with the help of
pandas.DataFrame.plot, then Analyse baby names by sorting out all birth counts.
 Then, analyse baby names by sorting out top 100 birth counts and group them by names to find
out popular baby names 
