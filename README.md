# India PIN Code Dataset with GPS Coordinates

All India PIN Code Directory Dataset available in the link is the input for this dataset.

https://data.gov.in/catalog/all-india-pincode-directory?filters%5Bfield_catalog_reference%5D=85840&format=json&offset=0&limit=6&sort%5Bcreated%5D=desc

During the time of creation, the dataset only contains GPS Co-ordinates for the Departmental Post offices situated in Mysore and Nanjangud Postal Divisions in Karnataka State.

There are very few updates happened in the Dataset, but it does not covers the all of the PIN Codes in India.

For the sake of simplicity, the input from the OGD Platform taken as base and filtered only unique "Deliverable" Pincodes as a single PIN Codes shall have multiple Branch Post Offices and found the GPS Coordinates for those.

All the information has been removed from the original dataset except the Name, Pincode, District and State. The other details like Taluk and Post Office Type, Delivery were removed.

The GPS Co-ordinates were found from the openly available maps via Geocoding, So, the co-ordinates may not be the exact location, but could give an approximate location for generic use cases, like finding the District and State with the PIN Code and finding the nearby PIN Codes, shortest distance between the given PIN Codes vs the predefined set of PIN Code etc.
