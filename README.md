# Pizza API Inventory Project

### .NET CLI terminal commands
- Start REPL and connect to API: \
`httprepl https://localhost:{PORT}`
- Connect to API (if REPL is already running): \
`connect https://localhost:{PORT}`
- #### with REPL running in CLI:
- Explore available endpoints: \
`ls`
- Select an endpoint: \
`cd {EndpointName}`
- #### CRUD actions from selected endpoint:
- Create: \
`post {id} "{{JSON}}"`
- Read: \
`get` | `get {id}`
- Update: \
`update {id} -c "{{UpdatedJSON}}"`
- Delete: \
`delete {id}`
- Exit the REPL/CLI: \
`exit`
