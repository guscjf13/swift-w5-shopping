# swift-w5-shopping
모바일 5주차 쇼핑 저장소

1. make project
- git clone
- project 생성

2. make Product class
- 다른 model class들이 상속할 Product class 생성

3. Product class -> Storeitem class
- Product class를 StoreItem class로 변경
- StoreItems class 생성

4. make MainCollectionView
- MainCollectionView, MainCollectionViewCell 생성
- Storyboard를 통해 Auto Layout 적용


5. make NetworkManager class
- NetworkManager class 생성
- URLSession을 통한 통신
- 통신으로 받은 json data 파싱


6. connect parsed data, collectionView
- parsed data와 collectionView 연결
- section은 아직 미구현
![Simulator Screen Shot - iPhone SE (2nd generation) - 2021-02-02 at 22 12 29](https://user-images.githubusercontent.com/28801805/106605067-d0145480-65a3-11eb-8639-b8d34bc3b629.png)


7. resparate of view roles
- MainCollectionView, MainViewController 역할 재분배
- 접근제어제 재설정


8. make CacheManager, DownloadManager class
- CacheManager, DownloadManager class 생성
- 캐시 디렉토리에 없는 이미지 파일은 다운로드 후 출력
- 캐시 디렉토리에 있는 파일은 출력


9. embed navigation controller
- MainViewController에 네비게이션 컨트롤러 embed
- 셀 클릭시 StoreItem 객체 데이터 DetailViewController한테 전달
