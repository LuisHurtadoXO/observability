# Observability

Please install the following modules/dependencies to run the project:

* npm install --save @opentelemetry/api --legacy-peer-deps
* npm install --save @opentelemetry/sdk-trace-node --legacy-peer-deps
* npm install --save opentelemetry-instrumentation-express --legacy-peer-deps
* npm install --save @opentelemetry/instrumentation-mongodb --legacy-peer-deps
* npm install --save @opentelemetry/instrumentation-http --legacy-peer-deps
* npm install --save express --legacy-peer-deps
* npm install --save mongodb@4.3.1 --legacy-peer-deps
* npm install --save @opentelemetry/exporter-jaeger --legacy-peer-deps

When trying to commit my changes, the node_modules folder would provide an GitHub error relating to secrets.