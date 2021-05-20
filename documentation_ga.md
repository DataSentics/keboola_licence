persona360_ga_keboola_extractor
GA Extractor for Keboola Component platform

DataSentics Keboola component for downloading Google Analytics 360 data. Raw data are downloaded via BigQuery and Google Cloud Storage to Keboola file storage as avro files.
These data are used in Persona360 service. Data are extracted incrementally. 

To configure this extractor, you need to have Google Cloud Platform storage (gcp) and appropriate credentials for GA API. You also have to add desired datasets id, gcp bucket name, gcp bucket folder, default_latest export date in format ('yyyymmdd').
