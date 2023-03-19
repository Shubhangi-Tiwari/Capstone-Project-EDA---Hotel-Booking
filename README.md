# Capstone-Project-EDA-Hotel-Booking

# Introduction
Provided with Hotel Booking dataset, main objective is to do some analysis and find general trends in hotel booking and how other factors effect hotel booking.

# Problem Statement

*Hotel Booking Data Analysis*

Hotel business is a very competitive market, as there are many new competitors it becomes tough for customers to select a hotel for booking as different customer have different requirement while booking hotel. The very first step for business owner towards improvement is analyzing data of our own business to find loopholes and work on various factors to improve booking of hotel.This data can also help customer to find answer of various question wie booking hotels, ike when is the best tme of year to book a hotel? Or the optimal length of stay in order to get the best daily rate? This hotel dataset can help explore those questions!

The provided dataset of hotel booking contains booking information for a city hotel and a resort hotel,includes information such as when the booking was made, length of stay, number of adults,children & babies, and the number of available parking spaces, country, customer types, market segment, distribution channels and many more factors. This data will help to understand which factors effect most of the hotel booking. Analyzing this data based on such factors give clear insights about bookings and help customers to do booking accordingly. We can get various information about booking such as when most hotel bookings were done? From which country most booking were done? Booking based on age group and many more things that will help to draw conclusion what things mst be considered while booking a hotel.

It can help customer to choose and decide when is the best time to book hotel? Which is the most liked meals? Also to check various factor of hotel and make proper decision while booking hotel, so this dataset is useful for both customer point of view and business owner point of view.

# Dataset Information
The provided Dataset is of Hotel Booking which consists detail of Hotel booking based and some other details regarding those hotel bookings. The provided dataset of Htel Booking have in total 119390 rows and 32 columns. This rows and columns have htel booking details such as Whether booked hotel was a Resort hotel or City Hotel, Locatin (Country) from where hotel was booked, Arrival Year, Month, Date of Customer and many more details.

Following are the details of all columns present in dataset:

**hotel**- Whether booked hotel is City Hotel or Resort Hotel.

**is_canceled** - Booking of Hotel was cancelled or not (0= not canceled, 1=cancelled)

**lead_time**-Number of days that elapsed between the entering date of the booking into the PMS and the arrival date.

**arrival_date_year**- Arrival Year

**arrival_date_month**- Arrival Month

**arrival_date_week_number**- Arrival Week

**arrival_date_day_of_month**- Arrival Date

**stays_in_weekend_nights**- Number of Weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

**stays_in_week_nights**- Number of week nights(Monday to Friday) the guest stayed or booked to stay at the hotel

**adults**- Number of adults

**children**- Number of Children

**babies**- Number of babies

**meal**- kind of meal opted for 

**country**- Country code

**market_segment**- Which segment the customer belongs to 

**distribution_channel**- How the customer accessed the stay corporate booking/Direct/TA.TO

**is_repeated_guest**- Guest coming for first time or not 

**previous_cancellations**- Was there a cancellation before

**previous_bookings_not_canceled**- Count of previous bookings

**reserved_room_type**- Type of room reserved

**assigned_room_type**- Type of room assigned

**booking_changes**- Count of changes made to booking

**deposit_type**- Deposit Type

**agent**- Booked through agent

**company**- Booked through company

**days_in_waiting_list**- Number of days in waiting list

**customer_type**- Type of Customer

**adr**- average daily rate

**required_car_parking_spaces**- If car parking is required

**total_of_special_requests**- Number of additional special requirements

**reservation_status**- Status of Reservation

**reservation_status_date**- Date of specific status

# Graphs Used & Analytics

1.Handling Null & Duplicate Values

* Null values in children,agent & company columns were replace by 0.
* Null values in country were replaced by NA.
* All duplicate rows were removed.

2.Converting Datatypes

* Converted column children,agent & agent to int type.
* Converted column reservation_status_date to datetime data type

3.Creating New columns

* Created new column total_stay by joining stay_in_week_night & stay_weekend_night
* Created new column total_guest by adding children, adults and babies column.

While analyzing data, we obtain some important insights like which hotel was booked the most? From which country most of the bookings done? and many more insights. Data visualization, in general makes complex data easy to understand and get significant insights from that entire dataset, so we used visualization which gave lots of insights of dataset, many questions were answered using graphs and visual plots. The graphs and visual plots used in this project are as follows:

Bar plot

Pie chart

Box plot

Pair Plot

Line Chart

Coorelation Heatmap

For this visualization mainly seaborn & matplotlib library were used.






# EDA answered following question about hotel booking




1.From which country most of the bookings were done?

2.Which hotel have the most of the repeat guest?

3.Which hotel bookings has higher cancellation rate?

4.How many types of customer are there while booking for hotel?

5.How many options are there while booking a hotel? Which one is booked the most?

6.From which market segment most of the booking was done?

7.Which distribution channel is most used by customer while booking hotel?

8.Which is the most ordered/served/liked meal in hotels?

9.Which deposit type was most preferred by the customers for hotel booking?

10.Through which agent most of the bookings were done?

11.In which year most of the customers arrived in both hotel?

12.In which of the month most of the custromers arrived? Which is the least favourable month for customers to visit hotel?

13.In which hotel most the customers arrived?

14.Which age group is most likely to book hotel?

15.How long people preferred to stay in hotels?

16.Which room is most preferred by customers while making bookings?

# Conclusion

The conclusion For this Hotel Booking Dataset are as follows:

1.City Hotel are preferred more as compare to Resort Hotels, about 66.4% of bookig is of City Hotel & only 33.6% is of Resort Hotel

2.City Hotel are more prone for cancellation of bookings as compare to resort hotel.

3.Number of Repeated guests are less in both hotels but number of repeat guest is slightly higher in Resort hotel as compare to City Hotel.

4.Transient, Group,Transient-party & Contract ae the four types of customer making booking for hotels.

5.TA/TO is the most preferred distribution channel wile making bookings.

6.The most preferred meal is BB, followed by HB,SC. The other two least referred meals are FB & Undefined.

7.For both Resort and City hotels, No Deposit type is most preferred by ustomer for making bookings.

8.Agent 9 made the most bookings

9.Most of the bookings for both hotels were done in year 2016.

10.July-August made the most of the booking throughout the year. 

11.Most of the bookings were done by couple(i.e. maximum of two adults)


