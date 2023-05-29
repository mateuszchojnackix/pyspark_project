# Zaliczenie: Analiza zbioru danych filmowych przy użyciu Apache Spark

## Opis zaliczenia
Celem projektu jest przeprowadzenie analizy zbioru danych filmowych za pomocą Apache Spark. Zbiór danych zawiera informacje o ocenach filmów, a dane pochodzą z projektu MovieLens.
W projekcie wykorzystywane są narzędzia takie jak Google Colab i Jupyter Notebook do analizy danych, a także biblioteki takie jak PySpark, pyspark_dist_explore, pandas i matplotlib do manipulacji i wizualizacji danych.

## Etapy projektu
Projekt składa się z następujących etapów:
- Wprowadzenie do Sparka i instalacja niezbędnych bibliotek.
- Wczytanie danych i zapoznanie się z ich strukturą.
- Analiza danych i odpowiedzi na postawione pytania.

## Postawione pytania i analiza danych
W projekcie odpowiedziano na następujące pytania dotyczące analizy zbioru danych filmowych:

- Z jakich kolumn składają się wczytane zbiory danych?
- Informacje o ilu filmach znajdują się w dostarczonym zbiorze?
- Oceny ilu użytkowników znajdują się w zbiorze?
- Czy w zbiorze danych występują braki?
- Ile filmów nie posiada ocen? Które filmy nie mają ocen?
- Który film ma najwyższą średnią ocenę? Jeśli istnieje wiele filmów z taką samą najwyższą średnią oceną, podaj ten z największą liczbą głosów.
- Jaki procent filmów ma tylko maksymalne oceny?
- Który film ma najwyższą minimalną ocenę? Jeśli istnieje wiele filmów z taką samą najwyższą minimalną oceną, podaj ten z największą liczbą głosów.
- Jaki jest rozkład ocen?
- Ile filmów jest zaklasyfikowanych jako filmy dokumentalne?
- Który z filmów dokumentalnych z co najmniej 10 ocenami ma najwyższą średnią ocenę?
- Jakie są różnice w liczbie filmów w zbiorze danych rok po roku? (Uwzględniono, że znacznik czasowy reprezentuje liczbę sekund od roku 1960.)
- Średnio ile kategorii jest przypisanych do jednego filmu? Który film ma najwięcej kategorii i jakie są to kategorie?

## Wyniki analizy

Wyniki analizy danych obejmują:
- Wypisanie kolumn dla poszczególnych zbiorów danych.
- Informację o liczbie filmów w zbiorze.
- Informację o liczbie użytkowników, którzy wystawili oceny.
- Sprawdzenie występowania braków danych w poszczególnych zbiorach.
- Wskazanie liczby filmów bez oc.

---

# Project: Analyzing a Movie Dataset Using Apache Spark

## Project Description
The aim of this project is to perform analysis on a movie dataset using Apache Spark. The dataset contains information about movie ratings and is sourced from the MovieLens project.
The project utilizes tools such as Google Colab and Jupyter Notebook for data analysis, along with libraries such as PySpark, pyspark_dist_explore, pandas, and matplotlib for data manipulation and visualization.

## Project Stages
The project consists of the following stages:
- Introduction to Spark and installation of necessary libraries.
- Loading the data and familiarizing with its structure.
- Data analysis and answering specific questions.

## Questions Posed and Data Analysis
The project addresses the following questions related to the movie dataset analysis:
- What columns are included in the loaded datasets?
- How many movies are present in the provided dataset?
- How many users' ratings are included in the dataset?
- Are there any missing values in the dataset?
- How many movies have no ratings? Which movies are they?
- Which movie has the highest average rating? If multiple movies have the same highest average rating, provide the one with the most votes.
- What percentage of movies have only maximum ratings?
- Which movie has the highest minimum rating? If multiple movies have the same highest minimum rating, provide the one with the most votes.
- What is the distribution of ratings?
- How many movies are classified as documentaries?
- Among the documentaries with at least 10 ratings, which one has the highest average rating?
- What are the differences in the number of movies in the dataset from year to year? (Taking into account that the timestamp represents the number of seconds since 1960.)
- On average, how many categories are assigned to a single movie? Which movie has the most categories, and what are they?

## Analysis Results
The analysis results include:
- Listing the columns for each dataset.
- Information about the number of movies in the dataset.
- Information about the number of users who provided ratings.
- Checking for missing data in the datasets.
- Indicating the number of movies without ratings.
- Identifying the movie with the highest average rating and, if applicable, the most votes.
- Determining the percentage of movies with only maximum ratings.
- Finding the movie with the highest minimum rating and, if applicable, the most votes.
- Analyzing the distribution of ratings.
- Counting the number of movies classified as documentaries.
- Identifying the documentary movie with the highest average rating among those with at least 10 ratings.
- Examining the differences in the number of movies in the dataset year by year.
- Calculating the average number of categories assigned to a single movie and identifying the movie with the most categories and listing them.
