# InheritanceProblem

## 과제

사원의 종류는 다음과 같다 

- 일반 사원
- 정규직 사원(연봉 1억2천)
- 파트타임 사원(시간당 25,000)
- 영업직 사원 (기본연봉에 영업실적 5%)

사원 클래스는 **부서** 객체를 가지고 있고, **부서** 종류는 다음과 같다 Department

- 개발팀
- 영업팀
- 고객대응팀
- 사무직

사번을 동적으로 생성하는데 **동반객체(UUID 활용)** 를 이용하여 생성한다 
- 자바의 static

반드시 EmployeeManager 클래스를 main에서 호출하여 각각의 임금을 계산하도록 한다

구현해야 할 **기능**은 다음과 같다

- 사원들의 총 월급
- 사원의 평균 월급
- 부서별 총 월급, 평균 월급
