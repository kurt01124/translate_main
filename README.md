# translate_main



## push.sh

`$ ./push.sh {branch name} "{commit message}"`



## 구조

#### Directory - component :

- [ ] translate - paper2string : 논문 pdf에서 string만 추출하고, 번역하기 적합하도록 편집하는 기능

- [ ] translate - paper2image : 논문 pdf에서 이미지를 추출하고, 어느 위치에 들어가야하는지 확인하는 기능

- [ ] translate - web : 최종 출력물을 html로 변환하는 기능

- [ ] translate - paper2math : 논문 pdf에서 수식을 확인하고, 이미지로 변경 후 어느 위치에 들어가야 하는지 

  ​                                             확인하는 기능

#### File - makeObj.py :

- [ ] 여러개의 component가 들어가고 실행 순서를 정하는 Object를 만드는 기능

#### File - main.py

- [ ] makeObj를 이용하여 여러가지 Object를 만들고, 해당 Object들의 실행순서를 정하는 기능
- [ ] Input pdf와 출력 결과를 관리하는 기능

