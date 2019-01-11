# Avro Tools jar
wget http://central.maven.org/maven2/org/apache/avro/avro-tools/1.8.2/avro-tools-1.8.2.jar

## To Json
java -jar avro-tools-1.8.2.jar tojson --pretty customer-generic.avro
java -jar avro-tools-1.8.2.jar tojson --pretty customer-specific.avro

## Get Schema
java -jar avro-tools-1.8.2.jar getschema customer-specific.avro