---
title: Tableau activity
nav: false
---


# Data visualisation with Tableau

`Tableau` is a powerful and flexible data visualisation tool. 

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
{% capture text %}
You will start to see the power of Tableau very quickly when you move to the Worksheet. {% endcapture %}
{% include alert.md text=text color="info" %}

Click on 'Sheet 1' at the bottom of the window. You will see that your columns have been placed in two categories, `dimensions` and `measures`.

{% include modal.md button="Tell me more" color="primary" title="Dimensions and Measures" text="A *dimension* is something that can be looked at categorically, like a list of countries. A *measure* is anything that can be put on a scale: a number, like a date, or currency." %}

{% capture text %}
1. Drag the dimension `Hospital name` to the `Rows` field at the top of the Worksheet
2. Drag `Number treated` from the Measures list to the `Columns` field at the top of the worksheet.{% endcapture %}
{% include card.md header="Make a simple bar chart" text=text %}

Voilà! You have your first chart. <i class="far fa-chart-bar"></i>

## Add filters

{% capture text %}
Oh-oh! There's a problem. One of the bars is far larger than the others, and it's not just that one hospital has been much more efficient than all the others.{% endcapture %}
{% include alert.md text=text color="warning" %}

There is an entry called `Queensland Reporting Hospitals` which records the sum of all the other entries. This is distorting the chart so we need to remove it. 

{% capture text %}
1. Drag `Hospital name` from the Dimensions List to the `Filters` box
2. Scroll down and uncheck the box next to `Queensland Reporting Hospitals`
3. Click OK
{% endcapture %}
{% include card.md header="Add a filter to your data" text=text %}

There's one more filter we need to add. In the 'Urgency' field, there is also a summary row that is distorting the data. So let's do it again for Urgency.

{% capture text %}
1. Drag `Urgency` from the Dimensions List to the `Filters` box
2. Scroll down and uncheck the box next to `ALL`. Make sure the others are checked.
3. Click OK
{% endcapture %}
{% include card.md header="Filter urgency results" text=text %}

## Sort and colour

It's time to make it look a bit nicer. 

{% capture text %}
1. Click the `Sort descending` button on the toolbar. 
2. Drag `Number treated` from the Measures list to the `Color` box under the heading 'Marks'
3. Click the `Color` button
4. Click `Edit colors`
5. Select a palette from the `Palette` drop-down. I chose 'Red-Green Diverging'
{% endcapture %}
{% include card.md header="Sort and colour" text=text %}

