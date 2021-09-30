# SQL Pair #3: SQL Whiteboarding

Let's do a quick review of SQL, and then also practice pseudocoding in a shared Google doc 
(emulating a whiteboarding interview) while we're at it!

`TABLE: RESTAURANTS`
<table>
  <tbody>
    <tr>
      <th>Name</th>
      <th>Cuisine</th>
      <th>Date_Founded</th>
    </tr>
    <tr>
      <td>Chipotle</td>
      <td>Mexican</td>
      <td>7/13/1993</td>
    </tr>
    <tr>
      <td>Taco Bell</td>
      <td>Mexican</td>
      <td>3/21/1962</td>
    </tr>
    <tr>
      <td>McDonald's</td>
      <td>American</td>
      <td>4/15/1955</td>
    </tr>
    <tr>
      <td>Popeye's</td>
      <td>American</td>
      <td>NULL</td>
    </tr>
    <tr>
      <td>Panda Express</td>
      <td>Chinese</td>
      <td>1/23/1983</td>
    </tr>
  </tbody>
</table>

`TABLE: CONTINENT`
<table>
  <tbody>
    <tr>
      <th>Cuisine</th>
      <th>Continent</th>
    </tr>
    <tr>
      <td>American</td>
      <td>North America</td>
    </tr>
    <tr>
      <td>Mexican</td>
      <td>North America</td>
    </tr>
  </tbody>
</table>

Allocate half the pair time to Part 1 and half the time to Part 2, getting through as many questions as possible during the allotted time.

**Part 1: Person #1 reads the questions. Person #2 whiteboards the answers.**
 1. Show me everything in the RESTAURANTS table.
 2. Show me the Names in the table.
 3. Show me the unique Cuisines.
 4. Show me 3 rows of data.
 5. Sort the restaurant names alphabetically.
 6. Exclude the rows with NULL values.
 7. What is the number of rows without NULL values?
 8. Show me all restaurants founded between 1/1/1950 and 1/1/1970.
 9. Out of all the restaurants, show me all restaurants that start with the letter P.

**Part 2: Person #2 reads the questions. Person #1 whiteboards the answers.**
 1. In the RESTAURANTS table, how many restaurants are there of each type of cuisine?
 2. Rename the new column you created as Num_Cuisine.
 3. For every restaurant, show me the continent that its cuisine is from. If the continent isn't in the CONTINENT table, don't show the data.
 4. For every restaurant, show me the continent that its cuisine is from. If the continent isn't in the CONTINENT table, still show the data.
 5. Show me restaurants that are Mexican or Chinese.
 6. Show me restaurants that are not American.
 7. Output the name of the Mexican restaurant that was founded most recently.
