docker run --name neo4j -e NEO4J_AUTH=none -p 7474:7474 -p 7687:7687 -e NEO4J_apoc_export_file_enabled=true -e NEO4J_apoc_import_file_enabled=true -e NEO4J_apoc_import_file_use__neo4j__config=true -e NEO4J_PLUGINS='["apoc"]' -d neo4j

![alt text](image.png)