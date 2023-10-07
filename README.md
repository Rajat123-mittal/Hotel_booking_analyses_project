# **Hotel_booking_analysis_project**
Project Name - Hotel Booking Analysis

Contribution - Individual

Presented By - Rajat Mittal

Email id - rajatmittal251@gmail.com

## **About the Project**
This project Relates to hotel reservation and includes a variety of city hotels and resort hotels .There are 32 columns and a total of 119390 rows in the dataset.Data collection,data cleaning and manipulation,and EDA(Experimental Data Analysis) are the three categories into which the workflow for data manipulation is divided .The names of some columns, including hotel,is_canceled,lead_time, arrival_date_year,arrival_date_month,arrival_date_week_number,arrival _date_day_of_month,stays_in_weekend_nights,stays_in_week_nights have been updated as the data collection process has progressed.This is done by coding Head(),Tail(),info(),describe(),columns(),and the other methods used for data collection.As we proceed,we identify the distinct value for each column,create a list in tabular format, and also verify the dataset type for each column.Identify some columns with inaccurate data types and fix them afterward.As we discover duplicate items totaling 87396,which are later discarded from the dataset, duplicate data items must also be removed during the data cleaning phase.

We must first problem data manipulation before visualizing any data from the data source.To Do that,We examined each columns null value. After checking ,drop the column using the 'drop' method .If we find one that has a greater percentage of null values.We are so removed from the 'company' column.When there are only a few null values,we fill those null values with the necessary values using the formula.fill()

To achieve greater understanding and buisness goals,many charts are utilized for data visualization.

## **Problem Statement**
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyse the data to discover important factors that govern the bookings.

## **Required Skills**
- **Data Analysis:** Students should be proficient in using Python and data analysis libraries (such as Pandas, NumPy, and Matplotlib/Seaborn).
- **Statistical Understanding:** A basic understanding of statistical concepts like mean, median, standard deviation, and correlation will be essential.
- **Data Visualization:** Familiarity with creating various types of graphs and visualizations to effectively communicate findings.
- **Critical Thinking:** Ability to formulate meaningful questions about the dataset and develop hypotheses to test.
- **Communication:** Students should be able to explain their findings clearly and concisely in the video presentation.

## **Approach to solving a problem**
First I read and understood the problem carefully. When I understood the problem completely, I started writing its code and then visualize the data using some python libraries like Pandas,numpy and seaborn.

## **Conclusion**
1.City Hotel generates greater income and profit and appears to be popular among travellers.

2.Compared to the other months,the majority of reservation are made in july and August.

3.Travellers favour accommodation Type A over all the other accomodation types.

4.Potugal and the United Kingdom make the most reservation.

5.The majority of visitors stays in hotel for 1-4 days.

6.The City Hotel Keeps a larger number of visitors.

7.About one-fourth of all reservations are cancelled .City Hotel is the source of more cancellations.

8.Compared to returning consumers,new guests frequently cancel reservations.

9.Booking cancellations are unaffected by lead time,waiting list length ,or client assignment of a reserved room.

10.Corporate has the most percentage of repeated guests while TA/TO has the least wheras in the case of cancelled bookings TA/TO has the most percentage while Corporate has the least.

11.The lenth of the stay decreases as ADR increases probably to reduce the cost.
