# FINAL_PROJECT 0802~0904
  웹 기반 텍스트 게임입니다. 아래는 날짜별로 한 것을 정리.<br><br>
  
  #### 0802 - CHAT GPT API 연결 시도

  #### 0803 - API기능 연결 완료. 홈에서 GAME 버튼 누른후 닉네임 받는 페이지까지만 구현
  
  #### 0804 - API를 JAVA에서 처리하던걸 JS로 변경함 - 이유는 AJAX통신을 JS를 통하는게 더 간단하며 Java를 걸칠 이유가 없다고 생각함.

  #### 0805/0806 - GPT AI 기반으로 텍스트게임을 구현시도중.

  #### 0807 - 구현시도중 텍스트를 찍고 버튼만드는거까진 가능 하지만 AI와의 상호작용으로인한 변수를 다 처리하는건 <br> 아직 내 단계에선 불가능하다고 생각이 들음. (일단 게임이 생각한대로 흘러가지않을뿐더러 너무 급조스럽게 끝남.) <br> AI 텍스트 게임을 철회.
  
  #### 0808 - 게임 로직 전체적으로 짜기로 계획 수정하고 만들어진 SCENE 객체를 통해 텍스트 찍기까지 구현.
 
  #### 0809 - SCENE 시나리오 추가와 진행하면서 전부 골라야 넘어가는것과 하나만 골라도 되는 시스템 추가.
 
  #### 0810 - 전체적인 SCENE 시나리오 추가 후 단서 찾는 게임(find_*) 만들기 시작.
  
  #### 0811/0812 - 단서 찾는 게임(find) 완료.
  
  #### 0813 - 텍스트를 주구장창 찍어내는건 가독성에서 불편하다고 느껴 이미지 추가후 대화 형식의 기반으로 바꿀 예정. 전체적인 UI 작업함.
  
  #### 0814 - 대화 형식의 기반으로 바꿈. 하지만 너무 빨리 바뀌는거 같아 읽기 불편 , 엔터를 눌러 진행할수있도록 전체 함수 수정
  
  #### 0815 - 단서를 다 찾고 난 이후의 단서를 이용한 미니게임(PROVISO) 구상 후 UI 작업
  
  #### 0816/0817 - 미니게임(PROVISO) 완성
  
  #### 0818 - SCENE을 조금 더 세분화하여 스토리 수정 및 로딩 기능 구현
  
  #### 0819 - ENDING SCENE전 까지 SCENE 구성 완료. 마지막 미니게임인 쫓아가서 잡는 형식의 게임을 만들고싶은데 아직 구상중.

  #### 0820 - 전체적인 마지막 미니게임(runWigoAndEmily) 구상 완료<br> CANVAS를 통해 움직임. 사진은 픽셀아트로 그려서 넣을예정(임시로 1개만듬) <br>  전체적인 박물관 이미지도 픽셀로 찍어서 충돌하면 못움직이도록 함수 구현해야할듯.<br>
  
  #### 0821 - 픽셀 LEFT , RIGHT , PRONT 제작 뒷면만 만들면됨 움직임 더 자연스럽게 구현함.

  #### 0822 - 샘플 배경넣기 완료,현재 플레이어 움직임(90%)과 배경 구현중

  #### 0823 - 픽셀 상하좌우 다 완성함. 현재 게임 캐릭터 중앙 배치 이후 맵 제작중.
  
  #### 0824/0825 -  맵 제작 완료후 캐릭터를 자유롭게 이동에서 중앙 배치 이후 움직임 구현 완료. 현재 맵에 그려진것과 같이 충돌함수 구현중. 
  
  #### 0826 - 충돌 함수 구현 완료.<br> 충돌 함수를 구현하니 처음에 그냥 부딪히면 아예 낑겨서 못움직이는 상황이 됨 거기서 그냥 값을 빼줬더니 <br> 거꾸로 움직이면서 맵밖으로 나가버림 그래서 함수를 키를 눌렀을때 충돌을 미리 감지하게 바꾸니 잘됨.<br>원래 있던 GAME내로 합침.<br>

  #### 0827 - 맵을 하나 더 만들고 그에 대한 충돌 레이어 , 맵 이동 기능 -> runWigoAndEmily 거의 완성(99%)

  #### 게임 완성
  </ul>


