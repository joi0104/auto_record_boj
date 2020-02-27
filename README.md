# auto_write



- auto_write는 푼 백준문제를 백주삼 스프레드 시트에 자동으로 기록해파이썬 프로그램입니다.

- 로컬 디렉토리에 존재하는 코드파일의 파일명을 기반으로 기록됩니다.
- 추후에는 크롤링을 통해서 백준 사이트의 제출을 기반으로 기록되도록 확장 할 예정입니다.
- 또한 시트 선택 또한 자동으로 선택되도록 확장 할 예정입니다.

- 반드시 코드파일의 파일명에 `1234` `boj1234` `b1234`와 같이 백준 문제의 번호가 존재해야 합니다.
- 현재 지원하는 파일 확장자는 `.py` `.cpp` `.c` `.java` 입니다.



## usage



- setup json 파일을 열어주세요.
- path 값에 기록될 디렉토리의 path를 입력해주세요.
- spreadsheet_url 값에 기록할 스프레드 시드의 url을 입력해주세요.
- worksheet 값에 기록할 시트 명을 입력해주세요.
- my_column 값에 기록할 열 명을 입력해주세요.
- 설정을 완료했습니다. 
- test.py를 실행하여 새로 푼 문제들을 시트에 기록해주세요.

