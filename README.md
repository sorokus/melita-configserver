# Melita Cloud Config Server
Manages Melita configurations available at https://github.com/sorokus/melita-config-repo.

Runs on port *8888* by default.

## Build
```bash
mvn clean install
```

## Run
```bash
mvn spring-boot:run
```

## Example client usage
```bash
curl localhost:8888/ordermanagement/dev
```

```bash
curl localhost:8888/ordermanagement/defaut
```
