# Artificial Communicator Programme(A.C.P.)

## Background

기술의 발달이 일반인들에게 편의와 자유를 더 효율적으로 제공하기 위해서는 일반인들이 사용하기 편해야 한다.

for efficiently providing confidence and free to people, it is confident to use by people.


사람의 가장 본질적 특징 중 하나는 바로 언어이다.

Human's essential factor is language.


따라서 기술과 로봇이 언어를 이해하고 처리하고 생산할 수 있어야 한다.

Thus, Technology and Robot should comprehend language and speech it.


언어학 이론의 결과를 일일이 코딩으로 구성하는 연역적 접근만으로는 프로그래밍상 언어 구현에 한계가 있었다.

Deductive approach in programing natural language was limits. 


신경망을 구성하고, 언어 자료를 입력하는 것은 언어 구현에 어느 정도 성과가 있으나 사람이 완전히 이해하기가 힘드므로 활용에 어려움이 있다.(자료 조사 필요)

Inductive method is trouble for human to comprehend result of program constructing artificial neural network.


신경망을 통한 귀납적 구성만으로는 정보 처리에 많은 자원이 소비된다.(자료 조사 필요)

This method need excessive plenty of resource in coumputer. 


언어학 이론을 컴퓨터 프로그램에 직접 구현하는 것이 아니라, 컴퓨터 프로그램이 언어 규칙을 스스로 구성할 수 있도록 한다.

I want to make program to construct itself Linguistic principle.


컴퓨터가 구성하는 언어 규칙을 인간(사용자)이 이해할 수 있는 형태가 되도록 한다.

I want to make program that human understand result of artificial language acquisition.

## Goal

1. 언어 표현을 입력 받았을 때, 자동으로 문장 규칙을 만들어주는 프로그램을 만든다.

1. product programe to automatically make gramatical rule, when computer input language message

2. 언어 표현을 입력 받았을 때, 자동으로 사전을 만들어주는 프로그램을 만든다.

2. Automatically creating dictionary program When it get language message.

3. 언어 표현을 입력 받았을 때, 자동으로 특정 맥락 정보를 만들어주는 프로그램을 만든다.

3. Automatically program creating context information matrix , when it get language message.

특정 맥락에 따라 적절한 언어 표현을 하는 프로그램을 만든다.

## 기본 아이디어

1. 인간의 언어 습득 단계를 프로그래밍으로 구현한다.

   - 사용자가 일일이 언어 규칙을 만들지 않고, 프로그램이 스스로 언어 규칙을 만들어 가도록 한다.
  
2. 입력 자료는 언어 자료로 한정되어야 한다. 그 범위는 사용자가 한정해준다.

3. 언어 규칙은 언어 보편적인 변형생성문법, HPSG를 반영한다.

   - 언어 발달 과정에는 변형생성문법을 사용한다.
   - 언어 발달이 어느 정도 고착화되면 HPSG를 사용한다.
  
4. 언어 자료를 입력한다.

5. 언어 자료(대개 문장 단위)들을 계열관계와 통합관계에 따라 분석한다.

   - 2개 이상의 언어 자료를 비교하여 계열 관계에 따라 언어 단위를 추출한다.
  
   - 추출된 언어 단위들의 통합 관계를 추출한다.

   - 단어 수준의 언어 정보는 HPSG 및 

6. 가네의 학습 단계(변별, 군집화 등)를 프로그래밍에 반영한다.

7. 정보 처리와 저장의 자원을 효율적으로 활용한다.

   - 언어는 되도록 씨(C), 씨피피(CPP)를 사용한다.
   - 메모리 사용은 최소화한다.
   - 언어 처리는 텍스트 파일의 입출력

## 단계

언어 텍스트를 읽고 자동으로 (형태소, 단어, 구, 문장, 텍스트 등) 언어 단위를 분류하는 프로그램을 개발한다.

언어 텍스트를 읽고 자동으로 (형태소, 단어 등의) 사전을 만드는 프로그램을 개발한다.

언어 텍스트를 자동으로 언어 규칙을 생성하는 프로그램을 개발한다.

## 참고자료
