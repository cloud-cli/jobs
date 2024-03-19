# jobs

Job scheduler

## add

```
cy jobs.add --exec 'rm /var/logs/*'
cy jobs.add --exec 'reboot' --at '12am'
```

## remove

```
cy jobs.remove --id '<id>'
```

## logs

```
cy jobs.logs --id '<id>'
```
