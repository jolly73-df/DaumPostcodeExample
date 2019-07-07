# DaumPostcodeExample
Daum 우편번호 서비스 안드로이드 샘플

http://postcode.map.daum.net/guide

위 주소에서 제공하는 다음의 우편번호, 주소 검색 서비스를 안드로이드에서 액티비티로 분리하여

사용 예를 만들어 본 것입니다.


2019.7.8  수정

 - 요즘 버전의 안드로이드 스튜디오에서 바로 컴파일, 실행 되도록 프로젝트를 다시 작성했습니다.
   sdk버전, 빌드툴 등의 정보가 변경되었습니다.

 - 보안관련 일부 수정이 있었습니다.
   DaumPostcodeExample\app\src\main\assets\daum.html 파일을 github로부터 직접
   http://cdn.rawgit.com/jolly73-df/DaumPostcodeExample/master/DaumPostcodeExample/app/src/main/assets/daum.html
   와 같이 rawgit.com을 통해 읽어오던 것을 http://www.inspond.com/daum.html 로 바뀌었습니다.
   또한 또한 http 소스로부터 파일을 읽어오기 위해 AndroidManifest.xml 파일의 <application> 부분에 android:usesCleartextTraffic="true" 항목을 추가 하였습니다.
   현재 daum에서 js소스를 https로 서비스 하지 않는것 같습니다.
   이 주소는 동작 확인용 샘플일뿐이며, 실제로 사용하실때에는 자신만의 웹 서버에 올려 사용해 주세요.
   트래픽이 많아지면 이 파일은 삭제될 것입니다. 
