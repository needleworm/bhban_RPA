# 인스타그램에서 특정 태그가 달린 게시물 모조리 좋아요 누르기

인스타그램을 돌면서, 특정 해시태그가 입력된 게시물을 모조리 좋아요 누르는 자동화입니다.

## 사용 방법
> python main.py <ID\> <PS\> <TAG\> <like_file\> <red_like_file\> <NUMBER\>


<ID\> <PS\>에는 ID와 비밀번호를 입력합니다.

<TAG\>에는 검색할 태그를 입력합니다.

<like_file\>에는 하얀 좋아요 아이콘을 캡쳐한 파일을 적어줍니다.

<red_like_file\>에는 빨간 좋아요 아이콘을 캡쳐한 파일을 적어줍니다.

<NUMBER\>에는 반복 회수를 입력합니다. -1을 입력하면 사용자가 중단할 때까지 작업을 계속 합니다.


## 필요 라이브러리
PyAutoGui 라이브러리를 설치해야 합니다.

> pip install pyautogui

