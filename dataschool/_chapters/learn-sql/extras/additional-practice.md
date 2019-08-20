---
section: Extras
title: Additional Practice
meta_title: ''
description: ''
number: 1000
authors: []
reviewers: []
feedback_doc_url: ''
image: ''
is_featured: false
img_border_on_default: false
is_under_construction: false
is_community_story: false
story_intro_blurb: ''
reading_time: 

---
For practicing we will be using a online music store database. Here is the entity relationship diagram of the schema.

![](/assets/images/chinookERD.png)

Feel free to explore the data by using SELECT * FROM \[table name\] in the SQL editor below:

<sqlbox></sqlbox>

## Select Questions

Select all columns and rows from the albums table in the SQL box below:

<sqlbox

answer='SELECT * FROM albums;'

hint='Try using SELECT *'

correct_message='Correct! SELECT * can be used to return all of the columns from any table you have access to.'></sqlbox>

Select all columns from the albums table where the album is  in the SQL box below:

<sqlbox

answer="SELECT * 

FROM albums 

WHERE albums.TITLE = 'Let There Be Rock'"

hint='Try using SELECT *'

correct_message='Correct! SELECT * can be used to return all of the columns from any table you have access to.'></sqlbox>