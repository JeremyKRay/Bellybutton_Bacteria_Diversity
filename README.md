# Bellybutton_Diversity_Challenge
Module 12 Challenge
## Overview
The purpose of this challenge was to explore the importance of data visualization to data analysists in communicating findings and conclusions. Although the topic is a bit strange, the outcome is a clear demonstration of the power these tools hold for data visualization. JavaScript is used to create attractive, accessible and interactive data visualizations. The JavaScript data visualization library Plotly.js is used to provide the interactivity needed to increase the user's comprehension of the data, drawing the same conclusions as the data analyst. To demonstrate this, a website was created that offers interactive analysis of a dataset containing information on the biodiversity of bacteria strains found in the human belly button. The hypothesis is that there might be a bacterial strain found in the belly button that can synthesize the proteins necessary to make improbable beef grown in a lab taste like real beef.  

## Technology Used

![download](https://user-images.githubusercontent.com/98500639/185666138-c4f0147e-ff29-45dd-aa57-bab9680d6f87.jpg)
![download](https://user-images.githubusercontent.com/98500639/185666192-e8458a1f-6a7f-4136-bb25-793d9735f432.jpg)
![download](https://user-images.githubusercontent.com/98500639/185666212-cb455389-a605-4a3f-b05b-44e676aa3489.png)

## Tasks

5 main tasks were required to complete the website.

### 1) Create the drop down menu so the user can choose samples based on sample id. 
#### Approach
The buildCharts() function containing the sample argument represents the sample that gets selected from the dropdown. The samples.json file is retrieved using the  d3.json.then() method and a variable is created that contains all the samples. The user chooses a sample from the dropdown list and Demographic Information, as well as the charts discussed further, are updated. The input box is shown below.

  ![Sample Input Box](https://github.com/JeremyKRay/Bellybutton_Diversity_Challenge/blob/59b581214c9d9c87b7bb76547b94d0be445220db/Sample%20Input%20Box.png)
  
### 2) Create the barchart
#### Approach
Plotly is used to create a barchart displaying The Top 10 Bacteria Cultures found. The chart is shown below.

![Bar Chart](https://github.com/JeremyKRay/Bellybutton_Diversity_Challenge/blob/59b581214c9d9c87b7bb76547b94d0be445220db/Bar%20Chart.png)
  
### 3) Create the bubble Chart
#### Approach
Plotly is used to create a bubble chart displaying the number of bacteria cultures found per sample. The chart is shown below.

![Bubble Chart](https://github.com/JeremyKRay/Bellybutton_Diversity_Challenge/blob/59b581214c9d9c87b7bb76547b94d0be445220db/Bubble%20Chart.png)
  
### 4) Create the Gauge Chart
#### Approach
Plotly is used to create a gauge chart displaying the belly button washing frequency of the sample subject. The chart is shown below.

![Gauge Chart](https://github.com/JeremyKRay/Bellybutton_Diversity_Challenge/blob/59b581214c9d9c87b7bb76547b94d0be445220db/Gauge%20Chart.png)
  
### 5) Customize the Dashboard
#### Approach
HTML and Bootstrap are used to customize the webage. This includes adding an image to the jumbotron, color changes, additional information as the user hovers over various charts, etc. Please follow the link below under the Results section to see the final webpage.

## Results
The resulting webpage allows the user to select a test subject id number from a dropdown list and various data visualizations update based on the selected test subject. Demographic information including ethnicity, gender, location, etc are updated. In addition, a bar chart showing the Top 10 cultures found in that subject's bellybutton, a gauge chart showing the frequency of bellybutton washings, and a bubble chart showing the number of cultures per sample are all updated. Additional information about the bacteria cultures can also be displayed as the user hovers over the bar chart and bubble chart. 
Please click the following link to access the interactive bellybutton biodiversity webpage. 

[Bellybutton Bacteria Diversity](https://jeremykray.github.io/Bellybutton_Bacteria_Diversity/)
