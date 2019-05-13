# Final project Jesse Pannekeet

<h1>Problem statement</h1>
<p>At the moment, immigration is a heavily debated topic in Europe/the Netherlands but these debates rarely tell the whole story. Distinctions between first- and second-generation immigrants are usually not factored into the debate and they are often focused on specific countries while leaving out others. Politicians and voters could both benefit from visualisations of data that tell the whole story.

<h1>Solution</h1>
<h3>Summary</h3>
<p>A visualisation of immigration to Europe/the Netherlands factoring in country of origin and generation<br />
<h3>Possible user interactions</h3>
<h5>MVP</h5>
<p>First figure shows dispersion by generation for immigrants from all available countries to the Netherlands with a select menu for which country
<h5>Optional</h5>
<p>

<h1>Prerequisites</h1>
<h3>Data Sources</h3>
<p>Eurostat, conversion from excel to json<br />
https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Migration_and_migrant_population_statistics&oldid=348832#Migration_flows:_Immigration_to_the_EU_from_non-member_countries_was_2.4_million_in_2017
<p>CBS, conversion from csv to json<br />
https://opendata.cbs.nl/statline/#/CBS/nl/dataset/37325/table?ts=1557777790739

<h3>External components</h3>
<p>d3-tip<br />topojson

<h3>Similar</h3>
<p>Similar programs use d3 for bar/graph representation with d3-tip for tooltip addition. Interacive european map is achieved with use of topojson

<h3>Working with topojson</h3>
Finding reliable data from each country in Europe for visualisation
