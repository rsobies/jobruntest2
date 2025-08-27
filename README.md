1. run 
```bash
docker run --name prometheus -d -p 9090:9090 -v ./prom.yml:/etc/prometheus/prometheus.yml prom/prometheus
```
2. run mongodb and create `harpagon` db
3. run the app
4. go to loclahost:9090
5. paste `process_cpu_usage * 100` in the expresion, swithc to graph tab


