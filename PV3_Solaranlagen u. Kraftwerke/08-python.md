# Übersicht
heute wird alle davor genutzten Programme in 

### Imports
from settings import postgres_session
from pv3_export_polysun import calculate_diffuse_irradiation

### Funktionen bilden
- gibt dhi und dni für htw weatherdata zurück
  `` def calculate_diffuse_irradiation(df, parameter_name, lat,  lon)``
  df_solarpos = pvlib.solarposition.spa_python
`pip3 install pvlib`