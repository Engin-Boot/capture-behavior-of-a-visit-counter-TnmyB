# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given: The data entry card issuer works and records purpose of visit
  
  When: Count the number of patients from the entry card issuer for each day
  
  Then: Data for working and holidays can be identified


Scenario: Compute parking slots to reserve for visiting specialists

  Given: foot-fall counter maintains real-time count of people inside hospital
         and count of total parking spaces

  When: number of vehicles in parking can be estimated as number of persons inside by 2
  
  Then: if the number is 20% of total parking spaces available reserve spots for specialists
