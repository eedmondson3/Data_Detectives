# Data_Detectives
<b>Data Analysis Project One</b></br>
By: Logan Barnes, Edwin Edmondson, Sabrina Recendez and Yeu-Jen Lee</br>
<i>Submitted May 18th, 2023</i></br>
<br>
<b>Topic:</b></br>
Electric Vehicle Ownership in the state of Washington</br>
<br>
<b>Points of interest:</b>
<ul>
  <li>What counties in Washington were most likely to have electric vehicles?</li>
  <li>Are electric car owners in Washington more likely to own a pure electric vehicle or a hybrid electric vehicle?</li>
  <li>Which brand and model of electric vehicle have the highest ownership in Washington?</li>
  <li>What is the electric range of these make and models?</li>
  <li>What is the income level of each county in Washington?</li>
  <li>How does the level of income in each county affect their electric vehicle ownership?</li>
</ul>
<br>
<b>Data Sources:</b>
<ul>
  <li><a href="https://catalog.data.gov/dataset/electric-vehicle-population-data">Electric Vehicle Population Data in Washington in 2020</a></li>
  <li><a href="https://data.census.gov/table?q=income+2020&g=040XX00US53,53$0500000_050XX00US53005,53007,53009,53011,53015,53021,53025,53027,53029,53033,53035,53041,53045,53053,53057,53061,53063,53067,53073,53077">
    Washington State Household Income by County from US Census</a></li>
</ul>
<br>
<b>Our Findings:</b>
<ul>
  <li>King County is most likely to have electric vehicles.</li>
  <li>Electric car owners in Washington is more likely to own a pure electric vehicle.</li>
  <li>Tesla Model 3 is the most popular brand and model of electric vehicle in Washington.</li>
  <li>The maximum electric range of BEV is 300 miles per charge, versus PHEV at 100 miles per tank of gas.</li>
  <li>King County has the highest median income level in Washington, with the median income of $99,158 per household estimate (far exceeding other counties in the state).</li>
  <li>There is a positively high correlation between electric vehicle ownership and median income in Washington.</li>
</ul>
<br>
<b>Limitations:</b>
<ul>
  <li>Electric Range in our data were reported by the vehicle owners, which may be inaccurate.</li>
  <li>Reporting errors in vehicle electric range can vary up to 36%, having access to manufacturer data would improve the accuracy of our BEV vs PHEV ranges.</li>
  <li>Data only accounts for electric vehicle ownership in 2020, thus we are unable to analyze chronological patterns of electric vehicle ownership.</li>
  <li>The data does not include reason for ownership, not having access to direct consumer data limits our ability to compare brand affinity to likelihood of ownership.</li>
  <li>We did not compare ownership with EV charging stations, there is possibly a correlation between electric vehicle ownership and availability of charging stations.</li>
  <li>We did not breakdown income further than county, which limits our insight into the cause of the income variation and resident spending habits.</li>
</ul>
<br>
<b>Resources Used:</b></br>
<ul>
  <li>Removing brackets in dataframe data:</br>
  https://stackoverflow.com/questions/38147447/how-to-remove-square-bracket-from-pandas-dataframe</li>
  <li>Creating new columns by index:</br>
  https://sparkbyexamples.com/pandas/pandas-create-new-dataframe-by-selecting-specific-columns/</li>
  <li>Plotting multiple bar charts:</br>
  https://www.geeksforgeeks.org/plotting-multiple-bar-charts-using-matplotlib-in-python/#</li>
  <li>Slideshow template:</br>
  https://slidesgo.com/theme/world-ev-electric-vehicles-day</li>
</ul>
