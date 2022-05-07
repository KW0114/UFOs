# UFO Sighting Website

## Overview and Purpose

The purpose of this project was to practice pairing HTML with JavaScript as well as CSS to
create a visually appealing web page that has dynamic table aspects. With a pre-made dataset,
you are able to filter based on several user inputs to narrow the table to specific criteria. 

## Results

### Web Page

Let's take alook at the web page! The header info includes a quick synopsis behind why this 
page was created:

![web page screenshot](https://github.com/KW0114/UFOs/blob/a80c4719cb4926449942f402a54e127af02c77e6/static/images/website_headers.png)


### Original Data Table

Here is a quick look at the original, unfilitered table along with the filter options available:

![table screenshot](https://github.com/KW0114/UFOs/blob/a80c4719cb4926449942f402a54e127af02c77e6/static/images/original_table.png)


### Filtered Table Example

In order to filter the table, simply type a search criteria into one (or more) of the search text
boxes. When you're finished, simply click anywhere else on the screen, or press enter to update
the table. You can easily clear the results by deleting your text input from the field and 
pressing enter again.

As you can see in this example, there is only one result on 1/2/2010 in Florida:

![filtered table screenshot](https://github.com/KW0114/UFOs/blob/a80c4719cb4926449942f402a54e127af02c77e6/static/images/filtered_table.png)


## Summary

### Drawbacks 

I think a major drawback of this original set up is that a lot of user input information is not set
up in a user-friendly manner. For example, cities and states are in all lower-case letters, when usually
we are used to seeing states capitalizes such as FL. There are also some discrepancies in the way that
the duration is input as data. Some entries are expressed in minutes (20 minutes), others are more
abstract like "several hours". There are also tons of typos and misspellings in many different places
in the data. It would be worth spending some extra time cleaning up this data before throwing it into
a filterable table for the user. Even the descriptions are super chaotic and include some weird characters.

![duration screenshot](https://github.com/KW0114/UFOs/blob/a80c4719cb4926449942f402a54e127af02c77e6/static/images/durations.png)

### Suggestions

1. My first major suggestion would be to simply clean the data so that it follows one specific pattern. 
I would probably just start by making sure all the durations are in the same format, either choose minutes,
hours, etc. 

2. Users would benefit from having a drop down list of options for them to choose from when filtering data.
They may not want to look through the whole table in order to see what cities they can choose from, and 
honestly that's the point of even having a filter: to save time. If there are any misspellings of cities, this
will need to be corrected in step 1 as well.


