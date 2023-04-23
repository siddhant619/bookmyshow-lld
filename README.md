# BookMyShow low level design

## Requirements overview

For simplicity I have considered the system design only from the perspective of the
user booking tickets.

1. Users can set their city.
2. System should display recommended movies in the city.
3. User should be able search for movies by - title/language.
4. User should be able to select date and the system should display the list of theatres
   showing the movie on that date.
5. System should then display the seat map for the hall that plays the selected movie on
   the given time slot. The seat map should clearly display the occupied/available seats.
6. User then selects seats and proceeds to payment.
7. No two users can select a particular seat: ?
