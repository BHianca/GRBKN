# GRBKN
Dataset associated to the article "Eighteen years of kilonova discoveries with Swift". Data for each GRB are made available in JSON format. Each file contains several fields and keys that are explained below.

| Field | Key | Description | Type 
| :--- | :--- | :--- | --- 
| `name`   |           | GRB name, e.g. "GRB060614" | String 
| `sources` |          | Data sources                   | 
|           | `bibcode` | 19 character NASA ADS bibcode | String 
|           | `reference` | Short form citation | String 
|           | `secondary` | Catalogue of published data | Boolean
|           | `id`   | Unique identifier | Integer 
| `trigger` |          | Discovery information                  | 
|           | `value` | Time of discovery | Float 
|           | `u_value` | Units, typically METs | String 
|           | `mission` | Satellite that discovered the GRB, e.g. Swift | String
|           | `instrument` | Detector that performed the observations , e.g. BAT | String
|           | `UTC`   | Time of discovery in Universal Time Coordinated | String
|           | `source`   | Reference ID | Integer 

