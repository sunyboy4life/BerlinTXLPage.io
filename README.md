# HeatHub TXL

<link rel="stylesheet" href="<layout.css>" />
<script src="path/to/md-gallery.js"></script>

The HeatHub Dashboard for heat meter data for Berlin TXL enables the partner to gain a transparent overview of energy consumption and capture derived information such as CO2 emissions.

<div id="content">
  <figure>
    <img style="float: center" src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild1.png" width="700" />
    <p>  </p>
    <figcaption><b>FIGURE 1:</b> The illustration depicts the HeatHub TXL Dashboard, an interactive platform for analyzing heat consumption on the premises of the former Berlin-Tegel Airport (TXL).</figcaption>
  </figure>
</div>

<p></p>
The **HeatHub** Dashboard features an interactive map with 3D visualization for a total of 17 buildings on the Berlin TXL site equipped with heat meters. The map allows for detailed monitoring of heat consumption values at the building level. Mini-charts provide precise information, while large visualizations offer a quick and comprehensive overview. A pie chart displays the average energy consumption across all buildings. This intuitive platform provides both detailed insights and a comprehensive overview of heat consumption on the Berlin TXL site.

### Our Goals:
The "HeatHub TXL" project aims for precise data capture and analysis of energy consumption and CO2 emissions at Berlin Airport TXL. By generating ESG reports, it aims to facilitate transparent communication of sustainability standards and targeted measures for controlling energy consumption. The dashboard serves not only for internal process optimization but also for external communication in the InfoCenter for the public. The overarching goal is to create comprehensive transparency and actively contribute to comprehensive ESG goals (Environmental, Social, and Governance).

### What are heat meters?
Heat meters (HM) are devices that measure energy consumption for heating and cooling in buildings. In the context of HeatHub TXL for the former Berlin-Tegel Airport (TXL), data from these meters are captured and analyzed. The collected information provides insights into heat consumption in various buildings on the premises. The data not only cover basic energy consumption patterns but also consider factors such as the energy efficiency class of buildings, weather conditions, number of employees, and building size. Through this holistic analysis, HeatHub TXL provides a transparent overview of energy consumption on the airport grounds and contributes to promoting sustainable decisions and measures for energy optimization.

### Existing Data
~~hier muss der Text noch ausformuliert und dann ergänzt werden~~

### Workshop/Ideation
<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild2.png" height="700" />
  <figcaption> <b>FIGURE 2:</b> The illustration provides an overview of the workshop progression, showcasing the evolution of visualization from simple to complex prototypes.</figcaption>
</figure>

<div>
    <figure>
        <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild-2.0.png" width="70" />
    </figure>
    <figure>
        <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild-2.1.png" width="70" />
    </figure>
    <figure>
        <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild-2.2.png" width="70" />
    </figure>
    <figure>
        <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild-2.3.png" width="70" />
    </figure>
</div>

~~Bilder als Galerie~~

### Description of Visualizations:
At the outset, the application presents the user with a clear choropleth map of the former Berlin-Tegel Airport (TXL). This map is divided into four main areas, with each area representing a specific zone or segment of the premises.

The subdivision allows users to examine the different parts of the airport more closely. In this view, each of the four areas is color-coded to indicate the current energy consumption. For instance, an area is depicted in green if it has low energy consumption and in red if the consumption is high. This creates a sort of heatmap within the visualization.

<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild3.png" width="70" />
  <figcaption><b>FIGURE 3:</b> The illustration depicts the user interaction process, wherein a user selects a specific area on the <b>HeatHub</b> map.</figcaption>      
</figure>

When the user selects a specific area or zooms into a particular zone, there is a further subdivision of the areas, revealing the buildings. Again, the buildings are color-coded to provide a quick overview of energy consumption.

At a more detailed zoom level, the user can then access very specific information about a particular building.

<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild4.png" width="70" />
  <figcaption><b>FIGURE 4:</b> The illustration illustrates the next step in the interaction process after the user has selected a specific building on the HeatHub map.</figcaption>      
</figure>
<p></p>
After selecting a specific building on the **HeatHub** map, charts are presented here depicting the energy consumption and outside temperature for the chosen building over a selectable period. The visualization demonstrates how the user gains detailed insights into consumption data to analyze trends and patterns.

The data is not only displayed in the choropleth map but additional charts are also available, focusing on the factors defined in the original question ("What factors influence heat meter data?").

### Possible Data Visualizations including Influencing Factors:

**Bar Chart with Energy Consumption and Building Size:**
As the mouse hovers over an area on the map, the bar chart highlights values for energy consumption and the size of buildings in that area. This allows users to establish a direct connection between energy consumption and the size of buildings in that specific zone.

**Line Chart with Energy Consumption and Temperature Over Time:**
The second chart is a line chart representing energy consumption over time in relation to temperature. Users can identify trends in energy consumption correlating with temperature fluctuations. This chart provides insights into the relationship between weather conditions and energy consumption.

Overall, this visualization offers an interactive way to analyze energy consumption at the former Berlin-Tegel Airport, taking into account spatial distribution, building size, time, and weather. This facilitates a thorough examination and analysis of data regarding various aspects of energy consumption on the airport grounds.

<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild-5.png" width="70" />   
</figure>
<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild-6.png" width="70" />    
</figure>
<p></p>

### Analysis and Influencing Factors: Design of the HeatHub Dashboard

**Spatial Zooming to Dynamically Aggregate Data:**
The visualization aims to enable spatial zooming, dynamically displaying heat meter data. Users can zoom into the map of the former airport to select specific areas or buildings and view energy consumption.

**What factors influence heat meter data?**

1.Energy Efficiency Class:
The visualization takes into account the energy efficiency class of individual buildings or areas at the former airport. This allows users to analyze energy consumption in relation to energy efficiency and identify optimization potential. For example, the visualization shows how energy-efficient buildings compare to less efficient ones.
<p></p>
2. Weather:
Weather data is a crucial factor influencing energy consumption. The visualization may display real-time weather data, including temperature and other relevant parameters, to help users analyze the connection between weather and energy consumption.
<p></p>
3.Employees:
The number of employees in different buildings or areas of the airport can significantly impact energy consumption. The visualization includes employee count data that can be considered in conjunction with energy consumption, allowing for the determination of energy consumption per capita.
<p></p>

4.Building Size:
The size of buildings at the airport is another crucial factor. The visualization allows users to display the size of buildings or areas and relate energy consumption to building size.

### Complexity Assessment in the HeatHub Dashboard
**Classification of Complexity:**
After examining Dimension D2 in the Urban Data Visualization (UDV) Card Deck, we evaluated our HeatHub Dashboard in terms of task complexity. The spectrum ranges from "simple" to "complex."
<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild7.png" width="70" />    
  <figcaption><b>FIGURE 7: </b>The illustration clarifies the position of the HeatHub Dashboard on the complexity scale. With a focus on experienced users who regularly interact with the data, the dashboard leans more towards the complex end of the scale.</figcaption>
</figure>
<p></p>

In classifying our initial interface, we particularly considered the user group. Since data access is restricted to authorized users with credentials, and these users regularly interact with the interface, we opted for the classification of "complex."
<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild8.png" width="70" />    
  <figcaption><b>FIGURE 8:</b> Dimension D2 in Urban Data Visualization (UDV)</figcaption>
</figure>
<p></p>

**User Orientation:**
The complexity is tailored to experienced users familiar with the data structure and analysis capabilities. The HeatHub Dashboard offers advanced features for detailed data analysis, utilized by staff to gain precise insights into energy consumption and relevant factors. Opting for higher complexity reflects the requirements and expertise of the target audience.

**Training and Efficiency:**
Due to the increased complexity, training may be necessary for new users to understand the full range of features. However, for experienced users, the more complex interface provides an efficient and powerful platform for optimizing energy consumption and achieving sustainability goals.

**Dynamic Adaptation:**
The flexibility of the complex interface allows dynamic adaptation to different analysis needs, ensuring that experienced users can effectively interact with heat meter data.

This classification contributes to maximizing user-friendliness for the target audience while providing comprehensive analysis capabilities.

<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild9.png" width="70" />    
  <figcaption><b>FIGURE 9:</b> The illustration depicts the developmental trajectory of the initial concept for the HeatHub Dashboard. From the original conception, which included spatial zoom and a dynamic map, to the paper prototype. The visualization highlights the iterative process where targeted visualizations can be accessed through simple clicks on the map.</figcaption>
</figure>
<p></p>

### Considerations on Technology Standards

#### Interactive Functionalities and Depth of Analysis

Interactive Zoom and Analysis Functions:
The visualization adheres to standards that facilitate effective interaction through zooming into the map and selecting specific areas. This supports differentiated analysis at various detail levels, allowing users to immerse themselves in the data and gain precise insights.

Introductory Explanation for Different Users:
To accommodate the diversity of user experience levels, the visualization provides a brief introductory explanation. This assists beginners in easy navigation, while experts can quickly dive into the analysis.

Training for Experienced Users:
As the visualization is not designed for various user groups and accesses non-public data, it requires users to be trained and experienced. This ensures competent utilization of advanced features.

Optimization for Web and Touchscreen Surfaces:
The visualization is specifically optimized for web and touchscreen surfaces to maximize zoom interaction possibilities in these environments. However, mobile solutions are not considered.

#### Selection of Visualization and Data

Consideration of Different Needs:
The visualization was developed to address the diverse needs and interests of various urban stakeholders. This includes users, TP employees, visitors to the InfoCenter, investors, and tenants of the InfoCenter.

User-Friendly Customization Options:
Through user-friendly customization options, the visualization provides flexible use to meet the individual needs of different users.

Exclusively Using Real Data:
The visualization is based solely on real data to ensure the authenticity and relevance of the presented information.

Standardized Shapes and Symbols:
The use of standardized shapes and symbols facilitates data interpretation for a broad audience without requiring extensive expertise. For example, color codings are used to highlight specific information.

Consideration of Nuanced Information:
The visualization captures nuanced and meaningful information, especially in deeper analysis at the building level. It integrates relevant metrics at this detailed level, enabling subtle but significant insights that might be overlooked at higher levels. This promotes a more thorough analysis and informed decision-making regarding urban development.

### Summary of the Initial Idea and Challenges:
The visualization of the former Berlin-Tegel Airport (TXL) provides a detailed insight into energy consumption on the premises. The starting point is a choropleth map dividing the area into four main zones, each representing a specific zone with color coding indicating the current energy consumption, creating a heatmap effect. By selecting or zooming in, buildings become visible, also color-coded to illustrate energy consumption. In addition, charts provide information on factors such as energy efficiency class, weather, employee count, and building size in relation to energy consumption.

The visualization allows for a comprehensive representation of energy consumption at the airport, considering various influencing factors. The zoom function enables users to dive into the data and analyze it at different detail levels, particularly beneficial for experienced and trained users. However, there are some challenges to address: the classified "complex" visualization may limit usability for beginners and requires training. Additionally, security measures should be implemented as the data is not publicly accessible. Despite these challenges, the visualization offers a valuable opportunity to analyze energy consumption at Berlin-Tegel Airport and consider various influencing factors. Adjusting complexity and access restrictions is crucial to maximize user-friendliness and overall utility.

### Why a Map Dashboard is the Ideal Choice!

Spatial Context:
A dashboard with a map is particularly effective in emphasizing spatial context. In our case, analyzing heat meter data on the former Berlin-Tegel Airport (TXL) premises, it is crucial to depict energy consumption in relation to the spatial distribution of buildings. A map visualization allows users to specifically view areas or buildings and understand energy consumption on a geographical level.

Interactive Exploration:
A dashboard provides the opportunity for interactive exploration of data. Users can zoom into the map, select specific areas, and retrieve detailed information. This interactivity allows for flexible and individualized analysis, giving users control over their exploration.

Comprehensive Overview:
With a map dashboard, various data and influencing factors can be simultaneously displayed. This provides a comprehensive overview of energy consumption on the airport premises. Instead of a linear narrative structure, users have the opportunity to understand the relationship between different factors and delve deeper into the analysis if they wish.

Real-time Updates:
Using a dashboard makes it easier to provide real-time updates or regular data refreshes. This is especially important when continuously new information about energy consumption on the airport premises becomes available.

Flexibility for Different Users:
A dashboard offers flexibility for various user profiles. Both beginners and experienced users can utilize the visualization by navigating to different detail levels. This contributes to making the application accessible to a broader audience.

Overall, a map dashboard enables a dynamic and flexible presentation of data, particularly suitable for complex spatial contexts and comprehensive analyses. It provides a platform that is both informative and interactive, allowing users to better understand energy consumption on the airport premises and promote sustainable decision-making.

### Prototype of the HeatHub Dashboard with Figma:
**What is Figma?**
Figma is a collaborative online design tool that allows teams to work together on the creation of graphics, user interfaces, and prototypes. It provides features for design, real-time editing, commenting, and prototyping. This makes it particularly effective for designing digital products and collaborating in distributed teams. For us, Figma has proven to be an indispensable tool for design exploration, and in this context, we now look at the individual process stages in which we have used it. The focus is on the reasons for changes, why certain aspects remained unchanged, and the advantages and disadvantages of specific features.

Analyzing the functions of Figma reveals clear pros and cons. The collaboration capabilities and real-time editing enhance efficiency and the exchange of ideas but may also lead to potential conflicts or uncertainties. By examining the reasons for changes, the persistence of certain aspects, and analyzing the pros and cons, we were able to create a balanced and effective design process that meets the requirements and expectations. Our product went through various design processes. Some elements remained unchanged throughout the process as they proved to be particularly effective or aesthetically pleasing, while other elements were carefully reconsidered, either discarded or adjusted.

**The first Ideas:**
The initial considerations regarding the representation of features led to two main options. The uncertainty about which option was the best determined the beginning of the design process. Now, let's delve into the details of these two options:

1. Navbar with Map View as the Homepage

<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild10.png" width="700" />    
  <figcaption><b>FIGURE 10:</b> The first design for the homepage</figcaption>
</figure>
<p></p>

The idea was to create a homepage with a prominent interactive map view. Various elements could be accessed through a navigation bar (Navbar). Alternatively, upon selecting a building, the relevant information could appear on the page below the map. The option of a login was considered but dismissed at this point, as it was not intended to display individual personal data.

<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild11.png" width="700" />    
  <figcaption><b>FIGURE 11:</b> Dashboard design</figcaption>
</figure>
<p></p>

The second option was a dashboard where all elements are directly presented, with the map still being prominent. All elements should interact with each other, particularly in terms of their connections. The dashboard allowed displaying all components with just one click. The only adjustable parameter was the timeframe. Interaction between elements was facilitated through selecting the timeframe and the building.

In addition to these considerations, the decision was made to use "Small Multiples" to represent the energy consumption of heat meters (WMZ) individually or collectively. Small Multiples are a visualization technique where multiple small graphics of the same chart are arranged in a matrix, allowing for quick and effective comparisons.

In the top right of the dashboard, the power of each WMZ in the building is depicted. This decision was made to enable a detailed yet comprehensive visualization of energy consumption.

<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild12.png" width="700" />    
  <figcaption><b>FIGURE 12:</b> This illustration showcases the map view of HeatHub TXL, with interactive clickable buildings.</figcaption>
</figure>
<p></p>


With the map, users have the option to click on specific buildings to access detailed information about that particular building and the heat meters located within it, along with their respective values. The map facilitates targeted selection and analysis.
<p></p>

**Commitment to one of the two options**

The decision to commit to a dashboard view was made because this option offered several advantages:

1. Comprehensive representation:
All elements were presented on a single screen, providing a holistic overview. This simplified the grasp and interpretation of information, eliminating the need to switch between different pages.
<p></p>
2. Reduction of representations:
Compared to multiple pages with different representations, the dashboard efficiently combined all relevant information on one surface. This promoted a clear and compact presentation without information overload.
<p></p>
3. Connection of elements:
Opting for the dashboard allowed for the connection of various elements. These connections reflected the interactions and linkages between the elements, enabling a more precise representation of relationships.
<p></p>
Therefore, committing to a dashboard view was a strategic decision to create a comprehensive, well-connected, and easily understandable visualization. This not only enhanced user-friendliness but also facilitated a more effective analysis of interactions and connections between different elements of the system.

<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild13.png" width="700" />    
  <figcaption><b>FIGURE 13:</b> Changed representation of the Heat Meters</figcaption>
</figure>
<p></p>

**Change in the representation of the consumed energy of the Heat Meters**
For the following reasons, we opted for a Pie Chart to represent the consumed energy of the Heat Meters.

1. Flexibility in the number of Heat Meters (HM):
A Pie Chart provides the flexibility to adjust the number of displayed HMs. With a high number of HMs, it can be challenging to accommodate them in other visualizations. The Pie Chart allows for a clear and compact presentation of this information, regardless of the quantity of displayed HMs.
<p></p>
2. Aesthetic and clear presentation:
The round shape of the Pie Chart offers an aesthetic representation while maintaining a clear and easily understandable presentation of the data. This visual component can enhance the user experience and facilitate data interpretation.
<p></p>
The decision for a Pie Chart in the top right corner added an additional dimension to the overall presentation, allowing for a flexible, clear presentation of relevant information about the Power of each HM.
<p></p>

**Addition of an information field and enlargement of the map**
<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild14.png" width="700" />    
  <figcaption><b>FIGURE 14:</b> Adding information-field and navigation-bar</figcaption>
</figure>
<p></p>

In the early phase of the design process, the exact representation of information was not yet finalized. However, from the outset, a goal was set to provide users with the ability to access detailed information about the displayed values. This could be achieved by placing the Pie Chart in the top right corner, contributing to the enhancement of the main visualization. For this reason, the idea of an adaptive information field was considered.
<p></p>
In addition, the decision was made to enlarge the map itself to ensure it takes a prominent place. To create space and improve user-friendliness, the date picker was minimized. Simultaneously, a navbar was added at the top, including the date picker, the time range picker, and an info button providing general information about the Heat Meters (HMs).
<p></p>
The interaction between the date picker and the time range picker was strategically designed. The time range picker determines the period for which the data should be displayed (Day, 1 Week, 2 Weeks, 1 Month), while the date picker sets the starting date for retrospective analysis. For example, if two weeks are selected with a start date of February 14th, the data displayed will cover the period from February 1st to February 14th.
<p></p>
This integration allowed precise control over the displayed timeframe and ensured effective and user-friendly interaction with the information on the map. The info button complemented this functionality by providing general information about the HMs, offering users comprehensive context.
<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild15.png" width="100" />    
  <figcaption><b>FIGURE 15:</b> Calendar view for selecting a timeframe.</figcaption>
</figure>
<p></p>

**New Color Scheme**
A unified color scheme has been introduced to make the entire dashboard more cohesive and aesthetically pleasing. This color scheme is applied to various elements such as backgrounds, buttons, text, and charts. The harmony in color design contributes to a pleasant user experience and enhances visual consistency.
Additionally, it now also depicts which buildings have been selected.
<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild16.png" width="700" />    
  <figcaption><b>FIGURE 16:</b> FIGURE 16 This figure shows the new color scheme.</figcaption>
</figure>
<p></p>

### Endprodukt
<figure>
  <img src="https://github.com/sunyboy4life/BerlinTXLPage.io/blob/main/assets/user/Bild17.png" width="700" />    
  <figcaption><b>FIGURE 17:</b> In this illustration, the final end product is presented.</figcaption>
</figure>
<p></p>

~~hier muss noch der Text geschrieben und ergänzt werde~~

### Implementation
~~hier muss noch der Text geschrieben und ergänzt werde~~

