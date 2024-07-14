# node-exporter-monitoring

- node-exporter를 사용해서 모니터링하는 소스 코드의 예제입니다.
- node-exporter <-> prometheus <-> grafana를 사용합니다.

## quick start

### worker node

1. node-exporter-init.sh 실행

   ```bash
   # init
   git clone https://github.com/marsboy02/node-exporter-monitoring

   cd node-exporter-monitoring

   ./node-exporter-init.sh
   ```

2. prometheus.yml에 node-exporter를 실행한 노드의 IP 추가
3. 마스터 노드 실행

### master node

```bash
# start docker
docker-compose up -d
```
