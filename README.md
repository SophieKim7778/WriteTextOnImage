# WriteTextOnImage

1. 개요 & 요구사항 :  
  - 행사 진행 준비 시 50내지 100명 이상의 명찰을 만들 때 단순 반복 작업이 많아 개발하게 됨.
  
2. 사용 설명 : 
  - 필수 항목 : 명찰 배경 이미지가 될 '이름'과 '소속' 리스트가 입력된 엑셀 파일을 업로드
    * 줄바꿈은 가로 너폭에 맞춰 설정했으나, '^'표시로 강제 줄바꿈 가능
  - 선택 항목 : 기본 설정된 값 외에 폰트, 줄 간격, 좌우 패딩값, 위 패딩값 수정 가능 
  - 미리보기 기능 : 원본 이미지 그대로 미리보기 가능
  - pdf 파일 다운로드 : 각 이미지 당 한 페이지로 노출

3. 사용 오픈소스: 
  - jquery, bootstrap, jspfd, xlsx, webfont
  
4. 추후 수정사항 :
  - 이미지 용량과 크기에 따라 속도 이슈, 그에 따른 로딩바 구현 필요
  - 더 다양한 사용자 액션 테스트 필요
  - 미리보기 축소 기능 추가
