# incognito-taskbar
작업 표시줄에 크롬 시크릿모드 고정하기 / pinning Chrome Incognito mode on Windows Taskbar

## How to use

1. 다운로드한 Chrome-Incognito 폴더를 C 드라이브에 저장합니다.
2. 폴더 안의 "Chrome Incognito" 바로 가기를 우클릭 한 뒤 "작업 표시줄에 고정" 을 클릭하시면 됩니다!

## 구동 원리

크롬 브라우저의 바로가기 경로 뒤에 '--incognito'를 붙이는 것으로 Incognito mode를 바로 실행할 수 있습니다. 
하지만 해당 태그를 붙이더라도 동일한 프로그램을 작업 표시줄에 중복하여 추가할 수 없기 때문에, 태그를 추가한 바로가기를 실행하는 간단한 배치 파일을 작성했습니다.

그런데 짜잔! 배치 파일은 어째선지 작업 표시줄에 추가할 수 없네요. 어쩔 수 없이 배치 파일을 실행하는 바로가기를 하나 더 작성했습니다.
해당 바로가기에 아이콘을 추가하고 출력되는 창의 크기를 눈에 띄지 않게 조절하면 끝입니다!

(혹은 'C:\Users\UserName\AppData\Roaming\Microsoft\Internet Explorer\Quick Launch\User Pinned\TaskBar' 폴더 안의 작업 표시줄 관련 내용을 직접 수정해도 됩니다.)
