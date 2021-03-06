# Job Synthesis

Jobs in GTAModelV4 are generated by splitting the total employment vector by the employment occupation rates,
external worker rates, and the work at home rates.  In GTAModel V4.0 these rates are applied at the planning
district level.  

In GTAModel V4.1 these rates are applied at a zonal level if there are a sufficient number
of observed full-time records in the Transportation of Tomorrow Survey 2016.  Sufficiency is defined as
having 20+ observations of a single occupation category or having 30+ total full-time observations.
While computing the planning district averages, zones that have sufficient observations are excluded.
