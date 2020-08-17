# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given: The data entry card issuer is works and records data for purpose of visit
  When: Compile data for the week and refresh it at the end of week
  Then: Facilities Manager can see data on patients, visitors or workers

Scenario: Alert when seating capacity is full

  Given: Total capacity, the data entry card issuer is working
  and records data for purpose of visit
  When: The count of patients is 2 less than the total capacity of hospital
  Then: Inform Facilities Manager and reserve seats for emergency cases
