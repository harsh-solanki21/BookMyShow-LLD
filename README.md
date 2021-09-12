# 🌈 BookMyShow Low-Level-Design(LLD)
- This Low-Level-Design is made considering particular Requirements and Assumptions that are listed below.

# Requirements : 
- App will be listing current movies and the shows.
- App allows user to search for movies.
- App will be listing different shows for a movie.
- App allows registered user to book ticket for a show.
- App allows theaters to add/edit a show.

# Assumptions : 
- Every theater has single screen.
- Every theater has some capacity (no. of seats).
- Registered users can book tickets, but Guest users are allowed to search movies.
- Registered users will have the history of their bookings.
- Movies can be in two languages: Hindi and English
- Movies can have any of the four genres: Action, Romance, Comedy and Horror.
- We are not considering Payment module for now.


# Use-Case Diagram
![Use Case Diagram](https://user-images.githubusercontent.com/52111635/132999378-6f126c93-9310-4281-ba48-d84fb38345c3.png)

# Class Diagram
![Class Diagram](https://user-images.githubusercontent.com/52111635/132999387-11830a47-4d69-48a7-84ef-cdd3c3ba793a.png)

# Program Output
{Iron Man=[Show{id=1, showTime=Sun Jun 07 09:00:00 IST 2020, movie=Iron Man, theater=PVR, availableSeats=30}], The Walk To Remember=[Show{id=3, showTime=Sun Jun 07 09:00:00 IST 2020, movie=The Walk To Remember, theater=Big Cinema, availableSeats=40}, Show{id=4, showTime=Sun Jun 07 12:00:00 IST 2020, movie=The Walk To Remember, theater=Big Cinema, availableSeats=40}], Hera Pheri=[Show{id=2, showTime=Sun Jun 07 12:00:00 IST 2020, movie=Hera Pheri, theater=PVR, availableSeats=30}]} <br>
Successfully booked <br>
Successfully booked <br>
Ticket{owner='Nisarg', bookingTime=Mon Sep 13 00:25:11 IST 2021, numberOfSeats=10, bookedShow=Show{id=3, showTime=Sun Jun 07 09:00:00 IST 2020, movie=The Walk To Remember, theater=Big Cinema, availableSeats=20}} <br>
Ticket{owner='Dhruva', bookingTime=Mon Sep 13 00:25:11 IST 2021, numberOfSeats=10, bookedShow=Show{id=3, showTime=Sun Jun 07 09:00:00 IST 2020, movie=The Walk To Remember, theater=Big Cinema, availableSeats=20}} <br>
Successfully booked <br>
Seats not Available <br>
Ticket{owner='Nisarg', bookingTime=Mon Sep 13 00:25:11 IST 2021, numberOfSeats=15, bookedShow=Show{id=3, showTime=Sun Jun 07 09:00:00 IST 2020, movie=The Walk To Remember, theater=Big Cinema, availableSeats=5}} <br>
null <br>
