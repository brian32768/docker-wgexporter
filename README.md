# docker-wgexporter


docker run -d --net=host --cap-add=NET_ADMIN --name wgexporter -e 9586:9586 mindflavor/prometheus-wireguard-exporter -a true

curl -s http://localhost:9586/metrics


