# Disemvowel Trolls

<br>
<br>

## Instructions
Trolls are attacking your comment section!

A common way to deal with this situation is to remove all of the vowels from the trolls' comments, neutralizing the threat.

Your task is to write a function that takes a string and return a new string with all vowels removed.

For example, the string "This website is for losers LOL!" would become "Ths wbst s fr lsrs LL!".

Note: for this kata y isn't considered a vowel.

<br>
<br>

## Solution
~~~
-- # write your SQL statement here: you are given a table 'disemvowel' with column 'str', return a table with column 'str' and your result in a column named 'res'.

SELECT
  A.STR,
  REGEXP_REPLACE(A.STR, '[aeiou]', '', 'gi') RES
FROM
  DISEMVOWEL A;
~~~

<br>
<br>

## Output
Time: 1182ms Passed: 8Failed: 0
Test Results:
SELECT Results (Top 100 of 103)
Results: Actual (Top 100 of 103)
Results: Expected
columns
column_names
Query
You have passed all of the tests! :)