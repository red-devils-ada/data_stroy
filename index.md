---
title: The REAL carbon footprint of your food!
description: A data story through the food-related emissions 
image: /images/cow.jpg
layout: story
---


## Introduction

In October 2018, the Intergovernmental Panel on Climate Change (IPCC) released a special report about the impacts of global warming of 1.5°C above pre-industrial levels [1], making it more than clear that scenario should be avoided at all costs. The warming is mainly due to greenhouse gas emissions. In this context, it is of most interest to evaluate our food system with a new view. How does it contribute to the worldly emissions? And what is the real carbon footprint of what we eat?

This data story will first have a look at the direct emissions linked to agriculture, differentiating between emissions due to vegetal or animal products. Then a deeper study on Belgium's case will be pursued. Next, we will look at the trade of food and how it impacts the emissions of the country. The emissions linked with the transportation of this traded food are going to be added. This will allow at the end to compute the Extended Carbon Footprint of Belgium's food which includes the direct emissions, the ones of trade and the ones of transportation.  This indicator gives a better view, in a globalized world, of the real emissions our food is responsible for. Finally, the same methodology will be applied to each country in the EU.

## A global view

Let us first get a general overview of what kind of problem we are dealing with.

### Is emission due to agriculture significant?
  
  
<iframe src="{{ site.baseurl }}/images/graphs/emissions_sector.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

Emissions are measured in CO2eq, this is a unit based on the global warming potential (GWP) of different greenhouse gases. The CO2eq unit measures the environmental impact of one tonne of these greenhouse gases in comparison to the impact of one tonne of CO2. The total world greenhouse gas emissions in 2017 add up to 49.4 billion tons of CO2 equivalent. Nearly half of it is due to the energy sector, explaining why the energy transition is such a hot topic nowadays. By 2017, the agriculture sector emissions reach 5 billion tons of CO2 equivalent which is 10% of the total emissions (note that we neglect the energy use caused by agriculture). Another point is that most of the food products will be traded and transported to be consumed elsewhere. Thus some of the emissions linked to the transport sector come from this trade of food. Further in the data story, this point will be assessed. 

### What causes agriculture emissions?

Agriculture-related emissions can be classified into ten categories.  Among them, enteric fermentation is predominant. When the ruminants are digesting, fermentation takes place emitting methane (a strong greenhouse gas). Three other categories that have an important role are synthetic fertilizers, rice cultivation and manure left on pasture.

<iframe src="{{ site.baseurl }}/images/graphs/detailed_emissions_world.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

A hot topic in global warming discussions is the impact of meat production. Many people choose a vegetarian lifestyle to reduce their ecological footprint. Throughout this data story, we will explore if this is grounded, by aggregating the categories into emissions linked to animal products and the ones linked with vegetal products.

<iframe src="{{ site.baseurl }}/images/graphs/veg_anim_emissions_world.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

Animal products generate about 3 million of gigagrams of CO2 equivalent. This is nearly double that of vegetal products. Knowing that the main source of emissions comes from the digestion of ruminants, this is an expected result. The ecological movement for vegetarianism definitely has some ground!

### Who are the main countries responsible for it?

<iframe src="{{ site.baseurl }}/images/maps/emissions_due_to_agriculture.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

<div class="boxed">Some fun trends about Mongolia to verify for the reader: In the decade from 1990 to 1999, livestock numbers increased, largely due to a rapid rise in the goat population from approximately 5 million head in 1990 to 11 million head in 1999. The widespread and multi-year drought of 2000-2002 caused high livestock mortality in the national herd. Accordingly, GHG emissions from the agriculture sector dropped during this period. From 2004 to 2009, livestock numbers rose again with government support in veterinary and feed services. However, in 2010, livestock production declined again due to extreme winter events <a href="https://www.climatelinks.org/sites/default/files/asset/document/Mongolia%20Fact%20Sheet%20-%20rev%2010%2008%2016_Final.pdf">[1]</a>. </div>

In most countries, the emission per capita has been decreasing, a welcome trend. China, which is mostly seen as a heavy polluter, has very low emission per person (mostly due to their enormous population). The recent heaviest polluter is surprisingly Mongolia. Herding is a business and a way of life in Mongolia. A large segment of the Mongolian population (small-scale and large-scale herders) remains dependent on livestock production as their primary means of livelihood. 

Next to Mongolia, the biggest consumers are Australia, Uruguay and New Zealand (all in the top 10 meat consuming countries of the world<a href="https://www.worldatlas.com/articles/top-meat-consuming-countries-in-the-world.html"> [2] </a>.


### Who are the food producers?

<iframe src="{{ site.baseurl }}/images/maps/production.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

As expected, the highest producers are China, India, Brazil and the USA (four of the five most populated countries in the world). Their (and most countries') production has increased over the last 16 years. 

## Calculating the real emission

Until now, we've only looked at the trivial emission, of products produced in a country. However, to get a realistic representation of emission per capita, one needs to take into account imported and exported goods. A country should be responsible for the emissions of the products they import while the responsability for the ones they export is not theirs. In this section, we will show the corrected emission per capita of Belgium, where exported goods are not taken into account, while imported goods are. 

### Correcting for import and export

In this section, we will show the corrected emission per capita of Belgium, where exported goods are not taken into account, while imported goods are. 

<iframe src="{{ site.baseurl }}/images/graphs/corrected_emissions_bel_swiss.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

We see that the correction only has minimal influence. While Belgium and Switzerland both import many goods, the export seems to make up for this. 

### Correcting for transportation

More than just the CO2 of imported goods, transport also influences the emission. In this section, we will calculate the emissions due to import transportation of all European Countries, and see how this influences our results.

The four most common ways of transporting food are by plane (air), truck (road), train (rail) or boat (sea). Below, the respective emissions per km\*ton of imported goods are given.

<iframe src="{{ site.baseurl }}/images/graphs/transport_mode.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

Air transport emits 690 grams of CO2eq per km\*ton, more than 9 times the emission of road and almost 50 times that of sea and rail<a href="https://www.sciencedirect.com/science/article/pii/S0959652615000438">[3]</a>.

The total emission per km\*ton is calculated by taking the distance between the two countries (from the capitals) and multiplying it by the number of goods that are imported, according to the mode of transportation (obtained by the EuroStat database).  

<iframe src="{{ site.baseurl }}/images/graphs/transport_proportion.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

Here we can see the proportion of transportation means used per country (use this to interpret the impact of transportation emission per country).  

#### The Extended Carbon Footprint of Belgium's food

First, let us have a look at what countries Belgium trades with, and the impact on the emissions.

<iframe src="{{ site.baseurl }}/images/maps/traded_product_with_belgium_(tons)
.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

Here, positive values mean import, while negative means that Belgium exports to the country. The countries from which Belgium imports and to which it exports change a lot from year to year. However, there isa general tendancy to have more imports than exports. If we look at the year 2017, the main imports were coming from Colombia, Ukraine, France, Canada and Brazil. The main destination for export producte were, in 2017, Germany, Italy, United Kingdom, Oman and China.

<iframe src="{{ site.baseurl }}/images/graphs/correction_emission_belgium.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

In this plot, the contribution of trade and transport to emission is plotted for Belgium. While animal products normally contribute more greenhouse gases, the import and transportation of vegetal products have a bigger influence than their animal counterparts. Indeed Belgium is a meet producer and exports a lot of it. Notice also that for vegetables, the transport has a bigger influence (due to large volumes), while for animal products the transportation costs can almost be neglected.  

This leads us to the following conclusion results for Belgium: 
<iframe src="{{site.baseurl}}/images/graphs/emission_belgium_corrected.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

Overall, the corrections have a minimal influence. The biggest difference is in transportation of vegetal products, as these get imported and exported in bigger quatity (weight) than meat.

Now, we will extend this approach to all EU countries. 

## A comparative study with the other EU countries

<iframe src="{{site.baseurl}}/images/graphs/bar_eu_countries" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

<iframe src="{{site.baseurl}}/images/maps/emissions_(in_tons_of_co2_eq_per_capita)_of_european_countries.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

<iframe src="{{site.baseurl}}/images/maps/corrected_emissions_(in_tons_of_co2_eq_per_capita)_of_european_countries.html" frameborder="0" allowfullscreen="false" style='width:100%; height:600px' scrolling="no"></iframe>

Incorporating traded goods and transport only has a limited amount of influence emissions. While the transport of vegetables is not neglectable, the huge amount of GHG emissions by animals overshadows this. 

## Conclusion





