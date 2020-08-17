# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given: backup facility which stores data on each update

  When: server restarts update server

  Then: update server

Scenario: Reconcile counts if the sensor is offline for a while

  Given: sensor with a buffer storage

  When: sensor is offline, store the count in buffer

  Then: update server from buffer
