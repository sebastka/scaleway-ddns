# scaleway-ddns

Update records on Scaleway's DNS server using API calls.

Set up .env files for every record to update:
```
$ cp env.example home.domain.tld.env
$ vi home.domain.tld.env
```

## Cron

Run every hour:
```
0 * * * * ./scaleway-ddns >>cron.log 2>&1
```
