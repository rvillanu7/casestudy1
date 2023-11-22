Case Study 1: How does a bike-share navigate speedy success?

This case study engaged in data analysis for a bike-share company, taking the tasks of a data analyst through the stages of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act. 

Ask
How do annual members and casual riders use Cyclistic bikes differently?

Prepare
-Download data and stored it appropriately
-Checked for dupilcates
-Sort & filtered data
-Verified Data Integrity

Process
-Check data for errors
-Transform the data so I can work with it effectively.
-Document the cleaning process
  Cleaning Process:
    1. Check for duplicates
    2. Formate column width and added filters to headers
    3. Created "day_riding" column using =TEXT(@C:C, "DDDD")
    4. Created "duration" column using =TEXT(E2-C2, "h:mm:ss")
    5. Created "time_of_day" using =TEXT(D2, "h:mm AM/PM")
    5. Created "date" column using =TEXT(D2, "MM/DD/YY")
    6. Hid columns started_at, ended_at, start_station_name, start_station_id, end_station_name, end_station_id (left Lat & Long columns for now)
    7. Created pivot tables


    what days of the week
    what hour they rode ie evenigng afternon
    
