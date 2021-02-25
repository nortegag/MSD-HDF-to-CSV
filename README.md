# MSD-HDF-to-CSV
SI 699 - Data Extraction from HDF to CSV. 

All credit to AGeoCoder/ and his <a href="https://github.com/AGeoCoder/Million-Song-Dataset-HDF5-to-CSV"> Million-Song-Dataset-HDF5-to-CSV  </a> repository

Simple changes to add additional features to the MSD Dataset. Mostly used for the extracted CSV data "SongCSV.csv"

1. /data directory is not included. Download the sample data (HDF5) and name the directory 'data'. The program will recursively write out our CSV file.
3. SongCSV.csv -- this is the generated full data. There's no real reason to run the program again, unless you want a fresh 10k or the full dataset.
4. To run -- python msdHDF5toCSV.py

Takes a while to run.

Added dimensions: 
- song_hotttnesss
- artist_hotttnesss
- artist_mbtags
- artist_mbtags_count

WARNING -- Python: This code was tested with a Python interpreter with version 2.7.9.
