
<h3>ANALYSIS ON AIRCRAFT DATA TO DETERMINE THE SAFEST AIRCRAFT FOR COMMERCIAL AND PRIVATE PURPOSES</h3>

<h4>Overview</h4>

This project aims to assess the risks associated with various aircraft in order to help the company decide which aircraft to purchase for both commercial and private enterprises. The focus is on determining which aircraft are the lowest risk for the company to enter this new business venture. The analysis will translate findings into actionable insights for the head of the new aviation division.

<h3>Business Understanding</h3>

Stakeholder(s):

    Head of the new aviation division
    Company leadership (for strategic decision-making)
    Risk management team
    
Key Business Questions:

    1.Which aircraft are the least risky in terms of injuries and accidents?
    2.What factors (e.g., weather conditions, aircraft type, etc.) contribute most to injury severity in aviation accidents?
    3.How can the company mitigate risk when selecting aircraft for purchase?
    
Data Understanding and Analysis:

Data Source:
The data [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.
 
Description of Data: 

The dataset contains the following columns:

    Country: The country where the accident occurred.
    Injury.Severity: Severity of the injuries sustained (e.g., fatal, serious, minor).
    Aircraft.damage: The extent of damage to the aircraft.
    Make: The manufacturer of the aircraft.
    Amateur.Built: Indicates if the aircraft was built by amateurs (yes/no).
    Number.of.Engines: Number of engines the aircraft has.
    Engine.Type: Type of engine used in the aircraft.
    Purpose.of.flight: The purpose for which the aircraft was being used (e.g., commercial, private).
    Total.Fatal.Injuries: Number of fatalities.
    Total.Serious.Injuries: Number of serious injuries.
    Total.Minor.Injuries: Number of minor injuries.
    Total.Uninjured: Number of individuals who were not injured.
    Weather.Condition: Weather conditions at the time of the accident.
    Total_Injuries: This is a weighted average of Fatal, Serious and Minor injuries 
Visualizations:

    Univariate: 
        Conducted Univariate vizualization of all columns with appropriate plots.
    Bivariate:
        Make vs. Engine.Type: This can help understand which engine types are associated with specific manufacturers
        Make vs. Aircraft.damage: Show the relationship between aircraft makes and the damage severity
        Engine.Type vs. Number.of.Engines: Find if any engine type corellates with a specific number of engines
        Engine.Type vs. Injury.Severity
        Make vs. Total.Fatal.Injuries
        Purpose.of.flight vs. Aircraft.damage
        Weather.Condition vs. Injury.Severity
    Multivariate:
        Heatmap of Correlation Matrix This helps us identify relationships between numerical variables, such as Total_Injuries
        Pairplot of Key Variables A pairplot will show pairwise relationships between several numeric variables.

<h4>Conclusions<h4/>
The company should buy Turbo Fan Engine Type.<br>

The company should purchase a Boeing Aircraft<br>

<h4>Link to Tableau Dashboard</h4>
https://public.tableau.com/app/profile/misheck.kibunja/viz/TableauDashboard_17331351787630/Dashboard1?publish=yes








        
        



        
