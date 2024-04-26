---
layout: page

title: "📃 Student Performance Dataset"
date: 2022-10-05T14:08:51+05:30
draft: false
tags : ['Python','Data-engineering','AWS VM']
description : "Dataset of results of candidates who sat for GCE AL (University Entrance Examination) containing  more than 300,000 records "

website: "kaggle.com/datasets/sasikaamarasinghe/student-performance-gce-al-exam-2020-sri-lanka"

# img: assets/img/12.jpg
importance: 5
category: "Data + Machine Learning"
related_publications: true
---


## 🌐 [Kaggle Link](https://www.kaggle.com/datasets/sasikaamarasinghe/student-performance-gce-al-exam-2020-sri-lanka)

This dataset contains information on the performance of students in the GCE Advanced Level (AL) exam in Sri Lanka in 2020. It was collected by [Sasika Amarasinghe](https://www.kaggle.com/sasikaamarasinghe) and is available on [Kaggle](https://www.kaggle.com/datasets/sasikaamarasinghe/student-performance-gce-al-exam-2020-sri-lanka).

<!-- ![Dataset coverimage](https://storage.googleapis.com/kaggle-datasets-images/2302701/3874430/392a677f33eed254db4316865e966ab4/dataset-cover.jpg?t=2022-06-28-10-41-30) -->

---
>I have removed some columns of the original dataset due to ethical reasons. But here's a sample of the data when a search query is given.

When a name of a school candidate is given, all the details including the birthday (which is not originally published on the exam result sheet) are given. **(About pretty much anyone from 2020 AL batch 😄)**
---
## Dataset Characteristics
- The dataset consists of over 300,000 records of student performance in the GCE AL exam in Sri Lanka.
- The data includes information on student identification, school, district, medium of instruction, stream, and their scores in different subjects.
- The data also includes the overall Z-score of each student, which is a standard score that indicates the number of standard deviations by which the student's exam results are above or below the mean.

## Variables
- `Index`: A unique identifier for each student
- `School ID`: Identification number of the school
- `District`: District where the school is located
- `Stream`: Science, Arts, or Commerce stream of the student
- `Medium`: Sinhala or English medium of instruction
- `Subjects`: The scores of the student in each of the subjects - Mathematics, Science, English, Buddhism, and History
- `Z-Score`: The overall Z-score of the student

## Use Cases
- This dataset can be used to study the performance of students in different subjects and in different streams, medium of instruction, and districts.
- The data can also be used to study the relationship between student performance and demographic factors such as medium of instruction and district.
- This dataset can be used to identify the factors that contribute to the performance of students in the GCE AL exam and to make recommendations for improving student performance in the future.

## Usability
- 9.41 / 10

## Sources

- Data were collected from (https://www.doenets.lk/examresults) which is the exam result site in Sri Lanka

## Collection Methodology

- Data were scraped data by a python script written by the author using the index no as the key.
- Later the national identity card numbers were decoded to extract applicants' birthdays and gender.
- For privacy concerns, "Full name","National Identity Card no" and "Index no" were removed, but the birthdays and genders have been added to the dataset.
- Used AWS instances to collect data parallely to reduce the time and data usage.

I got a `bronze` 🥉 medal for this dataset with 36 upvotes in the Kaggle Community. and very good feedback from the Community Members.

## Testimonials for the dataset

> ⭐ This can be actually used to look after the academic likelihoods and whereabouts of Sri Lankan students' academics! Great job! -- [VISHESH THAKUR - Datasets Expert](https://www.kaggle.com/vishesh1412)

> ⭐ This data could be used for EDA, visualization and even model development! Good work and great dataset! -- [RAVI RAMAKRISHNAN-Notebooks Grandmaster](https://www.kaggle.com/ravi20076)

## Github Link

I haven't publicized the code for the datascraping and datapreprocessing,search queries of students. Not available due to ethical reasons.

