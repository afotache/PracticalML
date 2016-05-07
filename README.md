---
title: "Practical Machine Learning - Final Project Report"
author: "Alina Fotache"
date: "May 8, 2016"
output: html_document
---
# Overview
One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants.This project uses data from these accelerometers of 6 participants, which were asked to perform barbell lifts correctly and incorrectly in 5 different ways. The data sources are specified below, in two files - a training set and a test set. The objective is to predict the manner in which they did the exercise. This is the "classe" variable in the training set. This report will explain the model, how crossed validation was used, what is the expected sample error and the reasoning behind the choices made. We will also include the results of predicting 20 different test cases. 
