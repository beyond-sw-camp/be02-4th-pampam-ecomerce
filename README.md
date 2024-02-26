<h1 align="center">로컬 푸드 팜팜(Pampam) 🌽<br>데브옵스 아키텍쳐 구현
</h1>

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

## 🎬CI/CD 구현

<br>
<br>
<br>
<br>
<br>
<br>

## 📌프로젝트 목표
운영중인 환경에 CI/CD 적용 목표 간단하게 작성
<br>
<br>
<br>
<br>
<br>
<br>

## 🖥️운영 환경

<br>
<br>
<br>
<br>
<br>
<br>

## ✨CI/CD 시나리오 📖(펼쳐주세요)

<details>
    <summary>
<span style="font-size:150%"> CI(Continuous Delivery)를 이용하는 이유 </span></summary>
작성중
</details>

</br>

<details>
    <summary>
<span style="font-size:150%"> CD(Continuous Delivery)를 이용하는 이유 </span></summary>
우리 팀은 백엔드 시스템을 모놀리식(monolithic) 아키텍처에서 MSA(Microservices Architecture)로의 전환 작업이 진행되었습니다.
이로 인해 회원과 관련된 여러 서비스가 독립적으로 운영되어야 하는 상황이 발생하였고, 이에 따라 추가적인 백엔드 서버가 요구되었습니다.
서버가 늘어남에 따라 각 서비스를 개별적으로 배포해야 하는 작업이 빈번하게 발생하게 되었습니다.

</details>

</br>

<details>
    <summary>
<span style="font-size:150%"> 문제 해결을 위한 자동화 도구 필요성 </span></summary>
</br>
수동으로 배포하는 작업을 반복하는 것은 개발자의 생산성을 떨어뜨립니다. 또한 MSA를 적용하므로써 분리된 여러 서비스들을 개별적으로 배포해야 되는 문제가 있었습니다.
이러한 수동적인 배포 방식에서는 서비스 개선을 위한 지속적인 프로젝트 형상관리에 많은 어려움이 예상되었습니다.
따라서 프로젝트 효율성과 안정성을 유지하기 위해 배포 프로세스를 자동화할 필요성을 느꼈고, 자동화한다면 프론트엔드 및 백엔드 배포 과정에서의 시간과 노력을 절약하고, 실수를 줄일 수 있습니다.

</details>

</br>

<details>
    <summary>
<span style="font-size:150%"> 우리 팀이 무중단 배포를 선택한 이유 </span></summary>
</br>

무중단 배포를 선택하는 이유는 사용자들이 서비스를 계속 이용할 수 있도록 보장하기 위함입니다. 중단 배포를 통해 서비스를 제공할 경우 새로운 버전을 배포하기 위해 이전 버전의 프로세스를 종료하고 새로운 버전을 시작해야 하는데, 이 때 사용자들은 일시적으로 서비스에 접근할 수 없게 됩니다. 특히 선착순으로 이루어지는 공동구매서비스를 제공하는 우리 서비스의 경우, 중단되는 시간에 사용자들이 원하는 거래를 완료하지 못할 수 있어 치명적인 문제가 발생할 수 있기에 무중단 배포를 선택하게 되었습니다.

</details>
<br>



<details>
    <summary>
<span style="font-size:150%"> Rolling Update 배포 방식 선택 이유 </span></summary>
</br>
중단 배포의 종류로는 Rolling Update, Blue-Green, Canary 배포가 있습니다. 3가지 방법 중에서 Rolling Update를 선택하였는데, 이 배포 방식에 대해 먼저 설명하자면 V1파드가 존재할 때 V2 파드를 하나 늘리고 V1 파드를 하나 줄이고 이를 반복하여 버전을 구버전에서 신버전으로 점진적으로 교체하는 방법입니다. Rolling Update는 서비스의 지속성을 보장하면서도 새로운 기능을 제공할 수 있다는 점과 다른 방법들에 비해 자원을 적게 소비하면서도 무중단으로 서비스를 제공할 수 있다는 장점으로 인해 선택하게 되었습니다.
<p align="center">
<img width="80%" src="./img/rollingUpdate.png">
</br>
</br>
 다른 배포 방식인 Blue-Green 배포는 한 번에 버전을 교체하기 때문에 리소스를 많이 필요로 하며, Canary 배포 역시 새로운 버전을 일부 사용자에게 테스트하면서 점진적으로 서비스를 업데이트하기 때문에 두 버전이 동시에 존재해야 하고 Blue-Green과 같이 많은 리소스를 필요로 하기에 우리에게 적합한 배포방식이 아니었습니다.
 따라서 우리팀은 MSA전환으로 인한 백엔드 및 DB 서버의 개수가 많아짐에 따라 자원을 더 효율적으로 사용 할 수 있는 Rolling Update 방식을 이용하게 되었고, 이를 통해 서비스의 지속성을 유지하면서도 자원을 효율적으로 활용할 수 있었습니다.
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
