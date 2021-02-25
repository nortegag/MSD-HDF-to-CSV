Modified Alexis Greenstreet's code (https://github.com/AGeoCoder/Million-Song-Dataset-HDF5-to-CSV) to extract H5 files from the data subset (and full data)

1. /data is not included. Download the sample data (HDF5) and name the directory 'data' (current one is empty). The program will recursively write out our CSV file.
2. SongCSV.csv -- this is the generated full data. There's no real reason to run the program again, unless you want a fresh 10k or the full dataset.
3. To run -- python msdHDF5toCSV.py

Takes a while to run.

N


Added dimensions: 
- song_hotttnesss
- artist_hotttnesss
- artist_mbtags
- artist_mbtags_count