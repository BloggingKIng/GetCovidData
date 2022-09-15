# GetCovidData

You can use this API to access basic `Covid Data` with simple commands. <br>
This package makes it easy for you to get Covid Data. You can use it in the backend to get covid data and display it on your website or use this data in your python scripts!

<h1> Installation </h1>

This API can be installed by using <b> pip </b> in the following way: <br>
<code> pip install GetCovidData </code>
 
 <h1>Usage:</h1>

Here is how to use this package (for more details about <b> syntax</b> and <b> functions </b>  you can take a look at the <code>examples.py</code> file)

<table>
<tr><th>Function</th><th>Params:</th><th>What it does!</th></tr>
<tr><td>get_covid_info ()</td><td> display (True/False), default=True</td><td>Return a JSON object with the latest info of Covid like "Active cases". If diplay=True it will also print the covid info.</td></tr>
<tr><td>get_covid_by_continent ()</td><td>None</td><td>Returns a pandas dataframe containing the Covid Info in all continents!</td></tr>
<tr><td>get_covid_by_continentJSON()</td><td>None</td><td>Retuens a JSON object with Covid Situation in all continents</td></tr>
<tr><td>get_covid_all_countries()</td><td>None</td><td>Returns a pandas DataFrame containing Covid Info in all countries</td></tr>
<tr><td>get_covid_all_countriesJSON()</td><td>None</td><td>Retuens a JSON object with Covid Info in all countries</td></tr>
<tr><td>get_covid_in_countries()</td><td>*args countries(countries to get covid data of), json= False</td><td>Return a pandas dataframe containing covid info in given countries. You can pass as many countries as you want. If json=True it will return a JSON object instead</td></tr>
</table>
