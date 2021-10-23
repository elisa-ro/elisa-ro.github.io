Due to many factors, Mexico City has been known to have bad air quality. This consists of a variety of patterns but I wanted to understand if this perception is accurate and if there are any annual patterns or seasonal patterns that can be outlined.

From Mexico City's Air Quality Database () one can see how the levels in Mexico City have been decreasig over the years, but they're still higher than the recommended WHO's daily limit of PM10:

<div id="observablehq-overallPlot-54eb5978"></div>
<p>Credit: <a href="https://observablehq.com/@elisa-ro/air-quality-monitoring">Air Quality Monitoring by elisa-ro</a></p>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/@elisa-ro/air-quality-monitoring.js?v=3";
new Runtime().module(define, name => {
  if (name === "overallPlot") return new Inspector(document.querySelector("#observablehq-overallPlot-54eb5978"));
});
</script>

A perhaps better way of visualising the dates and the over 20 stations that are measuring the air quality is to see which days in which stations go above the recommended limit by the WHO of 45 PPM daily:

<div id="observablehq-overlimit-2f5853da"></div>
<p>Credit: <a href="https://observablehq.com/@elisa-ro/air-quality-monitoring">Air Quality Monitoring by elisa-ro</a></p>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/@elisa-ro/air-quality-monitoring.js?v=3";
new Runtime().module(define, name => {
  if (name === "overlimit") return new Inspector(document.querySelector("#observablehq-overlimit-2f5853da"));
});
</script>


There seems to be many stations that have data that is not accounted for, so using the following facet visualisation we can get a better understanding of this: 

<div id="observablehq-myplot-65810ff9"></div>
<p>Credit: <a href="https://observablehq.com/@elisa-ro/air-quality-monitoring">Air Quality Monitoring by elisa-ro</a></p>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/@elisa-ro/air-quality-monitoring.js?v=3";
new Runtime().module(define, name => {
  if (name === "myplot") return new Inspector(document.querySelector("#observablehq-myplot-65810ff9"));
});

The air quality center "TLA" seems to be the most consistent over the years, and it's also centrally located so there should be interesting trends to figure out. Over the years there seems to be downard trend:

<div id="observablehq-TLAPlot-2f5853da"></div>
<p>Credit: <a href="https://observablehq.com/@elisa-ro/air-quality-monitoring">Air Quality Monitoring by elisa-ro</a></p>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/@elisa-ro/air-quality-monitoring.js?v=3";
new Runtime().module(define, name => {
  if (name === "TLAPlot") return new Inspector(document.querySelector("#observablehq-TLAPlot-2f5853da"));
});
</script>

//But now let's see what the data is like per average month in a year:

<a href="AirQualityMexicoCity">Air Quality in Mexico City</a>
  
  
<head>
Assignment 2  
</head>

I've lived in both Germany and the U.S. now - two countries which have quite strong economies. However, I've had much better healthcare experiences in Mexico and Italy, both of which aren't as strong economically. I wanted to understand and visualise if the strength of an economy (measured below in GDP per capita) had an impact on the health of an individual in that country (measured below in years of life expectancy).

<div id="observablehq-plot-b693ce4c"></div>
<p>Credit: <a href="https://observablehq.com/@elisa-ro/life-expectancy-vs-gdp">Life Expectancy vs GDP by elisa-ro</a></p>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/@elisa-ro/life-expectancy-vs-gdp@22.js?v=3";
new Runtime().module(define, name => {
  if (name === "plot") return new Inspector(document.querySelector("#observablehq-plot-b693ce4c"));
});
</script>

As can be seen above, there is some relationship between the health and wealth of a nation, but there seems to be a flattening of the curve. This might be the longest humans can live for, or this can be explained with other factors that contribute to health each nation has. 
