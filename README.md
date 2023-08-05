# Time Store

### Task Checkpoints

1. **Data Ingestion:**
   - [x] Read data from CSV files for data sources 1, 2, and 3.
   - [x] Store the data in a SQLite database as separate tables.
   - [x] Ensuring that the data is correctly stored and accessible.

2. **Data Processing:**
   - [x] Convert timestamps to the appropriate timezones using data source 3 (timezone information).
   - [ ] Extrapolate uptime and downtime based on periodic polls using interpolation logic.
   - [ ] Verify the accuracy of the extrapolation process.

3. **Business Hours Filtering:**
   - [x] Filter data from data source 1 to include only observations within business hours.
   - [x] Confirm that only valid data during business hours is extracted.

4. **Report Generation:**
   - [x] Calculate uptime and downtime metrics for each store for the last hour, last day, and last week.
   - [x] Format the output data with the required schema.
   - [x] Validate the correctness of the generated report.

5. **API Implementation:**
   - [x] Create an API to fetch the report data.
   - [x] Implement API endpoints for handling requests and queries.
   - [x] Ensure the API returns data in a structured format (e.g., CSV).

![Screenshot from 2023-08-05 17 43](https://github.com/Deepak-Choudhary0/time_store/assets/114693662/b6b566c6-91f7-4ba6-9b4e-ee5bc6bf4651)



![Screenshot from 2023-08-05 17 42 37](https://github.com/Deepak-Choudhary0/time_store/assets/114693662/03425af5-d902-4cc7-8672-74c91f6f3cd5)
