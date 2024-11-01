# GIT 과 GITHUB

## GIT

-- GIT : **분산** 버전 관리 시스템

-- GITHUB :  **원격 GIT 저장소**

### Local Git
- 저장소 생성 git init
``` bash
git config user.name "SeungHwan Kwan"
git config user.email quietly47@gmail.com
# 공용 git 설정을 하려면 -g
# 예) git config -g user.name 이름
```

- git 상태 확인
``` bash
git status
```
- staging
```bash
git add .
```

- 저장소에 반영(commit)
```bash
git commit -m "First commit"
```
```bash
-git status # 상태확인
-git log # 로그확인
``` 

### Local Git to GitHub
- GitHub에서 저장소 생성
- 저장소 주소
    https://github.com/Justinbeer/GITTEST.git
- 원격지 등록
```bash
git remote add origin https://github.com/Justinbeer/GITTEST.git
# git remote add 저장소이름 저장소주소
```
- push
```bash
git push -u origin master # 첫번째 푸시
git push # 기본원격지 현재브랜치를 푸시
```

### From GitHub to Local git
- 복제할 원격 저장소 주소 확보
- 복제
```bash
git clone https://github.com/Justinbeer/GITTEST.git
# git clone 원격지주소
```

- 저장소 설정을

- 원격지 변경사항 FETCH (확인)

- 원격지 변경사항 PULL (내려받기)