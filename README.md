# liebespaar93.github.io
git 블로그를 위한 레포입니다.
d
## 협업을 위한 준비
## vscode 플러그
### [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- 코드 스타일 에디터
	- 사용목적 : 협업의 일정한 코드 스타일 유지 하기위해
	- 참고 : http://editorconfig.org

### [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
- 깃 관리
	- 사용목적 : git network를 한눈에 보고 확인하기위해

### [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- 실시간 서버
	- 사용목적 : 로컬의 환경에서 테스트하기 위해

###  [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- vscode 파일 및 폴더 아이콘
	- 사용목적 : 파일 및 폴더아이콘을 동일시 하기 위해

### [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
- vscode markdown Mermaid 뷰어
	- 사용목적 : 마크다운안에 다이어그램 작성 가능

### [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
- npm import 자동완성
	- 사용목적 : 설치된 module을 자동 완성 기능을 쓰기위해
### [Dotenv Official +Vault](https://marketplace.visualstudio.com/items?itemName=dotenv.dotenv-vscode)
- env 자동완성
	- 사용목적 : env 목록 확인 및 자동완성
	- 보류 : 확인 안됨
### [ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
- react snippets
	- 사용목적 : 파일 틀 코드 만들기용
	- rfcp 예시
		```
		import React from 'react'
		import PropTypes from 'prop-types'

		function $1(props) {
			return <div>$0</div>
		}

		$1.propTypes = {}

		export default $1
		```

## git 설정
### .gitconfig
- 상태파일 정의
### .gitmessage
- 커밋 형식 맞추기  
	``` git commit ``` 으로 작성하여 vi 설정에서 확인후 수정하기
### .github/ISSUE_TEMPLATE/***.md
- 이슈 형식 맞추기
	```
	---
	name: "[이모티콘] 이슈 이름"
	about: 설명을 적는다
	title: "[YYYYMMDD] 타이틀 - 제목"
	labels: ''
	assignees: liebespaar93

	---

	### 내부 내용

	- 제목 : 
	- 번호 : 
	- 설명 : 
	- 링크 :
	```
### git GPG 
- 커밋 인증 사인하기
- 주소 : [Github Doc GPG](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits)
- mac : [GPGtools](https://gpgtools.org/) !주의 safari에서만 다운가능
- window : [gnupg](https://www.gnupg.org/)
### git LFS 
- 대용량 파일 업로드 
- 주소 : [Github Doc LFS](https://docs.github.com/ko/repositories/working-with-files/managing-large-files/installing-git-large-file-storage)
- ❌ 사용 안함

## 코드 정리
- mac  
	``` option + shift + f ``` 버튼으로 코드 정리
- window  
	``` alt + shift + f ``` 버튼으로 코드 정리


## 참고 사이트
### 이모지
- https://github.com/carloscuesta/gitmoji
