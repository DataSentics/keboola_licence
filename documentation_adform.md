This component uses the AdForm API to extract raw data for four entities and Metadata used in Persona360 service. Four entities are:
- 'Click',
- 'Event',
- 'Impression',
- 'Trackingpoint'.
- meta
Data are extracted incrementally and in gz format. Metadata are downloaded as zip.
By default all entities are downloaded, optionally you can selected only some of them.

To configure this extractor, you need to have AdForm account including appropriate credentials. Required fields for working correctly are Client ID, Client Secret and Setup ID.

By default it checks last downloaded files and started from them until current day, but optionally it's possible to select date from/to. If last downloaded is not found, it downloads everything. Via API is possible to download cca 7 days back. 
