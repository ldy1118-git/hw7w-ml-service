# HW7W 머신러닝 서비스 만들기

머신러닝프로젝트 001분반 HW7W — K-POP 여자 연예인 사진 분류 웹 서비스

- 작성: 임대윤 (22016077)
- 분류 클래스: 최예나 · 김채원 · 강혜원 (Kaggle KID-F 데이터, Teachable Machine으로 학습)
- 웹 템플릿: 안홍렬 교수 [machine-learning-app-template](https://github.com/hongryulahn-lecture/machine-learning-app-template)

## 실행 (학과 서버 JupyterHub · 내 계정 터미널)

```bash
mkdir -p ~/work/project && cd ~/work/project   # ~/work 밖은 로그아웃 시 삭제
git clone https://github.com/ldy1118-git/hw7w-ml-service.git   # 처음 한 번 (이후에는 git pull)
cd hw7w-ml-service
python -m http.server 6000         # 이 터미널은 웹 전용 — 다른 명령은 새 터미널에서
```

주소 확인: `echo "https://ahnbi4.suwon.ac.kr:5300${JUPYTERHUB_SERVICE_PREFIX}proxy/6000/"`

백업 주소 (GitHub Pages): https://ldy1118-git.github.io/hw7w-ml-service/
