# Ingest OpenAddresses data with Logstash

1. Download and extract a dataset from http://results.openaddresses.io/
2. Copy the CSV file into this directory, i.e. `./countrywide.csv`.
3. Run `LOGSTASH_DIR=$(pwd) logstash -f openaddresses.conf` from within this directory.
