# scaleway-ddns

Update DNS record on Scaleway's nameserver using their API.

Set up `.env` files for every record to update:
```
$ cp env.example home.domain.tld.env
$ vi home.domain.tld.env
```

## Cron

Run every hour:
```
0 * * * * ./scaleway-ddns >>cron.log 2>&1
```
