# 작심하루 : 하루에 하나만 열심히 하자

### 1일차 (Day 1)
- **주요 작업**:
  - `OneDayView` 페이지 개발
    - 사용자 인터페이스(UI) 구성: 날짜 선택, 카테고리 표시, 할 일 추가 기능
   
  - `MonthView` 페이지 개발
    - 월별 달력 뷰 구현
    - 날짜 선택 시 상호작용 기능 추가
 
### 2일차 (Day 2)
- **주요 작업**:
  - `CoreData` 모델 최적화
    - User, Category, Status, Time 엔터티 설계 및 최적화
    - 각 엔터티 간의 관계 설정 및 데이터 무결성 보장
   
### 3일차 (Day 3)
- **주요 작업**:
  - `AddCategoryView` 페이지 개발
    - 새로운 카테고리를 추가하는 기능 구현
    - 사용자 입력을 받아 CoreData에 카테고리 엔터티 저장
    - 저장 후, 이전 화면으로 돌아가는 네비게이션 처리 추가
   
  - `OneDayView` 페이지 개발
    - CoreData에 저장된 일정을 화면에 불러오기
  
### 4일차 (Day 4)
- **주요 작업**:
  - `CategoryManagerView` 페이지 개발
    - 카테고리 목록을 표시하고, 카테고리를 추가 및 편집하는 기능 구현
    - 카테고리 편집 및 삭제 기능 추가 `EditCategoryView`
    - 새로운 카테고리를 추가하는 모달 뷰 `AddCategoryModalView` 구현
    - 사용자 인터페이스 최적화 및 사용자 경험 개선
   
  - `OneDayView` 페이지 개발
    - CoreData에 수정 또는 삭제된 결과 View 업데이트
   
### 5일차 (Day 5)
- **주요 작업**:
  - `ClockTimeView` 페이지 기본 구조 개발
    - 알림 설정 UI 구현
    - 저장된 알림 시간 목록 표시
    - 알림 시간 추가 기능 구현
    - 알림 권한 요청 기능 추가
    - 알림 시간 삭제 기능 구현 및 CoreData와 연동
   
### 6일차 (Day 6)
- **주요 작업**:
  - `TimePickerView` 모달 뷰 개발
    - 사용자가 시간을 선택하고 알림을 설정할 수 있는 UI 구현
    - AM/PM, 시, 분 선택 기능 추가
    - 중복 시간 방지를 위한 중복 체크 기능 구현
    - 새 알림 시간 저장 및 기존 알림 시간 수정 기능 구현
    - CoreData와 연동하여 알림 시간을 관리하는 기능 추가
   
### 7일차 (Day 7)
- **주요 작업**:
  - 알림 기능 최종 구현 및 테스트
  - UNUserNotificationCenter를 사용하여 알림 예약 및 취소 기능 추가
  - 선택된 시간에 맞춰 할 일 알림 예약 기능 구현
  - `ClockTimeView` 와 `TimePickerView` 간의 데이터 흐름 최적화
  - 알림 메시지 커스터마이징 기능 추가 (buildNotificationBody 함수 구현)
  - 모든 기능에 대한 통합 테스트 및 디버깅

### 8일차 (Day 8)
- **주요 작업**:
  - 일정에 대한 수정, 삭제 기능 추가
 
### 9일차 (Day 9)
- **주요 작업**:
  - 일정 완료 시 해당 날짜의 UI 디자인 변경
 
## To-Do List
- [x] `OneDayView` 페이지 구현
- [x] `MonthView` 페이지 구현
- [ ] CoreData 모델 최적화
- [x] 사용자 인증 기능 추가 -> 사용자마다 기기의 고유의 아이디 사용으로 변경
- [ ] 앱 아이콘 디자인
- [x] 알림 기능 구현
- [x] 테스트 데이터 생성 후 디버깅
- [ ] 날짜별로 할 일을 관리할 수 있는 뷰를 구현
- [x] 일정에 대한 수정,삭제 페이지와 기능 구현
- [ ] 특정 버튼이 초기에 눌리지 않는 버그 수정
- [ ] 해당 날짜에 대해서만 일정 나타내기
- [ ] 일정의 대한 체크 박스가 모두 체크 되면 해당 날짜 UI 디자인 변경
- [ ] 추후 추가 예정
