# Hotel-Booking-Analysis

 This analysis aims to understand the factors that influences hotel booking cancellations.This can lead to a number 
 of issues like decreased revenue, underutilized room,overbooking can lead to operational stress for staff etc.
 Therefore, the top priority for both hotels is to reduce their cancellation rates, which will enhance their efficiency in 
 generating revenue. It focuses on the analysis of hotel booking cancellations and other factors that do not 
 directly impact their business and annual revenue generation.


#Description of dataset
This data set contains booking information for a city hotel and a resort hotel, and includes information such as
when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available
parking spaces etc.
The dataset contains a total of 119390 rows and 32 columns.
The columns in the dataset are as follows:
- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record.
- meal: Type of meal chosen
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.(ADR is based on the average price of a hotel room sold on a given day)
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed
- reservation_status_date: Date of making reservation status.


**Objective**
->To get information about the best time of year to book a hotel room.
->The optimal length of stay in order to get the best daily rate.
->To predict whether or not a hotel was likely to receive a
  disproportionately high number of special requests.

**Business Problem**
-> To minimize high cancellation rates and maximize revenue.
