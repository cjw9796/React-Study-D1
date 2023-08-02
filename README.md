## 로컬 폴더명 : my-app

만약에 node_modules 가 없을 경우
npm i 입력 후 npm start 시작
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

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

### React 정리 
nodejs : 패키지 관리자 (리액트 이외의 다양한 패키지 설치 가능)
    npx : 최신 패키지 설치이기 때문에 초반에 폴더 만들어줄 때 사용하는 명령어 
        npx create-react-app 폴더명
        npm 전반적으로 build, test, start, install 등 다방면으로 사용하는 명령어  
        프로젝트 시작하는 명령어 : npm start 
        추가적으로 필요한 패키지 설치하는 명령어 : npm install 패키지명
        npm start를 종료하고 다시 실행시키고 싶으면
        터미널에서 ctrl + c를 여러번 눌러주면 된다. 

    package.json : 간략한 사용설명서 
    package-lock.json : 자세히 적힌 사용설명서 
    README.md : 프로젝트에 대해 사람이 전반적으로 설명하는 공간 
    .gitignore : 깃허브에 파일을 업로드 할 때 업로드 하지 말아야될 이름이나 확장자를 작성한다. 

### 동작에 대해서 작성 
리액트는 초반에 index.html 파일만 바라본다. 
index.js 에서 사용할 javaScript 파일을 불러온다. 
그다음 App.js와 같은 파일을 만들어서 컴포넌트를 작성한다. 
파일의 이름은 개발자의 자유이다. 

### 폴더구조 
>node_modules : 패키지 여기안에 react가 들어있다. 
>public : 가장 처음에 보여지는 폴더 
>src : 우리가 원하는 코드를 작성하는 폴더  

### 리액트의 장점 
    Virtual DOM이란? -> "DOM을 추상화한 가상의 객체"
    SPA(Single Page Application) -> 단일 페이지로 처리 
    (index.html) 
    웹으로 모바일 앱도 만들 수 있다. 
    JSX(JavaScriptXML) : 우리가 작성한 코드를 컴퓨터에 맞게 변환해준다. 

### 컴포넌트 작성방법 
function 이름 {
    스크립트 
    const [기본값, 변경될 값] = 초기기본값;
    const 동작할 이름 = () => {
        변경될 값
    };
    ### 만약에 input 처럼 넣어줘야 하는 값이 있을 경우 
    const 동작할 이름2 = (event) => {
        변경될 값(event.target.value)
    };
return (
    <div>{기본 값}내용을 채워준다.</div>
);
}
export default 이름; 

"# React-study"  
"# React-study"  
"# React-study" 
