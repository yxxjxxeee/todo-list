# Todo List
간단한 Todo List 웹 애플리케이션입니다.  
Node.js와 Express를 기반으로 서버를 만들고, EJS로 프론트엔드를 구성했어요.  
fetch API를 사용해 할 일을 서버에 추가하고 불러옵니다.  
MySQL 데이터베이스를 사용해 할 일 데이터를 저장합니다.

## 사용 기술
- Node.js
- Express
- EJS
- MySQL
- Winston


## 주요 기능
- 할 일 추가
- 할 일 목록 조회
- 할 일 수정
- MySQL 데이터베이스에 데이터 저장 및 조회

## 실행 방법
1. 레포지토리 클론 및 폴더 이동
```bash
git clone https://github.com/yxxjxxeee/todo-list.git
cd todo-list
```

2. 의존성 설치
```bash
npm install
```

3. env 파일 생성 및 설정
```bash
DB_HOST=localhost
DB_USER=your_username
DB_PASSWORD=your_password
DB_NAME=todo_db
PORT=3000
```

4. MySQL 데이터베이스 및 테이블 생성
```bash
mysql -u your_username -p < db/schema.sql
```
5. 서버 실행
```bash
node app.js
```

6. 브라우저에서 접속
```bash
http://localhost:3000
```
