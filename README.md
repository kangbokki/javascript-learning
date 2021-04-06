# javascript-learning


### 개요


### 구성



### 목차

#### [?.semver - Semantic Versioning (유의적 연산자)](#semver)















### ?.semver<a name='semver'></a>  
> major.minor.patch-identifier  
> 0.x.x <- 개발 중  
> 1.x.x <- 릴리즈  
> ex) 1.2.3-alpha  
  
* rule
  - 이전버전 호환X &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-> major up
  - 이전버전 호환O 기능 변경O -> minor up
  - hotfix &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-> patch up
 
* ^(캐럿)  
 minor 영역 허용
* ~(틸드)  
 patch 영역 허용
 
+ [TEST](https://semver.npmjs.com/)



