# kafka-connect-mongo
this repo include 4 files : 
1. Dockerfile + jar file - create a image for kafka connect sink to mongo. is include copy *.jar while build image.
2. values-kafka-with-kafka-connect.yaml - deploy with bitnami helm kafka and kafka connect - use mongo image.
3. values-mongo.yaml - deploy with bitnami helm repo mongodb
