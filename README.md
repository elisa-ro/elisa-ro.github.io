Air Quality in Mexico: 
<a href="AirQualityMexicoCity"></a>

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
