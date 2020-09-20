# Immersion
> **WARNING: Immersion is not maintained anymore.**

Immersion is an open source project that allow users to create network visualizations of their email data.

## Building
### Downloading the project

```bash
git clone https://github.com/chopin2712/immersion
```

### Installing dependencies
You need to install the following dependencies:

* Python2
* Pip2
* Oath2client (1.4)
* Tornado

### Configure the ids
Before using immersion, you will need to update authentication data:

The authentication data in the project has been replaced with xxxxxx. These are:

1. client_id and client_secret in dev/newserver/client_secrets.json
2. client_id in authurl in dev/newserver/templates/index.html
3. client_id in authurl in dev/newserver/templates/indexStudy.html
4. client_id in authurl in dev/newserver/templates/gmail/busy.html
