# Tutorial

해당 프로젝트는 docker 기반 SVN (혹은 Gitlab?), Jenkins 컨테이너를 생성하여 최종적으로는 AWS EC2에 배포하여 클라우드 상에 CI/CD 환경을 구축하는 것을 목표로합니다.

## Directory

```
├── docker-compose.yml                      # docker-compose up target
├── docker-compose.core.yml                 # docker-compose 기본 설정정보
├── Dockerfile
└── README.md
```

디렉토리 구조 수정중...

## 참고

- https://kimseunghyun-bg.github.io/devops/docker/setup_svn_server/
- https://kimchi-dev.github.io/posts/Jenkins_SVN_commit/
