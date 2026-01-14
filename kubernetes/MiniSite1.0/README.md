#miniSite
#기존에 만들어진 html파일에 Dockerfile을 추가해 이미지 생성
#이미지 push 후 deployment와 service를 추가해 각 페이지마다 Pod 생성.
#ingress.yaml 파일에 rewrite-target 방식으로 경로 설정 후 apply
#페이지 및 버튼 정상 동작 확인
#이미지 파일 수정 시 rolling을 통해 웹 페이지 끊김 없이 업데이트
