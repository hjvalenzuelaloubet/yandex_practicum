# Data

We have the next features.
  - *DateCrawled* — date profile was downloaded from the database
  - *VehicleType* — vehicle body type
  - *RegistrationYear* — vehicle registration year
  - *Gearbox* — gearbox type
  - *Power* — power (hp)
  - *Model* — vehicle model
  - Mileage — mileage (measured in km due to dataset's regional specifics)
  - *RegistrationMonth* — vehicle registration month
  - *FuelType* — fuel type
  - *Brand* — vehicle brand
  - *NotRepaired* — vehicle repaired or not
  - *DateCreated* — date of profile creation
  - *NumberOfPictures* — number of vehicle pictures
  - *PostalCode* — postal code of profile owner (user)
  - *LastSeen* — date of the last activity of the user

Our target is

  *Price* — price (Euro)

## Goal:
Create a model that is able to predit the price of the listing. Models used: random forest, linear regression, LightGBM and CatBoost.
