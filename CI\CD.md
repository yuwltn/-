# CI(Continuous Integration)
> 빌드/테스트 자동화 과정
<img src="https://github.com/yuwltn/yuwltn/blob/main/CI_img.png" width="370" height="300"> 

### 지속적인 통합
새로운 코드 변경 사항이 정기적으로 빌드 및 테스트 되어 공유 레포지토리에 통합하는 것이다.
<br><br>
### CI가 왜 필요할까?
매번 개발자가 코드를 수정하고 빌드와 테스트를 하고 배포까지 한다면 상당히 많은 시간이 소요된다. 
여러명의 개발자가 동시에 애플리케이션 개발과 관련된 코드 작업을 할 경우 서로 충돌할 수 있는 문제를 해결할 수 있다.<br>
커밋할 때마다 빌드와 일련의 자동 테스트가 이루어져 동작을 확인하고 변경으로 인해 문제가 생기는 부분이 없도록 보장한다.
<br><br>
### 필요한 환경 조건
* 다수의 개발자가 형상관리 툴(- Git, SVN 등)을 공유하여 사용하는 환경<br>
  공유 레포지토리에 쌓인 수많은 commit들을 기능별로 빌드/테스트 /병합 까지 하려면 번거롭기 때문에
  이런 상황에서, 자동화된 빌드&테스트는 원천 소스코드의 충돌 등을 방어하는 Benefit을 제공할 수 있다.
* MSA(Micro Service Archietectuire) 환경
  MSA는 최근 IT 업계에서 붐처럼 떠오르고 있는 아키텍처 모델로 작은 기능별로 서비스를 잘게 쪼개어 개발하는 형태이다.

# CD(Continuous Delivery & Continuous Deployment)
> 지속적인 서비스 제공 & 지속적인 배포<br>
> Continuous Delibery : 공유 레포지토리로 자동으로 release 하는 것<br>
> Continuous Deployment : Production 레벨까지 자동으로 deploy 하는 것

소프트웨어가 항상 신뢰 가능한 수준에서 배포될 수 있도록 지속적으로 관리하는 것이다.
<br><br>
## CI/CD 종류
* Jenkins
* CircleCI
* TravisCI
* Github Actions
* etc
