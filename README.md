# Applied-Data-Science-Capstone
Final Project for Applied Data Science Caption


spacex_url="https://api.spacexdata.com/v4/launches/past"
response = requests.get(spacex_url).json()

response2 = requests.get(static_json_url).json()
data = pd.json_normalize(response2)
