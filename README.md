# argocd

CI/CD 프로세스를 위한 레포지토리
github action 으로 CI 프로세스를 진행하면, 현 레포의 yaml 파일 중 일부가 변경 됨
변경 된 레포의 정보를 argocd가 관찰하고 있다가, 자동으로 sync를 맞춤으로서 CD 프로세스를 완료함
