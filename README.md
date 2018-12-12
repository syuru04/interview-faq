# 최초 프로젝트 생성 시 수행하는 작업


## 1. 작업폴더 및 파일 생성
```bash
mkdir interview-faq
cd interview-faq
echo "# interview-faq" >> README.md
```

## 2. 로컬 저장소 생성
```bash
git init
```

## 3. 백업
```bash
git add --all
git status
git commit -m "frist commit"
git log
```

## 4. 원격저장소 등록(연결)
```bash
git remote add origin https://github.com/elinmk627/interview-faq.git
git remote -v
```

## 5. 로컬 저장소 ==업로드==> 원격 원격저장소
```bash
git push -u origin master
```

## 6. 팀원에게 접근권한부여
```bash
깃헙 접속 >> settings >> collaborators
>> Serch by username, full name or email address
```
-----------------


# 프로젝트 중간에 수행하는 작업

##1. 작업폴더 및 파일 생성
에디터로 수행하는 작업

##2. 로컬 저장소 생성
```bash
git add --all
git status
git commit -m "frist commit"
```

##3. 로컬 저장소 ==업로드==> 원격 원격저장소
등록된 원격 저장소가 하나일 때 간단하게 업로드가 가능함.
```bash
git push
```

push를 거부하는 경우에 대처방법은 먼저 pull을 수행하고 그 후 push하는 것이다.
```bash
git pull
git push
```
-------------------------------
# 팀원이 최초 수행하는 작업

## 1. 작업 폴더 및 파일 생성

이미 팀장이 수행했으므로 팀원은 팀장의 작업결과물을 가져오면 된다.

```bash
git clone URL https://github.com/syuru04/interview-faq
```

--------------------------
# 프로젝트 중간에 수행하는 작업
```bash
git pull
git push
```