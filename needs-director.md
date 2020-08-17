# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given: Data entry card issuer works, records purpose of visit, holidays known
  
  When: Count the number of patients from the entry card issuer for each day
  
  Then: Data for working and holidays is obtained

Scenario: Compute parking slots to reserve for visiting specialists

  Given: foot-fall counter maintains real-time count of people inside hospital
         and count of total parking spaces

  When: number of vehicles in parking are estimated as
        number of persons inside by 2
  
  Then: if the number is less than 20% of total parking spaces
        reserve spots for specialists
