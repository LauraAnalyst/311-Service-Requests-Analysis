# 311-Service-Requests-Analysis
As a data analyst and newcomer to the vibrant city of Calgary, understanding and accessing the various services and information provided by the City is crucial. The 311 Service Requests system, offered by The City of Calgary’s Citizen Services division, serves as a comprehensive platform for residents, business owners, and visitors to connect with the city government and access non-emergency services. Through this system, individuals can submit requests, seek information, and track the progress of their inquiries or service needs. This data-driven exploration of Calgary’s 311 Service Requests aims to empower newcomers like myself and contribute to the continuous enhancement of city services.

![picture](picture.jpg)

This data story aims to uncover hidden narratives within the 311 Service Requests dataset and present a comprehensive understanding of the urban landscape. I will endeavor to address the following five key inquiries:

- What are the most common types of service requests received through the 311 system?
- Which city departments are responsible for resolving the majority of service requests?
- How does the volume of service requests vary over time? Are there any noticeable patterns or trends?
- Are there any geographical patterns or disparities in the distribution of service requests across different areas of the city?
- How does the response time vary overall and for different types of service requests?

## 311 Service Requests Dataset
The dataset includes essential details such as the request date, closure date, service channel, service name, and responsible department for each request. Additionally, it provides valuable information about the community, as well as the longitude and latitude coordinates associated with the location of the service request.

I analyzed a dataset consisting of 2,736,776 service requests recorded between 2018 and 2023. To ensure data quality, I performed basic data cleaning procedures to standardize the dataset. Specifically, I converted the date fields to the appropriate data type and extracted the year, month, and day of the week from the request dates. This allowed for a more comprehensive analysis of time-related insights in the data. I also extracted categories and subcategories from the ‘service name’ and ‘agency responsible’ fields. This extraction allowed for enhanced filtering options based on both main and subcategories.

It was noted that approximately 158,000 requests lacked information regarding their associated location. However, this information was intentionally left as is, as some services may not be connected to specific locations or may have been completed online. A small number of entries were found to be missing the ‘service name’ and ‘agency responsible’ fields. These rows were removed from the analysis since they lacked essential information for further examination.

## What are the most common types of service requests received through the 311 system?
Exploring the realm of service requests received through the 311 system, we discover a fascinating revelation: the most common types that stand out. By analyzing the frequency distribution of categories, we uncover the pulse of urban life. Below, you’ll find a bar chart depicting the top 10 categories of service requests.

<iframe src="service_categories.html" width="800" height="600"></iframe>
