# Finals Lab Task 1 - Events Management DB

## Create Database:
We first create the database **kaloy_events** if it doesn't already exist.

### Create `kaloy_events_tbl`:
This table holds events with an `event_id` as the primary key and `event_name`.

### Create `kaloy_attendees_tbl`:
This table holds attendees with an `attendee_id` as the primary key and `attendee_name`.

### Create `kaloy_events_attendees_tbl`:
This table links `kaloy_events_tbl` and `kaloy_attendees_tbl` using a many-to-many relationship. It uses `event_id` and `attendee_id` as foreign keys.

### Create `kaloy_event_sponsors_tbl`:
This table links sponsors to events with the `event_id` and `sponsor_name`.

## STEP 2 - Here's the screenshot of my output tables:

![Event Tables](Images/TABLES.jpg)

[*Here's the raw file*](https://github.com/MassStarvation01/Anaya_Portfolio/blob/main/Finals_Task-1/Images/Kaloy_tbls.jpg)

## STEP 3 - Here's the screenshot of my output ERD:

![Event ERD](Images/ERD.jpg)

[*Here's the raw file*](https://github.com/MassStarvation01/Anaya_Portfolio/blob/main/Finals_Task-1/Images/ERD_FT1.jpg)
