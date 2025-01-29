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
    # api = AirportsAPIClient("[e67a1284-b622-4338-8add-070e4452f61e]")
#
# 2d. Perform Request
  # Define query
  # Dallas  
    #   query = { "iata": "DFW" }
    #   query = { "iata": "ADS" }
    #   query = { "iata": "DAL" }
    #   query = { "iata": "RBD" }
    #   query = { "icao": "KGKY" }
  # CHICAGO
    #   query = { "iata": "ORD" }
    #   query = { "iata": "PWK" }
    #   query = { "iata": "DPA" }
    #   query = { "iata": "MDW" }
    #   query = { "iata": "GYY" }
    #   query = { "iata": "RFD" }
# 2e. Make a request to the API
    #   result = api.execute(query)

# Print the result
    #   print(result)
