---
layout: page
title: Team02 AI-based Water Resource Prediction and Management
description: When building a website it's helpful to see what the focus of your site is. This page is an example of how to show a website's focus.
sitemap:
    priority: 0.7
    lastmod: 2020-10-25
    changefreq: weekly
---
## Design

<span class="image"><img src="{{ "/images/pic04.jpg" | absolute_url }}" alt="" /></span>

Our page is divided into two major sections. The first part is visualization. We convert some data into charts, hoping to give users a complete picture and enhance their understanding of the data, so as to facilitate future research. The second part is the computation graph. This is a webpage showing the structure of our GNN model, where researchers could explore and optimize the model used for prediction.

## Visualization
The home page of visualization is an overview of all of our information, including four charts, maps, and a live information update bar. This information bar will show the user today's weather, date, wind, and other weather conditions. At the centre of the page is a map of Ningbo, with a circular marker showing reservoir's location. On both sides of the page are two maps, showing the basic situation of the reservoir, the amount of water stored, the pollution situation and the comparison between region.
### Map
<div class="box">
  <p>
  One map is displaying on this page. Each blue marker represents a reservoir. 
When users click one marker, an information box pop out, indicating the name, district of the reservoir and the date. Some blue lines connecting other markers may appear, which means these lakes are connected.
  </p>
</div>
### Customize
<div class="box">
  <p>
  This page is specially customized for users. The user can choose one or more of the five options including map, air temperature and pollution in the form. Only selected graphs would be shown on the next page. 
  </p>
</div>

## Computation graph
### TensorBoard
<div class="box">
  <p>
  In this section, the user interface of the TensorBoard website will be introduced.
TensorBoard is a tool to visualize models in machine learning by using the TensorFlow framework. In our project, we specifically use TensorBoard to visualize the computation graphs of our GNN model. Besides, other experiment metrics such as loss and accuracy is also included in this visualization tool.
  </p>
</div>

<span class="image"><img src="{{ "/images/pic05.jpg" | absolute_url }}" alt="" /></span>

## Implementation
As our project is developed based on an existing system, we decide to implement our website using the same tools as the last team used, along with some updates.
For the team website, we used Jekyll, a static website generator, and GitHub to set up our team website. Basic HTML, CSS and JavaScript will be used in building the visualization website. ECharts library will be implemented to generate visualization graphs such as line chart, pie chart and k-line diagrams. As the dataset of water resources for prediction is given directly by the stakeholder and used in the machine part, no back-end tool will be used.
For the machine learning part, language use will be Python. And for setting up the online server, we will use Tencent Cloud.

## Software development Procedure
We apply the agile development process. The main process is to identify a new requirement, and then discuss whether it is needed and how to implement it. After that, the team leader usually evaluates the difficulty of the task and assigns it to the team members. After the completion, the team leader is responsible for the integration. In addition, we send the screenshot to the teacher for confirmation at the formal meeting every week to ensure that we meet the requirement.
Besides, we applied pair programming. Four people were divided into two groups, and each component was completed by two people. Two people checked each other's code, which dramatically reduced the possibility of errors.

## Future work
We still have some requirements that have not been realized and some contents need to be improved. We think that we can focus on the following aspects in the future:
1. Realize explainable graph neural network
2. Purchase domain name and space so that other users can access web pages through the domain name
3. Develop a mobile version, so that users can access our page through mobile phones or iPad

