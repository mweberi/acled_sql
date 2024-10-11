
# ACLED Dataset SQL Practice Question - BONUS Questions

## Beginner Level

1. **Select Basic Columns**: Write a query to select `EVENT_DATE`, `EVENT_TYPE`, and `COUNTRY` from the dataset.
    ```sql
    -- Your SQL code here
    ```

2. **Count Records**: How many records are in the ACLED dataset?
    ```sql
    -- Your SQL code here
    ```

3. **Filter by Country**: Write a query to retrieve all events that occurred in Kenya.
    ```sql
    -- Your SQL code here
    ```

4. **Filter by Year**: Write a query to find all events that happened in the year 2020.
    ```sql
    -- Your SQL code here
    ```

5. **Filter by Event Type**: Write a query to find all `Protests` in the dataset.
    ```sql
    -- Your SQL code here
    ```

6. **Count Events by Country**: Write a query to count the number of events in each country.
    ```sql
    -- Your SQL code here
    ```

7. **List Unique Event Types**: Write a query to list all unique `EVENT_TYPE` values.
    ```sql
    -- Your SQL code here
    ```

8. **Select Events with Fatalities**: Write a query to select events where `FATALITIES` are greater than 0.
    ```sql
    -- Your SQL code here
    ```

9. **Filter by Region**: Write a query to retrieve all events that occurred in the `East Africa` region.
    ```sql
    -- Your SQL code here
    ```

10. **Sort by Date**: Write a query to list events sorted by `EVENT_DATE` in ascending order.
    ```sql
    -- Your SQL code here
    ```

11. **Select Events in Specific Location**: Write a query to select all events that occurred in `Nairobi`.
    ```sql
    -- Your SQL code here
    ```

12. **Filter by Disorder Type**: Write a query to find all events of the type `Violence against civilians`.
    ```sql
    -- Your SQL code here
    ```

13. **Count Events by Year**: Write a query to count the number of events for each year.
    ```sql
    -- Your SQL code here
    ```

14. **Select Columns with Conditions**: Write a query to select `EVENT_ID_CNTY`, `EVENT_DATE`, and `FATALITIES` where `FATALITIES` are more than 5.
    ```sql
    -- Your SQL code here
    ```

15. **Filter by Latitude and Longitude**: Write a query to find events within a specific latitude and longitude range.
    ```sql
    -- Your SQL code here
    ```


## Intermediate Level

1. **Aggregate Fatalities by Country**: Write a query to find the total number of fatalities in each country.
    ```sql
    -- Your SQL code here
    ```

2. **Events by Month**: Write a query to count the number of events that occurred each month.
    ```sql
    -- Your SQL code here
    ```

3. **Top Fatalities Events**: Write a query to find the top 10 events with the highest number of fatalities.
    ```sql
    -- Your SQL code here
    ```

4. **Events by Actor1**: Write a query to count the number of events involving each `ACTOR1`.
    ```sql
    -- Your SQL code here
    ```

5. **Filter by Interaction Type**: Write a query to find all events where `INTERACTION` equals 1.
    ```sql
    -- Your SQL code here
    ```

6. **Events by ISO Code**: Write a query to count events grouped by `ISO` code.
    ```sql
    -- Your SQL code here
    ```

7. **Average Fatalities**: Write a query to find the average number of fatalities per event.
    ```sql
    -- Your SQL code here
    ```

8. **Join with Admin Areas**: Write a query to join `ADMIN1`, `ADMIN2`, and `ADMIN3` for a comprehensive location analysis.
    ```sql
    -- Your SQL code here
    ```

9. **Filter by Precision**: Write a query to find events with `GEO_PRECISION` less than 1.
    ```sql
    -- Your SQL code here
    ```

10. **Events in Specific Regions**: Write a query to list all events that occurred in `Central Africa`.
    ```sql
    -- Your SQL code here
    ```

11. **Events by Source**: Write a query to count events by `SOURCE`.
    ```sql
    -- Your SQL code here
    ```

12. **Filter by Civilian Targeting**: Write a query to find all events where `CIVILIAN_TARGETING` is 'Yes'.
    ```sql
    -- Your SQL code here
    ```

13. **Monthly Events in a Year**: Write a query to find the number of events each month for a specific year (e.g., 2020).
    ```sql
    -- Your SQL code here
    ```

14. **Sub-Event Type Analysis**: Write a query to count the number of events for each `SUB_EVENT_TYPE`.
    ```sql
    -- Your SQL code here
    ```

15. **Fatalities by Region**: Write a query to find the total fatalities in each region.
    ```sql
    -- Your SQL code here
    ```


## Advanced Level

1. **Detailed Fatalities Analysis**: Write a query to find the total, average, and maximum number of fatalities for each `EVENT_TYPE`.
    ```sql
    -- Your SQL code here
    ```

2. **Event Trends Over Time**: Write a query to analyze the trend of events over the years (yearly event count).
    ```sql
    -- Your SQL code here
    ```

3. **Complex Filtering**: Write a query to find events involving a specific `ACTOR1` and occurring in a specific `COUNTRY` and `YEAR`.
    ```sql
    -- Your SQL code here
    ```

4. **Event Distribution by Location**: Write a query to analyze the distribution of events based on `LATITUDE` and `LONGITUDE`.
    ```sql
    -- Your SQL code here
    ```

5. **Temporal Analysis**: Write a query to analyze the distribution of events by `TIME_PRECISION`.
    ```sql
    -- Your SQL code here
    ```

6. **Country and Actor Interaction**: Write a query to find the number of interactions between specific actors (`ACTOR1` and `ACTOR2`) in each country.
    ```sql
    -- Your SQL code here
    ```

7. **Multi-Year Analysis**: Write a query to compare the number of events and fatalities across different years.
    ```sql
    -- Your SQL code here
    ```

8. **Events by Population Density**: Write a query to analyze the number of events in areas with different `POPULATION_BEST` values.
    ```sql
    -- Your SQL code here
    ```

9. **Location and Event Type Analysis**: Write a query to analyze the relationship between `LOCATION` and `EVENT_TYPE`.
    ```sql
    -- Your SQL code here
    ```

10. **Events by Source Scale**: Write a query to count the number of events reported by each `SOURCE_SCALE`.
    ```sql
    -- Your SQL code here
    ```

11. **Detailed Notes Analysis**: Write a query to search for specific keywords in the `NOTES` field and analyze the corresponding events.
    ```sql
    -- Your SQL code here
    ```

12. **Complex Joins and Filtering**: Write a query that combines multiple fields (e.g., `EVENT_TYPE`, `COUNTRY`, `YEAR`, `FATALITIES`) for a detailed report.
    ```sql
    -- Your SQL code here
    ```

13. **Correlation Analysis**: Write a query to analyze the correlation between `FATALITIES` and `DISORDER_TYPE`.
    ```sql
    -- Your SQL code here
    ```

14. **Dynamic Filtering**: Write a query to dynamically filter events based on multiple criteria (e.g., `REGION`, `EVENT_TYPE`, `YEAR`).
    ```sql
    -- Your SQL code here
    ```

15. **Performance Optimization**: Write a query to optimize the retrieval of events with high fatalities, ensuring efficient execution.
    ```sql
    -- Your SQL code here
    ```
