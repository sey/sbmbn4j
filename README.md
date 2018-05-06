docker run \
  --detach \
  --name=sbmbn4j-neo4j \
  --env=NEO4J_AUTH=none \
  --volume=totem-neo4j-data:/data \
  --publish=7474:7474 \
  --publish=7687:7687 \
  neo4j:3.3.5