# Reversing_PE
본 문서는 **pe파일 리버싱 스터디** 를 위한 레포 설명서입니다.
아래 내용을 읽고 폴더를 알맞게 설정하세요.


### 작업순서와 설명
1. Reversing_PE 레포 하위에 {Your_github_nickname} 폴더를 생성합니다.
   > 예시: Reversing_PE/MJ-bin
2. 그후 본인 폴더 하위에 note 폴더와 pefile 폴더, peview 폴더를 각각 생성합니다.
3. note 폴더는 실습을 통해 배운것, 구글링을 통해 알게된 것 등을 md 파일로 작성하여 업로드합니다.
4. pefile 폴더에는 실습과 워게임에서 진행했던 PE파일들을 업로드합니다. 이때 하위폴더로 구분짓는건 자유입니다.
5. peview 폴더는 생성만 해두고 추후 각자 깃허브 레포에서 개발한 peview 도구를 서브모듈로 포함합니다.(폴더 생성만)

> 별도의 문의, 스터디에 도움이 되는 정보(워게임, 라이트업, 논문, 좋은 기술블로그 등), 그외 TMI 등은 Issues 에 등록해주세요!

### 디렉토리 구조 예시
```sh
Reversing_PE
│
├─{nickname1}
│  ├─note
│  │  ├─note1.md
│  │  └─note2.md
│  ├─pefile
│  │  ├─pe1.exe
│  │  ├─pe1_db.dd32
│  │  ├─pe2.exe
│  │  └─pe2_db.dd64
│  └─peview
│
├─{nickname2}
│  ├─note
│  │  ├─note1.md
│  │  └─note2.md
│  ├─pefile
│  │  ├─pe1.exe
│  │  ├─pe1_db.dd32
│  │  ├─pe2.exe
│  │  └─pe2_db.dd64
│  └─peview
:
:
└─README.md
```
