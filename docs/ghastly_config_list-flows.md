## ghastly config list-flows

list in-progress but not started config flows

### Synopsis

list in-progress but not started config flows

```
ghastly config list-flows [flags]
```

### Options

```
  -h, --help   help for list-flows
```

### Options inherited from parent commands

```
      --loglevel string   log level; one of TRACE, DEBUG, INFO, WARN, ERROR, FATAL, PANIC (default "INFO")
  -o, --output text       output format for commands; options are text or `json` (default "text")
      --server string     the URL used to access homeassistant. defaults to value of HASS_SERVER environment variable (default "http://nuc.lan:8123")
      --token string      the bearer token used to authenticate to homeassistant. defaults to value of HASS_TOKEN environment variable (default "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJjZGZlZDAwNDE1NmM0NTM2YTI4MDRiMmRiMjUzN2JmMCIsImlhdCI6MTU0OTc2Mzc3MywiZXhwIjoxODY1MTIzNzczfQ.wHtNVzQoEb1hY5m86QaEKOIp5pApyO0HZBJBDjfCJZc")
```

### SEE ALSO

* [ghastly config](ghastly_config.md)	 - sub-commands for manipulating and interacting with config entries

###### Auto generated by spf13/cobra on 17-May-2020