<div align="center">
    <div style="float: center;">
        <img src="heatmap_image.png" alt="Heatmap Image" width="500"/>
    </div>
</div>
<div align="center"><h2>Flight Passenger Preferences and Booking Patterns: A Basis for Predictive Modeling at Horizon Airlines</h2></div>

# PHASE 5 CAPSTONE PROJECT
## Predictive Modeling for Flight Passenger Preferences and   Booking Patterns in Horizon Airlines
### Group Members
Kamande Karigi

Lewis Otsieka

Marion Jelimo

Titus Kilonzo Mutuku

Yusra Noor

## OVERVIEW

Horizon Airlines, a prominent player in the aviation industry, stands as a cornerstone of reliable air travel services. As a leading airline company, Horizon Airlines is dedicated to providing safe, efficient, and seamless travel experiences for passengers across Kenya. With a fleet of modern aircraft and a commitment to operational excellence, Horizon Airlines has positioned itself as a trailblazer in the aviation sector. Recognizing the challenges and complexities inherent in managing a vast network of flights, passenger preferences, and operational logistics, Horizon Airlines has enlisted our expertise. Our team has been entrusted with the task of implementing advanced analytics to derive valuable insights from the company's extensive datasets. By harnessing the power of data-driven decision-making, our goal is to assist Horizon Airlines in optimizing its operations, enhancing customer experiences, and maintaining a competitive edge in the dynamic aviation landscape.


## BUSINESS UNDERSTANDING

In response to the challenges posed by the post-COVID-19 landscape in the aviation industry, Horizon Airlines aims to leverage advanced analytics to gain profound insights from its extensive datasets. The primary goal is to enhance operational efficiency, elevate customer experiences, and maintain a competitive edge in the dynamic aviation sector. The focus is on understanding the nuanced dynamics of customer behavior in the aftermath of the pandemic, with an emphasis on factors like travel preferences, safety concerns, and additional service demands. By harnessing the power of data-driven decision-making, the project seeks to guide Horizon Airlines in tailoring its services effectively to meet the evolving needs of passengers, ensuring safety measures, accommodating extra baggage, preferred seating, in-flight meals, and other personalized preferences. This strategic approach will not only facilitate a robust recovery for the airline but also position it as a trailblazer in adapting to the changing landscape of post-pandemic travel.


## DATA UNDERSTANDING

Our dataset was sourced from 'www.forage.com'. The dataset consists of 50,000 entries and comprises 15 columns. It includes both numerical and categorical features, providing insights into flight passenger preferences and booking patterns. Below is an overview of the dataset columns:


num_passengers - Represents the number of passengers for each booking.


sales_channel - Denotes the specific channel through which flight bookings were made.


trip_type - Indicates the type of trip, distinguishing between one-way and round-trip bookings.


purchase_lead - Represents the lead time (in days) between considering and making a flight purchase.


length_of_stay - Captures the duration of the stay associated with each flight booking.


flight_hour - Specifies the hour of the day at which the flight is scheduled.


flight_day - Records the date of the flight booking.


route - Describes the specific route of the flight.


booking_origin - Indicates the origin of the booking, providing insight into the geographic source.


wants_extra_baggage - Binary variable indicating whether passengers express a desire for additional baggage.


wants_preferred_seat - Binary variable indicating whether passengers express a preference for specific seating.


wants_in_flight_meals - Binary variable indicating whether passengers express a desire for in-flight meals.


flight_duration - Captures the total duration of the flight for each booking.


booking_complete - Binary variable indicating whether the flight booking process is completed.


## MODELING AND EVALUATION

The predictive models, comprising Logistic Regression and Random Forests, were employed to analyze passenger booking behavior for Horizon Airlines. The Logistic Regression model exhibited an overall accuracy of 85.27%, with a precision of 0.52, recall of 0.06, and an F1-score of 0.11 for predicting successful bookings. The initial Random Forest Model achieved an accuracy of 81.79%, featuring a precision of 0.36, recall of 0.29, and an F1-score of 0.32 for successful bookings. Notably, the Random Forest Model, enhanced through feature selection, demonstrated improved performance with an accuracy of 86%, a precision of 0.55, recall of 0.14, and an F1-score of 0.22 for successful bookings. These models provide valuable insights into passenger preferences, aiding Horizon Airlines in optimizing its booking processes and tailoring services to meet evolving customer expectations, thus positioning the airline for success in the post-pandemic aviation landscape.

## Conclusion 
In pursuit of our objectives to enhance Horizon Airlines' services and understand customer behavior and preferences we  successfully provided Horizon Airlines with valuable insights into passenger behaviors and operational trends.
Through logistic regression, random forest, and ensemble modeling, we've gained insights into predicting booking completion and uncovering travel preferences. These insights reveal critical drivers influencing both booking completion and passenger preferences. With a better understanding of customer needs and behaviors, Horizon Airlines can tailor services and strategies accordingly.
## Recommendations
* Enhance Ancillary Services - Focus on promoting services such as extra baggage allowances, which were preferred by a significant portion of passengers.
* Marketing Strategies - Tailor marketing strategies to promote round-trip bookings, which were the most preferred booking type. 
* Customer Experience Enhancement - Focus on improving the booking experience for passengers by streamlining the booking process and providing personalized recommendations based on historical booking patterns. 
## Next steps
Horizon Airlines should consider the following next steps:

* Tailor services and promotions according to passenger preferences.
* Collect ongoing customer feedback for continuous improvement.
* Monitor key performance indicators to gauge effectiveness.
* Implement necessary adjustments to enhance customer experience and drive business growth.






