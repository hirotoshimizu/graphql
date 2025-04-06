# graphql
```
mutation CreateConnectionMutation ($config: ConnectionConfig!, $projectid: ID) {
  createConnection(config: $config, projectId: $projectid){
    id,
    driverId,
    name,
    host,
    port,
    serverName,
    databaseName
  }
}
```

```variable
{
  "config": {
    "connectionId": "connectionid-test",
    "name": "name-test",
    "driverId": "driverId-test",
    "host": "host-test"
  },
  "projectid": "g_GlobalConfiguration"
}
```
