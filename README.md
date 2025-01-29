# Python-Projects
#
# 2. Choose A Map API & Fetch Data
# 
# 2a. Airport API PIP Installation
# pip install apiverve-airportslookup
# 
# 2b. Airport API Key
# API Key: e67a1284-b622-4338-8add-070e4452f61e from NCHeld linked GitHub at https://apiverve.com/dashboard/
# 
# 2c. Setup
# Import the client module
# from apiverve_airportslookup.apiClient import AirportsAPIClient

# Initialize the client with your APIVerve API key
#   api = AirportsAPIClient("[e67a1284-b622-4338-8add-070e4452f61e]")
#
# 2d. Perform Request
# Define query
#   query = { "iata": "ORD" }
  # Dallas
  #IATA: DFW Dallas Fort Worth International
  #ICAO: KGKY Arlington Municipal
  #IATA: ADS Addison Airport
  #IATA: DAL Dallas Love Field
  #IATA: RBD Dallas Executive Airport
  # CHICAGO
  #IATA: PWK - Chicago Executive Airport
  #IATA: ORD - O'Hare Airport
  #IATA: DPA - DuPage Airport Authority
  #IATA: MDW - Chicago Midway
  #IATA: GYY - Gary/Chicago International
  #IATA: RFD - Chicago Rockford International

# 2e. Make a request to the API
#   result = api.execute(query)

# Print the result
#   print(result)
