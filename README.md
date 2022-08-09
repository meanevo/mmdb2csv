# mmdb2csv

# What does it do?

Convert Maxmind mmdb database to CSV.

# Why?

Many applications support CSV but not mmdb.  For example it's easy to import CSV to SQL databases.

# How?

1. Build `go build mmdb2csv.go`
2. Update [database](https://github.com/P3TERX/GeoLite.mmdb)
3. Run
   * `./mmdb2csv GeoLite2-ASN.mmdb 4809`
   * `./mmdb2csv GeoLite2-City.mmdb Taipei`
   * `./mmdb2csv GeoLite2-Country.mmdb TW`

