# Booking-App
A tickets booking application which performs booking and generation of tickets concurrently using go routines.

## About
1. Used go routines for implementing a ticket booking application for booking and sending tickets to the users.
2. The main application performa the booking of the tickets for the users.
3. Threads are used for sending the tickets to multiple users simultaneously without stopping the flow of execution for the booking function.
4. Once the tickets are sent the threads are removed automatically.
5. The program end when all the tickets have been sent.

## Output
Execute using : `go run .`

![Screenshot from 2022-02-08 13-14-35](https://user-images.githubusercontent.com/43132209/152942951-36f49d53-f2b1-4cbb-8210-a338acf4d501.png)
