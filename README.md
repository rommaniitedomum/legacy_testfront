<a name="top"></a>
[![Legacy project](/legacyprjt-main.png)](https://test-front-lovat.vercel.app)
![JavaScript Badge](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript&logoColor=white&style=flat)
![Python Badge](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white&style=flat)
![OS](https://img.shields.io/badge/OS-ubuntu%2C%20windows-0078D4)
![Deployment](https://img.shields.io/badge/Deployment-AWS%20%2B%20Vercel-orange?logo=amazonaws&logoColor=white&style=flat)
![Database](https://img.shields.io/badge/Database-PostgreSQL-blue?logo=postgresql&logoColor=white&style=flat)
![API](https://img.shields.io/badge/API-Google%20Maps-4285F4?logo=googlemaps&logoColor=white&style=flat)
![Environment](https://img.shields.io/badge/Environment-Anaconda-yellowgreen?logo=anaconda&logoColor=white&style=flat)
![Frontend](https://img.shields.io/badge/Frontend-React%20%2B%20Redux%20%2B%20TailwindCSS-blue?logo=react&logoColor=white&style=flat)
![Backend](https://img.shields.io/badge/Backend-Node.js%20%2B%20Express-green?logo=nodedotjs&logoColor=white&style=flat)
![IDE](https://img.shields.io/badge/IDE-VS%20Code%20%2B%20Cursor.ai-blue?logo=visualstudiocode&logoColor=white&style=flat)
![GitHub](https://img.shields.io/badge/Version%20Control-GitHub-black?logo=github&logoColor=white&style=flat)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue?logo=githubactions&logoColor=white&style=flat)
[![OpenAI API](https://img.shields.io/badge/OpenAI%20API-GPT--4o-brightgreen.svg?logo=OpenAI&logoColor=white)](https://openai.com/)

## 목차

- [설명](#-설명)
- [구성](#-구성)
- [설치](#-설치)
- [디버깅로그](#-디버깅)
- [자료](#-자료)
- [연락처](#%EF%B8%8F-연락처)

## 🏛️ 설명

**유산지기**: 국가 문화재,행사 알림 서비스

- **구글 맵 지원**:사용자 위치 기반 문화재 정보 제공
- **챗봇**: - 사용자 질문에 실시간으로 응답하고, 관심 있는 문화재 정보를 제공,
  문화재 검색 및 행사 일정 알림
- **데이터관리**: 문화재 및 행사 데이터의 효율적 저장 및 업데이트
- **유지보수**: 시스템 안정성 확보 및 정기적 업데이트를 통한 최적화

## 🎓 구성

| 기능             | 설명                                                                                  | 주요 파일                                                                                          |
|------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| **홈**           | 메인 화면과 네비게이션 제공                                                          | `Home.jsx`, `Header.jsx`, `Navbar.jsx`, `ImageSlider.css`, `store.js`                             |
| **챗봇**         | 문화재 관련 질문 응답 및 정보 제공                                                    | `Chatbot.jsx`, `Chatbot.css`, `config.js`, `MessageParser.js`, `store.js`                         |
| **위치 검색**     | 사용자 위치 기반 문화재 및 행사 검색                                                 | `Search.jsx`, `Map.jsx`, `Modal.jsx`, `heritageDetailSlice.js`, `store.js`                        |
| **행사 일정**     | 행사 일정 관리 및 알림 제공                                                         | `Event_schedule.jsx`, `EventModal.jsx`, `eventSlice.js`, `apiUrl.js`                              |
| **마이페이지**    | 사용자 관심 문화재 및 행사 목록 관리                                                  | `FavoriteList.jsx`, `Mypage.jsx`, `favoriteSlice.js`, `PageModal.jsx`                             |
| **로그인/회원가입**| 사용자 인증 및 계정 관리                                                           | `useAuth.js`, `authSlice.js`, `Login.jsx`, `Signup.jsx`, `apiUrl.js`                              |



## 📝 설치

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

├── front/
│ ├── public/ # Public static assets
│ ├── src/
│ │ ├── api/ # API configuration
│ │ ├── assets/ # Images and static media
│ │ ├── components/ # Reusable components
│ │ ├── redux/ # State management files
│ │ ├── user/ # User-specific components
│ │ ├── utils/ # Utility functions
│ │ ├── App.js # Frontend entry point
│ │ └── index.js # React entry point
│ ├── package.json # Frontend dependencies
│ └── tailwind.config.js # TailwindCSS configuration
