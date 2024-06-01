Tax_Training folder creates the model.pkl and model_columns.pkl files.

Service folder creates the Rest API service using Flask at https://127.0.0.1:5000

Test the output using https://127.0.0.1:5000/show_result path.

Send the data using the POST response. Sample input data: [{"pickup_community_area":40, "trip_start_hour":12,"trip_miles":20.3, "trip_seconds":5000,"dropoff_community_area":33},{"pickup_community_area":40, "trip_start_hour":12,"trip_miles":20.3, "trip_seconds":500,"dropoff_community_area":33}]

The web page will be launched at https://127.0.0.1:80 
