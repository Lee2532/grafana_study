# grafana

> Grafana VS Kibana
```
데이터를 시각화하여 분석 및 모니터링을 용이하게 해주는 오픈소스 분석 플랫폼

그라파나 : 시스템 관점인 CPU 메모리, 디스크 IO 및 사용율과 같은 메트릭스 지표를 시각화 하는데 특화

키바나 : 엘라스틱 위에서 실행되며 주로 로그메세지 분석에 사용
```

> 그라파나 초기 user 및 password setting file

```
config.env
```

> 최초 부팅시 DB 세팅

```
./provisioning/datasource

관련정보

doc

https://grafana.com/docs/grafana/latest/administration/provisioning/

github

https://github.com/grafana/grafana/blob/main/devenv/datasources_docker.yaml

```
> Dashboard 세팅

```
https://github.com/grafana/grafana/blob/main/devenv/dashboards.yaml
```
> notifier 세팅
```
./provisioning/notifier

https://github.com/grafana/grafana/blob/main/conf/provisioning/notifiers/sample.yaml


```

> 추가 작업해야하는것들

```
1. slack 자동 세팅 (완)
2. image render 세팅 및 이미지 전송 (with S3 or local save)
3. 구축된 기능들 자세하게 공부
4. 타 서버 연동하여 모니터링
5. Dash Board custom
6. default 계정 추가하기 (admin 제외, read 권한만 가진)
7. 포트 변경하기
```