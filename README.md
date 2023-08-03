# time_store

### Task Checkpoints

1. **Data Ingestion:**
   - [x] Read data from CSV files for data sources 1, 2, and 3.
   - [x] Store the data in a SQLite database as separate tables.
   - [x] Ensuring that the data is correctly stored and accessible.

2. **Data Processing:**
   - [ ] Convert timestamps to the appropriate timezones using data source 3 (timezone information).
   - [ ] Extrapolate uptime and downtime based on periodic polls using interpolation logic.
   - [ ] Verify the accuracy of the extrapolation process.

3. **Business Hours Filtering:**
   - [ ] Filter data from data source 1 to include only observations within business hours.
   - [ ] Confirm that only valid data during business hours is extracted.

4. **Report Generation:**
   - [ ] Calculate uptime and downtime metrics for each store for the last hour, last day, and last week.
   - [ ] Format the output data with the required schema.
   - [ ] Validate the correctness of the generated report.

5. **API Implementation:**
   - [ ] Create an API to fetch the report data.
   - [ ] Implement API endpoints for handling requests and queries.
   - [ ] Ensure the API returns data in a structured format (e.g., JSON).

6. **Error Handling:**
   - [ ] Implement error handling to gracefully handle potential issues.
   - [ ] Test the system to verify proper error handling.

7. **Documentation:**
   - [ ] Create detailed documentation explaining the system architecture, data flow, and API endpoints.
   - [ ] Include clear instructions on how to use the API to fetch the report.
