Getting_and_Cleaning_Data
=========================

Este es el repositorio de alemary22 creado para el curso Getting and Cleaning Data.

1.- Descargue y descomprima los datos: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip dentro de tu carpeta local C:\Users\yourname\Documents\R\

2.- En RStudio, crear un script llamado run-analysis.R y guardelo en C:\Users\yourname\Documents\R\UCI HAR Dataset\

          run-analysis.R debe contener las instrucciones para calcular los promedios y la desviacion estandar de cada                     actividad, de acuerdo a:
                  1. Merges the training and the test sets to create one data set.
                  2. Extracts only the measurements on the mean and standard deviation for each measurement. 
                  3. Uses descriptive activity names to name the activities in the data set
                  4. Appropriately labels the data set with descriptive variable names. 
                  5. From the data set in step 4, creates a second, independent tidy data set with the average of each                               variable for each activity and each subject.

3.- En RStudio, escribir setwd("C:\\Users\\yourname\\Documents\\R\\UCI HAR Dataset\\") seguido de source("run_analysis.R")

4.- Guardar los resultados en la variable data <- read.table("data_set_averages.txt"), que contiene un archivo texto con los valores de los promedios y la desviacion estandar de cada actividad.
