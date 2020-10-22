# MaRINET2 metadata schemas
This repository contains MaRINET2 metadata schemas for :
- [Data streams](./datastream_schema.yaml), where data stream represents recorded values of one variable
 
- [Datasets](./dataset_schema.yaml), where dataset represents collection of one or multiple data streams

The schemas are meant to be used when generating MaRINET2 compatible [NetCDF](https://www.unidata.ucar.edu/software/netcdf/) files. An end-user should be able to fill-in above schemas, which are currently provided as [YAML](https://en.wikipedia.org/wiki/YAML) files, and use data conversion tools to read them and enrich NetCDF files prior their publication and preservation.

The schemas are registered at [FAIRsharing.org](https://fairsharing.org/bsg-s001497/).
