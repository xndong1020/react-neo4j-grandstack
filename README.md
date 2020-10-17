### bootstrape project

```js
npx create-grandstack-app <project_name>
```

Then create an sandbox environment on sandbox.neo4j.com

change the settings from `api/.env`

```
NEO4J_URI=<your_neo4j_sandbox>
NEO4J_USER=<your_neo4j_sandbox>
NEO4J_PASSWORD=<your_neo4j_sandbox>

# Uncomment this line to enable encrypted driver connection for Neo4j
# NEO4J_ENCRYPTED=false

# Uncomment this line to specify a specific Neo4j database (v4.x+ only)
# NEO4J_DATABASE=neo4j

GRAPHQL_SERVER_HOST=0.0.0.0
GRAPHQL_SERVER_PORT=4001
GRAPHQL_SERVER_PATH=/graphql
```
