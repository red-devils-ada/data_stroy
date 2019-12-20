---
title: Emissions
description: Detailed analysis of emission due to agriculture per country
image: /images/emissions.jpg
layout: post
---


## Introduction

On this page, we will dive deeper into the analysis of the emissions for each country. We will see how these emissions changes when we consider the emission of the whole country or per capita in each country.

## Distribution of the emissions
First, let's look at the distribution of the emission when we consider the whole country.

* [Histogram of emission] + bar chart

We can see that the distribution is heavy-tailed, it means that most of the countries do not produce a lot of emissions but some emit huge amounts of CO2. If we look at those countries, we can see that these are the most populated country which is something we could expect.


## Emission per capita

To balance this bias introduced by the number of inhabitants we can divide all the emissions by the number of people in the country to obtain the emission per capita.

* [Histogram of emission per capita] + bar char 

We see that there is one country having a much higher emission per capita than all other, it is the `Falkland Islands (Malvinas)`. The emission seems not so big on absolute (90 Gigagrams of CO2eq), however, the island is only populated by 2000 people. Furthermore, the island (which has the 5th highest Gross Product per Capita) is known for its industry of sheep farming. This explains that the emission coming from animals is the biggest one per capita. For now let us remove that country because even if the data is correct, we want to focus on larger countries and this particular case can be neglected.

To have a better view we can remove this country and look again at the distribution of emission per capita

* [Histogram of emission per capita] + bar char (without Falkland)

The countries that emit the most are not necessarily the ones we expected. Indeed we do not see China or India.
That's because this dataset focuses on emission due to agriculture. Moreover, we can see that the top 10 emitters are the same (almost in the same order) if we look at the total emissions and the emissions due to animal products. These countries are known for producing a lot of meat.