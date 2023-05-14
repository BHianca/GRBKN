# GRBKN
Dataset associated to the article "Eighteen years of kilonova discoveries with Swift". Data for each GRB are made available in JSON format. Each file contains several fields and keys that are explained below.

| Field | Key | Description | Type 
| :--- | :--- | :--- | --- 
| `name`   |           | GRB name, e.g. "GRB060614" | String 
| `sources` |          | Data sources                   | 
|           | `bibcode` | 19 character NASA ADS bibcode | String 
|           | `reference` | Short form citation | String 
|           | `url` | Link to the catalogue's website | String 
|           | `secondary` | Catalogue of published data | Boolean
|           | `id`   | Unique identifier | Integer 
| `trigger` |          | Discovery information                  | 
|           | `value` | Time of discovery | Float 
|           | `u_value` | Units, typically METs | String 
|           | `mission` | Satellite that discovered the GRB, e.g. Swift | String
|           | `instrument` | Detector that performed the observations , e.g. BAT | String
|           | `UTC`   | Time of discovery in Universal Time Coordinated | String
|           | `source`   | Reference ID | Integer 
| `photometry` |          | Photometric data                  | 
|           | `time` | Time since the GRB | Float 
|           | `u_time` | Time units: seconds (s), hours (hr), or days (d) | String 
|           | `filter` | Photometric passband used for the observation | String 
|           | `magnitude` | Apparent magnitude  | Float 
|           | `e_magnitude` | 1 sigma error. When negative, it indicates an upper limit | Float 
|           | `ul_sigma` | Upper limit confidence level (in units of sigma). If negative its value is unknown | Integer 
|           | `system` | Photometric system used, either Vega or AB | String
|           | `telescope` | Telescope that performed the observation, e.g. Gemini-N | String
|           | `instrument` | Detector used for the observation, e.g. GMOS | String
|           | `source`   | Reference ID | Integer 
