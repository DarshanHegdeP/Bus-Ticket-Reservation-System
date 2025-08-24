# Bus Ticket Reservation System

**Repository URL**: [https://github.com/DarshanHegdeP/Bus-Ticket-Reservation-System](https://github.com/DarshanHegdeP/Bus-Ticket-Reservation-System)

---

## Overview

This is a **Node.js backend project** for a Bus Ticket Reservation System.  
It allows users to view buses, search by destination, book and cancel tickets.

---

## Features

- **View Buses**: List all available buses with schedules.  
- **Search Buses**: Search buses by destination.  
- **Book Tickets**: Reserve seats and store passenger details.  
- **Cancel Tickets**: Cancel previously booked tickets.

---

## Technologies Used

- **Backend**: Node.js  
- **Database**: MySQL  

---

## Installation & Setup

### Prerequisites

- Node.js (v14 or higher)  
- MySQL  

### Steps

1. **Clone the Repository**:

```bash
git clone https://github.com/DarshanHegdeP/Bus-Ticket-Reservation-System.git
cd Bus-Ticket-Reservation-System
```
Install Dependencies:
```
npm install
```
**Set Up Database**:

Create a database in MySQL and import the provided SQL file.
Update database credentials in the configuration file (e.g., config.js).

**Run the Server**:
```
node server.js
```

The backend will run locally, ready to handle bus ticket operations.

## Usage
Users can:
- View available buses.
- Search for buses by route or destination.
- Book tickets and store passenger information.
- Cancel previously booked tickets.
