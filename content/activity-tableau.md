---
title: Tableau activity
nav: false
---


# Data visualisation with Tableau

Tableau is a powerful and flexible data visualisation tool. 

## Before you start

Before doing this activity you will need to install Tableau onto your computer. Tableau Public is already installed on the student-use computers at Griffith. If you are using your own computer, follow the instructions below to install Tableau.

{% include button.md text="Install Tableau" link="workshop-prep.html" color="primary" %}

---

{% capture text %}
1. Download the sample data: [Queensland Hospital Procedures 2018](https://griffitheduau.sharepoint.com/sites/DigitalToolsforResearchApril2019/Shared Documents/General/Queensland Hospital Procedures 2018.xls)
2. Launch Tableau
3. Click 'Connect to data source'
4. Select the sample data from your Downloads folder
5. Click OK

The data should appear in columns on the bottom half of your screen.{% endcapture %}
{% include card.md header="Connect your data sources" text=text %}

## Prepare your data for use

You will see that Tableau attempts to detect what kind of value is in each column and assigns a value type accordingly. Tableau doesn't get all of these guesses correct, so we have to correct some of them. 

{% capture text %}
1. Click on the 'Abc' at the top of the 'Percent on time' column
2. Select 'Number (decimal)' from the list
3. Do the same with 'YoY Variation', 'Percent ready within time'
4. Click on the 'Abc' at the top of 'Date updated'
5. Select 'Date and time' from the list

The data should appear in columns on the bottom half of your screen.{% endcapture %}
{% include card.md header="Connect your data sources" text=text %}

## Make your first chart

You will start to see the power of Tableau very quickly when you move to the Worksheet. 

1. Click on 'Go to worksheet'

The value types are then placed in two categories, *measures* and *dimensions*.

{% include modal.md button="Tell me more" color="primary" title="Example Modal" text="A *measure* is anything that can be put on a scale—a number, like a date, or currency. A *dimension* is something that can be looked at categorically, like a list of countries." %}
