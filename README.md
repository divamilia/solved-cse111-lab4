Download Link: https://assignmentchef.com/product/solved-cse111-lab4
<br>
<strong>DATABASESYSTEMS</strong>




In this lab session you have to write 15 SQL queries for the TPCH database created and populated in the previous labs. The queries are the following (1 point per query):

<ol>

 <li>Find the total price paid on orders by every customer from FRANCE in 1995. Print the customer name and the total price.</li>

 <li>Find the number of suppliers from every region.</li>

 <li>How many orders are posted by customers in every country in AMERICA?</li>

 <li>How many parts with size below 20 does every supplier from CANADA offer? Print the name of the supplier and the number of parts.</li>

 <li>Find the number of orders posted by every customer from GERMANY in 1993.</li>

 <li>How many unique parts produced by every supplier in CANADA are ordered at every priority? Print the supplier name, the order priority, and the number of parts.</li>

 <li>How many orders do customers in every nation in AMERICA have in every status? Print the nation name, the order status, and the count.</li>

 <li>Find the number of distinct orders completed in 1995 by the suppliers in every nation. An order status of F stands for complete. Print only those nations for which the number of orders is larger than 50.</li>

 <li>How many different order clerks did the suppliers in UNITED STATES work with?</li>

 <li>Find the minimum and maximum discount for every part having ECONOMY and COPPER in its type.</li>

 <li>Find the supplier with the largest account balance in every region. Print the region name, the suppliername, and the account balance.</li>

 <li>What is the maximum account balance for the suppliers in every nation? Print only those nations forwhich the maximum balance is larger than 9000.</li>

 <li>How many line items are supplied by suppliers in AFRICA for orders made by customers in UNITED STATES?</li>

 <li>List the maximum total price of an order between any two regions, i.e., the suppliers are from oneregion and the customers are from the other region.</li>

 <li>How many distinct orders are between customers with positive account balance and suppliers withnegative account balance?</li>

</ol>

In order to complete the lab you have to perform the following tasks:

<ol>

 <li>Write the SQL statement corresponding to every query in the file test/x.sql, where x is the number of the query above. Every query goes into its separate file. These are the only files you have to modify and submit in this assignment.</li>

 <li>You can check the correctness of your queries by executing the command ./test.sh in the terminal. You have to be in the main lab folder. The expected output is available in results/x.res, where x is the number of the query. The output produced by your code is available in output/x.out. They have to match for every query, e.g., res has to match with 1.out.</li>

 <li>In case there are any errors, repeat the process from step 1 for the incorrect queries.</li>

 <li>The submission consists of a compressed zip file that contains the files in the test The name of the file has to be lab-4.zip. When you create the file, include the folder test into the compression, not every file test/x.sql separately.</li>

</ol>