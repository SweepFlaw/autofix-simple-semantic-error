# autofix-simple-semantic-error
### Computer Science Graduation Project in Korea University

## Object
- 프로그램 코드 내에서 발생하는 사소한 semantic error를 자동으로 탐색하고 고치는 방법을 제시하고 프로그램을 제작한다.

## Target
- Codeforce 사이트에서 문제를 풀기 위해 제출한 코드 데이터를 수집하여 그 중 테스트를 통과한 코드와 그 코드 이전에 제출한 코드 중 사소한 semantic error로 통과하지 못한 코드 데이터를 골라내고 이를 자동으로 수정하는 것을 목표로 한다.
- ## 특징
  - 인위적이지 않은 실제 프로그래머가 실수한 코드이다.
  - 제출시간이 기록되어있어 실제 수정에 걸린 시간을 알 수 있다.
  - 제출한 코드 내역이 전부 있어 어떠한 과정으로 수정을 거쳤는 지 알아낼 수 있다.

## Relative Repository
- ### [Crawl and Diff](https://github.com/SweepFlaw/get-codeforce)
- ### [c++ lex and parse](https://github.com/cushionbadak/cppfileLex)
- ### [Get changable variable list](https://github.com/SweepFlaw/VarSubsCandListGenCpp)
- ### [Autofix program](https://github.com/SweepFlaw/CppSynth)