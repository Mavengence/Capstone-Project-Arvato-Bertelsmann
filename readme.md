 <div style="border-bottom:none;">
<div align="center">
<img src="img/logo.png" width="700" height="250">
<hr>
<h1>Capstone Project | Arvato Bertelsmann<h1>
<h3>Udacity Data Science Nanodegree</h3>
<img src="img/Udacity_logo.png" width="400" height="170">˘

</div>
</div>

## Motivation

As I enrolled for the Udacity Data Science Nanodegree, I didn’t know where my journey is going to end. This time has now arrived after I chose the dataset provided by Arvato for this final project to graduate from the Nanodegree.
I am a Computer Science Master student from Germany, for that reason I chose this german company, because it provided data about the german population which appeared to be really interesting to me.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
The dependencies to this project are stored in the file:
   -environment.yml

I use python version 3.7.4
```

###

```

+-- arvato_data
|   +-- DIAS_attributes.xlsx                        | Additional Information about the data
|   +-- DIAS_information.xlsx                       | Additional Information about the data
|   +-- Udacity_MAILOUT_052018_TEST.csv             | Test data without label
|   +-- Udacity_MAILOUT_052018_TRAIN.csv            | Train data with label
+-- img
|   +-- Udacity_logo.png
|   +-- logo.png
+-- Arvato Project Workbook.ipynb                   | Main Project <includes all the work>
+-- environment.yml                                 | The dependencies and their version for this project
+-- readme.md
+-- .gitignore              

```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
clone the repository: https://github.com/Mavengence/Capstone-Project-Arvato-Bertelsmann-Kaggle.git
```

## Analysis

#### Person Topic
* The average age of Arvato customers is 70 years old. Whereas the overall average age of the population dataset is around 50 years old people. They are most likeli cutural driven eldery.
* The customers are more likeli to have their teens in the "60ies - economic miracle (Mainstream, O+W)", whereas the median of the entire german population had their teens in the "80ies - Generation Golf (Mainstream, W)" of this dataset.
* The average Arvato customers has a saving behaviour of saving "very high", whereas the wide population is only a "average" savor. This could lead to the conclusion Arvato is targeting people which potentially have more money on the bank.
* Additionally, customers have a median value of financial investors to be very high with an overall median of average behavior. So Arvato customers are more likeli to invest money.
* Another small deviation is the finiancial minimalism. Arvato customers appear to be less financially minimalistic than the regular population.
* Customers have according to the dataset a lower affinity for a sensual mindset.
* Customers furthermore have a slightly affinity for being traditionally minded.
#### Household Topic
* The customers have a median consumption type value of "Versatile" instead of the wider population which has a consumption type of "Family". This leads to the conclusion that Arvato is not really after families, but wants to send ads to people with a versatile lifestyle.
#### 125m x 125m Grid Topic
* The average customer is a Buyer > 24 months, which means that the transactional activity based on the product group ALL OTHER CATEGORIES is way higher than the average population which is averaglely a Singlebuyer 0-12 months.
* Furthermore, the customers of Arvato have a median value of buying books in the last 13-24 months, whereas the overall population didn't buy so many books. This could be an indicator for a more academic target.
* A very interesting point is that the target for customers is people with transactional activity based on the product group COMPLETE MAIL-ORDER OFFERS is Multi-/Doublebuyer 13-24 months, whereas the entire population's behavior is unknown or very low. The target is people who bought things since a 2 years period of time.

#### Specific Customer Behaviour
* Product Group: This is very equally distributed between food and cosmetic. There is no clear tendency that either women or men are more likely to be customers.

* Online Purchase: This is undeniably the case the most customers (91%) are buying the things online. So a digital marketing campaign for online purchasers makes a lot of sense.

* Customer Group: This is most often multi buyers (69%) and only (31%) are single buyers. Since there is no further information about this column, I assume it means that people who buy at Arvato are (69%) people who already bought something in the past from Arvato. This was already shown above in "125m x 125m Grid Topic", that Arvato customers frequently multi buy things online.

## Summary

```
Since the score is to a very high percentage of 0’s, a mean accuracy is not good, because in this way an accuracy of 98% can be easily achieved by only predicting 0’s. In this way, the metric AUC-Score is used.

My training score after splitting the data was 78,62%
My test score after uploading it to Kaggle was 73,33%
```

## Author

* **Tim Löhr** - I built this entire notebook completely by myself. If you have questions you can contact me under timloehr@icloud.com

## License

This project was done due of my [Udacity Data Science Nanodegree](www.udacity.com). This was the final project for succeeding in the course.

## Acknowledgments

* Thanks to Udacity for teaching me so many interesting and helpful things
* Thanks to Arvato for providing this dataset
