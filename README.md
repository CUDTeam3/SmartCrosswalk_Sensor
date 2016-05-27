#[2016_한이음] 3팀_IoT기반 국도 횡단보도 보행자 지킴이

아두이노를 사용하는 센서 제어 및 제어장치와의 통신 알고리즘.

## 개발 환경
> 개발 언어 : c/c++ for Arduino 1.6.9

> 개발 타겟 : Arduino Mega 2560 R3

> 개발 도구 : Eclipse Mars.2, Github, Arduino 

## 시작 전 확인사항
### Code Copyright
샘플코드들은 **저작권이 있는 자료**입니다. 하위 목록은 각 파트 대표 개발자이며 프로젝트 이외의 사용에는 문의가 필요할 수 있습니다. 
> 아두이노-LED 신호처리 : 정영주(vertex50@cu.ac.kr), 대구가톨릭대학교

> 아두이노-광수신 신호처리 : 최홍준(ghdwns7121@naver.com), 대구가톨릭대학교

> 아두이노-PC 신호처리 : 정세연(best0937@naver.com), 대구가톨릭대학교

### Ground Rule
1. 담당파트 개발시 각 개별 Branch(가지)를 생성하여 작업해주세요. 개인당 1개 생성입니다. 
2. 실제 운용 점검 후 검증된 작업에 한하여 회의 후 승인이 되었을 때 Master에 Merge(병합)요청을 해주세요. 
3. Comment는 **"개발하고 있는 알고리즘 이름_주번호.보조번호.작업번호"** 양식을 유지하며 번호의 증가조건은 아래와 같습니다.
  예) 버튼 전송 알고리즘_0.0.1
 * 주  번호 : 작업 결과물이 다른 담당자의 결과물과 병합되었을 때.
 * 보조번호 : 타 담당자들에게 동작되는 결과를 회의 때 검증하였을 때.
 * 작업번호 : 작업 결과물을 타 담당자의 검증 없이 올릴 때.
4. 소스코드를 제외한 문서들은 [Dropbox](https://www.dropbox.com/sh/7vmnmwyq8xp75xb/AADxzAP9nBhgIPdVGKtEdNQ4a?dl=0)에 있습니다
5. 소스코드 주석은 Eclipse 주석 표기법 아래 최소 코드 설명(요약이 아님), 인자, 반환값에 대한 설명은 필수입니다.
6. 타 작업자의 Branch에 있는 소스를 허락하에 수정하여도 됩니다. 단, Commentary는 꼭 갱신하여야 합니다.

### 개발자 도움말
1. 개발 도구인 Eclipse와 Git의 사용방법은 아래 링크에서 다운받으면 됩니다.

> EGit, Git for Eclipse : [다운로드](http://203.250.32.155:5000/fbsharing/lwCfWNUq)

2. 아두이노를 Eclipse로 개발하는 방법입니다. 문서는 완성되는 대로 업데이트 될 예정입니다. 

> 아두이노_이클립스연동 : [링크](http://playground.arduino.cc/Code/Eclipse)

## 맴버
멘토
+ 지도 멘토 : 윤정훈 멘토 (yoonjunghun@naver.com)
+ 서브 멘토 : 김유정 멘토 (bluehorn@cu.ac.kr)

멘티
+ (*)안광은 멘티 (yooer10@cu.ac.kr)
+ 정영주 멘티 (vertex50@cu.ac.kr)
+ 이성원 멘티 (lee12041993@cu.ac.kr)
+ 이민우 멘티 (dnj011@cu.ac.kr)
+ 이득희 멘티 (te03074@cu.ac.kr)
