# Todo List
이 프로젝트는 간단한 Todo List 웹 애플리케이션입니다.<br />
Node.js와 Express로 서버를 구현하고, 프론트엔드는 EJS 템플릿 엔진으로 구성했습니다.<br />
사용자는 할 일을 입력하면, 해당 데이터는 fetch API를 통해 서버로 전송되고, 서버는 이를 MySQL에 저장합니다.<br />
저장된 데이터는 다시 서버에서 조회되어 클라이언트에 표시됩니다.

### 🛠️ 사용 기술
- Node.js
- Express
- EJS
- MySQL
- Winston

### ✨ 주요 기능
- 할 일 추가
- 할 일 수정
- 할 일 삭제
- 할 일 목록 조회

### 🚀 실행 방법
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
```env
DB_HOST=localhost
DB_USER=your_username
DB_PASSWORD=your_password
DB_DATABASE=todolist
PORT=3000
NODE_ENV=dev
```
4. MySQL 데이터베이스 및 테이블 생성
```bash
mysql -u your_username -p < db/schema.sql
```
5. 서버 실행
```bash
node app.js
```

### 🖥️ 실행 화면
<img src="./img/test.gif" alt="test-page" width="500" />