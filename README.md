<h1 align="center">로컬 푸드 팜팜(Pampam) 🌽<br>데브옵스 아키텍쳐 구현
</h1>

<img src="./img/pampamLogo.png">

<br>
<br>
<br>

## 🧑‍🤝‍🧑 팀원

🐯 **정동섭** 🐶 **박현범** 🐺 **양호신** 🐱 **백송연** 🐧 **김도현**

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/Hosae0905"><img src="https://github.com/beyond-sw-camp/be02-2nd-pampam-ecomerce/assets/80888180/71e60cdb-cc1c-4f25-829c-9e6e33d4fd8c" width="100px;" alt=""/><br /><sub><b> 팀장 : 양호신</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/JungDongSeob"><img src="https://github.com/beyond-sw-camp/be02-2nd-pampam-ecomerce/assets/80888180/d6210ade-6e08-4f1a-a893-a96e064a7c8f" width="100px;" alt=""/><br /><sub><b> 팀원 : 정동섭</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/ParkHyeonBeom"><img src="https://github.com/beyond-sw-camp/be02-2nd-pampam-ecomerce/assets/80888180/852c7c08-43c8-4aba-bb02-894ad52f7daa" width="100px;" alt=""/><br /><sub><b> 팀원 : 박현범</b></sub></a><br /></td>
     <tr/>
      <td align="center"><a href="https://github.com/SongYeonBaek"><img src="https://github.com/beyond-sw-camp/be02-2nd-pampam-ecomerce/assets/80888180/7db0d8e5-d406-46f3-9164-aa7b23b9a69f" width="100px;" alt=""/><br /><sub><b> 팀원 : 백송연</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/dohyun0408"><img src="https://github.com/beyond-sw-camp/be02-2nd-pampam-ecomerce/assets/80888180/262aa149-cebf-4e86-a422-29ed9349d745" width="100px;" alt=""/><br /><sub><b> 팀원 : 김도현 </b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

<br>
<br>
<br>
<br>
<br>
<br>

## ✔️ 기술 스택 
<br>
<div align="center">
<img src="https://img.shields.io/badge/k8s-326CE5?style=for-the-badge&logo=#326CE5&logoColor=white">
<img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/jest-C21325?style=for-the-badge&logo=jest&logoColor=white">
<img src="https://img.shields.io/badge/grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
<img src="https://img.shields.io/badge/prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
<img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
<img src="https://img.shields.io/badge/longhorn-6929C4?style=for-the-badge&logo=longhorn&logoColor=white">
<img src="https://img.shields.io/badge/istio-466BB0?style=for-the-badge&logo=istio&logoColor=white">
<img src="https://img.shields.io/badge/webhook-2088FF?style=for-the-badge&logo=webhook&logoColor=white">
</div>
<br>
<br>
<br>
<br>
<br>
<br>



## 📌프로젝트 목표

* 수작업으로 진행되는 배포 작업을 CI/CD를 적용한다면 자동화를 통해 배포 지속적인 형상관리를 쉽게할 수 있을 것입니다.


* 또한, 사람의 개입을 줄여 지속적 배포, 지속적 테스트 및 코드 관리에 드는 시간 및 인적 자원과 같은 리소스를 줄일 수 있게 됩니다. 따라서 CI/CD 적용이 목표입니다.



<br>
<br>
<br>
<br>


## 🖥️운영 환경 📖(펼쳐주세요)


<details>
    <summary>
<span style="font-size:150%"> k8s 전체 서비스 아키텍쳐 </span></summary>
</br>


<p align="center">
<img width="80%" src="./img/back/01. k8s_전체서비스_아키텍처.png">

</details>

</br>
</br>

<details>
    <summary>
<span style="font-size:150%"> k8s 내부 아키텍처 </span></summary>
</br>


<p align="center">
<img width="80%" src="./img/back/02. k8s_내부_아키텍처.png">

</details>



<br>
<br>
<br>


## ✨CI/CD의 필요성 📖(펼쳐주세요)

<details>
    <summary>
<span style="font-size:150%"> CI(Continuous Integration)/CD(Continuous Delivery)를 이용하는 이유 </span></summary>
CI/CD는 다음과 같은 장점이 있습니다.

* 소프트웨어 품질 향상: CI를 통해 버그를 빠르게 발견하고 수정할 수 있으므로 소프트웨어의 품질을 향상시킬 수 있습니다.
* 소프트웨어 안정성 향상: CD를 통해 소프트웨어가 더 자주 배포되므로 프로덕션 환경에서 발생하는 문제를 빠르게 발견하고 수정할 수 있습니다.
* 개발 생산성 향상: CD를 통해 개발자는 소프트웨어를 더 자주 배포할 수 있으므로 개발 생산성을 향상시킬 수 있습니다.
* 고객 만족도 향상: CD를 통해 소프트웨어가 더 자주 배포되므로 고객이 최신 소프트웨어를 사용할 수 있습니다.
</details>

</br>

<details>
    <summary>
<span style="font-size:150%"> 우리 팀이 무중단 배포를 선택한 이유 </span></summary>
</br>
무중단 배포를 선택하는 이유는 다음과 같습니다.</br> 

* **사용자들이 서비스를 계속 이용할 수 있도록 보장하기 위함입니다.**</br>
- 중단 배포를 통해 서비스를 제공할 경우 새로운 버전을 배포하기 위해 이전 버전의 프로세스를 종료하고 새로운 버전을 시작해야 하는데, 이 때 사용자들은 일시적으로 서비스에 접근할 수 없게 됩니다. 
* 특히 선착순으로 이루어지는 공동구매서비스를 제공하는 우리 서비스의 경우, 중단되는 시간에 사용자들이 원하는 거래를 완료하지 못할 수 있어 치명적인 문제가 발생할 수 있기에 무중단 배포를 선택하게 되었습니다.

</details>
<br>



<details>
    <summary>
<span style="font-size:150%"> Rolling Update 배포 방식 선택 이유 </span></summary>
</br>

* 중단 배포의 종류로는 Rolling Update, Blue-Green, Canary 배포가 있습니다. 3가지 방법 중에서 Rolling Update를 선택하였는데, 이 배포 방식에 대해 먼저 설명하겠습니다.


* Rolling Update 방식은 V1파드가 존재할 때 V2 파드를 하나 늘리고 V1 파드를 하나 줄이고 이를 반복하여 버전을 구버전에서 신버전으로 점진적으로 교체하는 방법입니다. 


* Rolling Update는 서비스의 지속성을 보장하면서도 새로운 기능을 제공할 수 있다는 점과 다른 방법들에 비해 자원을 적게 소비하면서도 무중단으로 서비스를 제공할 수 있다는 장점으로 인해 선택하게 되었습니다.
<p align="center">
<img width="80%" src="./img/rollingUpdate.png"><br>Rolling Update 방식
</br>
</br>

* 다른 배포 방식인 Blue-Green 배포는 한 번에 버전을 교체하기 때문에 리소스를 많이 필요로 하며, Canary 배포 역시 새로운 버전을 일부 사용자에게 테스트하면서 점진적으로 서비스를 업데이트하기 때문에 두 버전이 동시에 존재해야 하고 Blue-Green과 같이 많은 리소스를 필요로 하기에 우리에게 적합한 배포방식이 아니었습니다.


* 따라서 우리팀은 MSA전환으로 인한 백엔드 및 DB 서버의 개수가 많아짐에 따라 자원을 더 효율적으로 사용 할 수 있는 Rolling Update 방식을 이용하게 되었고, 이를 통해 서비스의 지속성을 유지하면서도 자원을 효율적으로 활용할 수 있었습니다.
</details>

</br>

<details>
    <summary>
<span style="font-size:150%"> 모니터링 시스템을 사용한 이유 </span></summary>
</br>

* 장애 대처를 위한 모니터링 시스템을 도입한 이유는 서비스를 운영하면서 여러 가지 측면에서 발생하는 문제점을 사전에 식별하고 이를 해결하고자 사용하였습니다.


* 우선, 모니터링 시스템 없이 서비스를 운영하게 되면 사용자가 직접 에러를 보고해야 한다는 점은 문제의 근본이 되었습니다. 


* 이로 인해 시스템에 문제가 발생하더라도 사용자의 수동적인 보고에 의존해야 했으며, 이는 능동적이고 신속한 대응을 어렵게 만들었습니다.


* 또한, MSA 환경을 구축하면서 여러 대의 서버를 동시에 운영하게 되면서 시스템 복잡성가 증가하였습니다. 


* 이러한 MSA의 복잡한 구성 방식을 보다 효율적으로 관리하고, 문제가 되는 부분을 사전에 식별하여 대처할 수 있도록 모니터링 시스템의 도입이 필요하게 되었습니다.

</details>

</br>

<details>
    <summary>
<span style="font-size:150%"> Prometheus 및 Grafana를 사용한 이유 </span></summary>
</br>

* 저희 서비스를 모니터링해줄 시스템으로는 Prometheus와 Grafana를 채택하였습니다.


* 저희 서비스에서는 Kubernetes를 사용하여 시스템을 관리하고 있기 때문에 Kubernetes와의 호환성이 좋은 모니터링 시스템을 선택하고자 했습니다. 


* Prometheus는 Kubernetes와의 통합이 용이하며, 설치 및 운영이 간편하여 IT 인프라의 모니터링과 관리를 단순화할 수 있기 때문에 사용하였습니다. 


* 또한, 헬름 차트를 통해 기본 구성 요소 설치부터 모니터링 대시보드를 간편하게 관리할 수 있습니다. 이를 활용하여 효율적인 서비스 운영과 빠른 장애 대응이 가능해졌습니다.


* Prometheus에 더하여 Grafana를 사용한 이유는 보다 가시성있는 대시보드를 제공하기 때문입니다.


* Prometheus를 통해 얻을 수 있는 여러 가지 데이터를 개발자가 Grafana에서 제공하는 대시보드를 통해 데이터를 시각화할 수 있게 되고, 필요에 따라서 직접 대시보드를 제작할 수 있기 때문에 Grafana를 함께 채택하여 사용하였습니다.

</details>
<br>
<br>
<br>
<br>

## 🎥CI/CD 테스트 및 결과 📖(펼쳐주세요)
<details>
    <summary>CI/CD 테스트 및 결과</summary>
  
<p align="center">
<img width="80%" src="#">
</p>

</details>
<details>
    <summary>2</summary>

<p align="center">
<img width="80%" src="#">TEST
</p>

</details>
<details>
    <summary>3</summary>

<p align="center">
<img width="80%" src="#">TEST
</p>

</details>
<details>
    <summary>4</summary>

<p align="center">
<img width="80%" src="#">TEST
</p>

</details>
<details>
    <summary>5</summary>

<p align="center">
<img width="80%" src="#">TEST
</p>

</details>
<br>
<br>
<br>
<br>
<br>
<br>

## 🌽 [팜팜 사이트 바로가기]<br>
(http://www.localfoodpam.kro.kr/)
