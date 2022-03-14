# ReactBuild_Test

vscode 터미널에서
git remote add origin https://github.com/Redchrysanthemum/ReactBuild_Test 
로 repository를 추가한뒤

package.json 파일에 "scripts"단에서
"deploy": "gh-pages -d build"
와
"predeploy": "npm run build" 
를 추가시켜 
npm run deploy 
를 실행시켜줍니다.

그러면 윗 주소로 코딩한내용이 Published 됩니다
