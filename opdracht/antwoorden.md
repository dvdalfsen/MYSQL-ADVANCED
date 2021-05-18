# Antwoorden Eindopdracht

1. Copy paste je gemaakte SQL query hieronder
   SELECT races.name"race" , circuits.name"circuits" from races left join circuits on circuits.circuitId = races.circuitId
2. Copy paste je gemaakte SQL query hieronder
   SELECT r.name, drivers.surname, driver_standing.points from races r LEFT JOIN driver_standing ON driver_standing.raceId = r.raceId LEFT JOIN drivers ON driver_standing.driverId = drivers.driverId WHERE r.year = 2017 AND driver_standing.points = 10
3. Copy paste je gemaakte SQL query hieronder
   SELECT drivers.forename, drivers.surname, pitstops.duration from drivers LEFT join pitstops on drivers.driverId = pitstops.driverId WHERE pitstops.milliseconds < 25000
4. Copy paste je gemaakte SQL query hieronder
   
5. Copy paste je gemaakte SQL query hieronder
   
