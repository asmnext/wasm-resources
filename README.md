# wasm-resources-cobol
WASM resources for COBOL, Portran, Pascal, and ADA (Korean)

## 개요

우리는 반세기 전 사용되던 컴퓨터 프로그래밍 언어(코볼, 포트란, 파스칼, 에이다 등)의 존재에 대해 학부 과정에서 배웁니다.

이 중 일부 언어는 신생 언어 뒤에 숨어 현재까지도 널리 사용하고 있습니다. 일부 파이선(Python)의 연산 라이브러리에는 포트란(Portran)이 사용됩니다.

60년대 프로그래밍을 대표하는 코볼(Cobol)은 2019년 COVID-19 상황으로 인해 발생된 미국의 국가 행정 수요를 감당하지 못해, 2020년 IBM은 대학가를 중심으로 코볼 교육을 다시 시작했습니다.

하지만 과거의 언어들은 최근의 언어가 제공하는 편의성과 시스템 호환성 모두에서 밀려나 있습니다. 그럼에도 최근의 언어와 그 생태계가 만족시키지 못한 많은 유형의 요구를 감당하고 있습니다.

여기서는 WebAssembly (일명 WASM)으로 최신의 시스템에서 과거의 언어를 사용하기 위한 자료를 정리해두었습니다. 

## COBOL

### cloudflare/cobweb

이 프로젝트를 사용하면 COBOL 프로그램을 웹어셈블리로 컴파일할 수 있습니다.

  * https://github.com/cloudflare/cobweb

### PORTRAN

### FORTRAN In The Browser

이 기사는 Portran(F90)을 웹어셈블리로 컴파일 하기 위한 툴체인(LFortran, Flang-7, F18, Dragonegg, AOCC 등)을 다룹니다.

  * https://chrz.de/2020/04/21/fortran-in-the-browser/


### Pascal

### FreePascal

아래 글들은 Pascal을 웹어셈블리로 컴파일 하기 위한 방법을 안내합니다.

  * https://wiki.freepascal.org/WebAssembly/Compiler

### Oz.Wasm

이와 반대로 Pascal로 짜여진 WASM 인터프리터가 존재합니다. 이것은 기존 Pascal 언어 사용자가 WASM의 특성을 이해하는데 도움이 될 수 있습니다.

  * https://github.com/marat1961/wasm

### ADA

### godunko/adawebpack

이 프로젝트를 사용하면 ADA 언어로 작성된 프로그램을 웹어셈블리로 컴파일 할 수 있습니다.

  * https://github.com/godunko/adawebpack
  * https://blog.adacore.com/use-of-gnat-llvm-to-translate-ada-applications-to-webassembly

## 문의

대한민국의 웹어셈블리(WASM) 연구팀인 어셈넥스트(AsmNext)는 COBOL, Portran, Pascal, ADA 등을 포함하여 컴파일러를 지원하는 과거형의 다양한 언어를 최신의 기술로 지원할 수 있습니다.

주저없이 연락주시기 바랍니다.

  * support@exts.kr (이메일)
  * https://catswords.re.kr/go/kakaoba (카카오톡 오픈채팅방)
