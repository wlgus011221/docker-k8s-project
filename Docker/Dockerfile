# Node.js 공식 이미지 사용
FROM node:18

# 앱 작업 디렉토리 설정
WORKDIR /app

# package.json과 package-lock.json 복사
COPY package*.json ./

# 의존성 설치
RUN npm install

# 앱 소스 복사
COPY . .

# 컨테이너 내부 포트
EXPOSE 80

# 앱 실행 명령
CMD ["node", "app.js"]

