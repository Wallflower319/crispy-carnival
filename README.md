6.8.1 자동 이동 옵션
브랜치를 생성과 이동 명령을 두번 입력하는것은 불편하기 떄문에 깃에서는 둘을 한번에 처리하는 -b옵션을 사용하여 생성과 이동을 한번에 가능합니다.

<img width="588" alt="스크린샷 2022-10-11 19 54 05" src="https://user-images.githubusercontent.com/102798520/195075814-5fa3cdbf-fb89-4034-805f-088001a416b1.png">

6.8.3 HEAD를 활용한 이동
체크아웃을 하려면 복잡한 해시키가 필요하기 떄문에 입력 오류가 생길 확률이 높아집니다 그래서  HEAD포인터를 활용하여 체크아웃이 가능합니다.

<img width="476" alt="스크린샷 2022-10-11 20 15 27" src="https://user-images.githubusercontent.com/102798520/195076149-19282ec8-acf3-46ba-9b47-0a3d1a6612c6.png">

6.8.4 돌아오기
만약 과거의 커밋으로 체크아웃 한 경우에 다시 현 시점으로 돌아와야 합니다. 현재 시점으로 돌아가는 방법은 대시(-)를 사용하여 돌아가면 됩니다.

<img width="482" alt="스크린샷 2022-10-11 20 16 54" src="https://user-images.githubusercontent.com/102798520/195076358-2a8fe81e-10b5-4aaf-a59f-d9bdaf40eaf4.png">

만약 현재로 돌아가야하는데 여러번 돌아가야한다면 대시(-)대신 브랜치 이름을 입력하면 됩니다.

<img width="405" alt="스크린샷 2022-10-11 20 18 08" src="https://user-images.githubusercontent.com/102798520/195076712-3fdf25b8-c47b-4b9f-8886-9ebadeec2893.png">

6.10.1 브랜치 푸시
깃의 푸시는 저장소의 파일과 브랜치 정보와 커밋까지 모두 전송합니다.
처음 커밋과 브랜치를 푸시하려면 업스트림 설정이 필요합니다. 원격 저장소 연결만으로 업스트림이 자동으로 설정되지는 않기 떄문입니다.그래서 처음에는 수동으로 트래킹 브랜치와 업스트림을 설정 해야합니다.

<img width="652" alt="스크린샷 2022-10-11 20 20 04" src="https://user-images.githubusercontent.com/102798520/195076923-3c010da7-6716-400b-ba1e-5dadadd9b9e5.png">

6.11.4 리모트 브랜치를 삭제하는 방법
원격 저장소에 저장 되어 있는 브랜치를 삭제하려면 먼저 삭제 명령[$ got push origin —delete 리모트브랜치이름]을 푸시 해야 합니다 .

<img width="545" alt="스크린샷 2022-10-11 20 21 28" src="https://user-images.githubusercontent.com/102798520/195077221-903757f5-87a7-4f40-ab0b-3ed4c7066ff9.png">
