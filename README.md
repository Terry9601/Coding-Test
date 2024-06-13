**System Requirements**
1. Hardware Requirements ATM Device:
    Card Reader
    PIN Pad
    Cash Module (Cash Tray)
    Receipt Printer
    Network Connection (Internet connection for communication with bank system)
2. Software Requirements
    Operating System (OS):
      Windows
    Programming Language:
      C++
    Libraries and Frameworks:
      Standard C++ Library (iostream, unordered_map, string) 
    Development Tools:
      Integrated Development Environment (Visual Studio)
4. Network Requirements (Not Implemented) Communication with Bank System:
    Secure data transmission using security protocols (SSL/TLS) Connection with ATM Management System:
    Network connection for ATM status monitoring
    Software updates and remote diagnostic capabilities
**User Requirements**
**1. Functional Requirements**
    Card Insertion:
       The system must read card information when the user inserts a card into the ATM.
    PIN Input:
       Users should be able to enter their PIN number securely.
       Security should be maintained during PIN entry.
       After five consecutive incorrect PIN entries, the account should be locked. Account Selection:
       Users should be able to select the type of account (e.g., savings, checking).
    Balance Inquiry:
       Users should be able to check the balance of the selected account.
    Deposit:
       Users should be able to deposit money into the selected account.
       The balance should update after a deposit.
    Withdrawal:
       Users should be able to withdraw money from the selected account.
       The balance should update after a withdrawal.
       Withdrawal should be refused if the account balance is insufficient.
    Exit Options:
       Users should be able to exit operations at any time.
       They should return to the main menu or exit the system after completing operations.
       Selecting "Return to Main Menu" should return to the account selection screen.
2. Non-functional Requirements
  Security:
    User card information and PIN numbers must be encrypted.
    All communications must be protected using security protocols.
  Usability:
    The user interface should be intuitive and easy to use.
    On-screen instructions should be clear and understandable.
  Performance:
    Each operation should be processed quickly without delays.
    The system must maintain high availability.
  Scalability:
    The system should be designed for easy addition and modification of new features.
    Integration with the bank system and cash module should be straightforward.
  Maintainability:
    The code structure should be clear and modular for easy maintenance.
    Error messages should be clear and helpful for troubleshooting.
  Reliability:
    The system should be designed to minimize user errors.
    Important data should be handled to prevent loss.
3. User Scenarios
  Card Insertion Scenario:
    User inserts their card.
    The system reads the card information and prompts the user to enter their PIN.
  PIN Input Scenario:
    User enters their PIN.
    If valid, the account selection screen appears.
    If invalid, an error message is displayed and the user can retry entering their PIN.
    After five consecutive incorrect attempts, the account is locked and an error message is displayed.
  Account Selection Scenario:
    User selects the account type (savings, checking).
    Options for balance inquiry, deposit, and withdrawal are displayed based on the selected account type.
  Balance Inquiry Scenario:
    User selects the balance inquiry option.
    The balance of the selected account is displayed on the screen.
  Deposit Scenario:
    User selects the deposit option.
    They input the amount to deposit.
    The system deposits the amount into the account and displays the updated balance.
  Withdrawal Scenario:
    User selects the withdrawal option.
    They input the amount to withdraw.
    The system withdraws the amount from the account and displays the updated balance.
    An error message is displayed if the balance is insufficient.
  Exit Scenario:
    User intends to exit operations.
    They choose either "Return to Main Menu" or "Exit."
    Choosing "Return to Main Menu" returns to the account selection screen.
    Choosing "Exit" shuts down the system.
---------------------------------------------------------------------------------------------------------
**시스템 요구사항 (System Requirements)**
1. 하드웨어 요구사항 (Hardware Requirements)
  ATM 기기:
    카드 리더기
    PIN 패드
    현금 입출금 모듈 (현금 트레이)
    영수증 프린터
    네트워크 연결 (은행 시스템과의 통신을 위한 인터넷 연결)
2. 소프트웨어 요구사항 (Software Requirements)
  운영 체제 (OS):
    Windows
  프로그래밍 언어:
    C++
  라이브러리 및 프레임워크:
    표준 C++ 라이브러리(iostream, unordered_map, string)
  개발 도구:
    통합 개발 환경 (IDE) (Visual Studio)
3. 네트워크 요구사항 (Network Requirements)( 미구현)
  은행 시스템과의 통신:
    보안 프로토콜 (SSL/TLS)을 통한 안전한 데이터 전송
    ATM 관리 시스템과의 연결:
    ATM 상태 모니터링을 위한 네트워크 연결
    소프트웨어 업데이트 및 원격 진단 기능

**사용자 요구사항 (User Requirements)**
1. 기능 요구사항 (Functional Requirements)
  카드 삽입:
    사용자가 ATM에 카드를 삽입하면 카드 정보를 읽어야 합니다.
  PIN 입력:
    사용자가 PIN 번호를 입력할 수 있어야 합니다.
    PIN 번호 입력 시 보안이 유지되어야 합니다.
    PIN 번호가 5회 연속으로 틀리면 계좌를 잠급니다.
  계좌 선택:
    사용자가 계좌 유형 (예: 저축, 당좌)을 선택할 수 있어야 합니다.
  잔액 조회:
    사용자가 선택한 계좌의 잔액을 조회할 수 있어야 합니다.
  입금:
    사용자가 선택한 계좌에 금액을 입금할 수 있어야 합니다.
    입금 후 잔액이 갱신되어야 합니다.
  출금:
    사용자가 선택한 계좌에서 금액을 출금할 수 있어야 합니다.
    출금 후 잔액이 갱신되어야 합니다.
    계좌 잔액이 출금 금액보다 적으면 출금이 거부되어야 합니다.
  종료 옵션:
    사용자가 언제든지 작업을 종료할 수 있어야 합니다.
    작업 완료 후 처음 화면으로 돌아가거나 시스템을 종료할 수 있어야 합니다.
    "메인 메뉴로 돌아가기"를 선택하면 계좌 선택 화면으로 돌아가야 합니다.
2. 비기능 요구사항 (Non-functional Requirements)
  보안:
    사용자의 카드 정보와 PIN 번호는 암호화되어야 합니다.
    모든 통신은 보안 프로토콜을 사용하여 보호되어야 합니다.
  사용성:
    사용자 인터페이스는 직관적이고 사용하기 쉬워야 합니다.
    화면의 지침은 명확하고 이해하기 쉬워야 합니다.
  성능:
    각 작업은 지연 없이 신속하게 처리되어야 합니다.
    시스템은 고가용성을 유지해야 합니다.
  확장성:
    시스템은 새로운 기능 추가 및 변경이 용이하도록 설계되어야 합니다.
    은행 시스템과의 통합 및 현금 입출금 모듈과의 통합이 용이해야 합니다.
  유지보수성:
    코드 구조는 명확하고 모듈화되어 있어 유지보수가 용이해야 합니다.
    오류 메시지는 명확하고 문제 해결에 도움이 되어야 합니다.
  신뢰성:
    시스템은 사용자의 오류를 최소화하도록 설계되어야 합니다.
    중요한 데이터는 손실되지 않도록 처리되어야 합니다.
3. 사용자 시나리오 (User Scenarios)
   카드 삽입 시나리오:
    사용자가 카드를 삽입합니다.
    시스템이 카드 정보를 읽고 사용자에게 PIN 번호 입력을 요청합니다.
  PIN 입력 시나리오:
    사용자가 PIN 번호를 입력합니다.
    PIN 번호가 유효하면 계좌 선택 화면이 나타납니다.
    PIN 번호가 유효하지 않으면 오류 메시지가 표시되고 다시 PIN 번호를 입력할 수 있습니다.
    PIN 번호가 5회 연속으로 틀리면 계좌가 잠기고 오류 메시지가 표시됩니다.
  계좌 선택 시나리오:
    사용자가 계좌 유형 (저축, 당좌)을 선택합니다.
    선택한 계좌 유형에 따라 잔액 조회, 입금, 출금 옵션이 표시됩니다.
  잔액 조회 시나리오:
    사용자가 잔액 조회 옵션을 선택합니다.
    선택한 계좌의 잔액이 화면에 표시됩니다.
  입금 시나리오:
    사용자가 입금 옵션을 선택합니다.
    입금할 금액을 입력합니다.
    시스템이 금액을 계좌에 입금하고 새로운 잔액을 표시합니다.
  출금 시나리오:
    사용자가 출금 옵션을 선택합니다.
    출금할 금액을 입력합니다.
    시스템이 계좌에서 금액을 출금하고 새로운 잔액을 표시합니다.
    잔액이 부족하면 오류 메시지가 표시됩니다.
  종료 시나리오:
    사용자가 작업을 종료하려고 합니다.
    사용자는 "메인 메뉴로 돌아가기" 또는 "종료" 옵션을 선택합니다.
    "메인 메뉴로 돌아가기"를 선택하면 계좌 선택 화면으로 돌아갑니다.
    "종료"를 선택하면 시스템이 종료됩니다.
