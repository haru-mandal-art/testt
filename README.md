
![하루 만다라트](https://github.com/haru-mandal-art/testt/assets/94586184/4b39abf6-29d3-4b75-8157-99c7cfbef372 "하루 만다라트")

<a href="https://play.google.com/store/apps/details?id=com.google.samples.apps.nowinandroid"><img src="https://play.google.com/intl/ko_kr/badges/static/images/badges/ko_badge_web_generic.png" height="70"></a> <a>&nbsp;&nbsp;</a>
<a href="https://strong-marlin-f95.notion.site/SRS-3098c52bd8da4fc6aa41f6cba6b2f47f?pvs=4"><img src="https://github.com/haru-mandal-art/testt/assets/94586184/541768ab-a91d-429b-a56f-c688c682fcaf" height="70"></a>



## 하루 만다라트
> 💡 **만다라트와 투두의 만남으로 가지고있는 꿈과 목표를 구체화하고 달성하세요.**

### Feature
#### 온/오프라인 지원
- 최초 로그인 이후 온라인, 오프라인 환경 지원
- 데이터 자동 동기화
#### 만다라트
- 9 X 9 만다라트,  목표 계획, 시각화
- 최종 목표 예시 제공
- 최종목표, 핵심목표, 세부목표로 구분, 달성률 표출
- 만다라트 확대, 축소, 제스처를 통한 전환
#### 하루 만다라트
- 하루마다 8개의 할일 그룹 관리
- 날짜별, 그룹별 투두 완료 상태 표출
- 미완료한 투두 시간에 알림 표출
#### 기록
- 작성한 투두 기록 github 잔디 형태로 표출
- 투두를 작성한 총 일수 표출


### ScreenShots
<img src="https://github.com/haru-mandal-art/testt/assets/94586184/0f9e1026-6f75-4e7b-be8a-bfd5e9631e5a" height="360">| <img src="https://github.com/haru-mandal-art/testt/assets/94586184/79887c39-2f08-4c9d-9537-b47b550e336a" height="360">| <img src="https://github.com/haru-mandal-art/testt/assets/94586184/61e68df3-b61e-45bd-b251-abd5a9a5cdd8" height="360"> | <img src="https://github.com/haru-mandal-art/testt/assets/94586184/3094ecdf-4b84-49f1-b806-70ef9bf71cc2" height="360">|
|-|-|-|-|
| <img src="https://github.com/haru-mandal-art/testt/assets/94586184/c8219c8f-dc41-4bfc-b61c-0e06ea77809b" height="360"> | <img src="https://github.com/haru-mandal-art/testt/assets/94586184/e5ae765e-0ed9-4ba2-b407-ecaf175ca730" height="360"> |<img src="https://github.com/haru-mandal-art/testt/assets/94586184/f1d84d56-25b6-4ec1-97f1-a11ffa427784" height="360"> |<img src="https://github.com/haru-mandal-art/testt/assets/94586184/336a6ed5-bd3f-4878-b500-7376015e3c694" height="360">| 

## Module

```mermaid
graph TD;
    app:::app-->:feature:::feature;
    app:::app-->:core:designsystem;
    :feature-->:core:designsystem;
    :feature-->:core:domain;
    :feature-->:core:data;
    :feature-->:core:model;

    :core:data-->:core:model;
    :core:data-->:core:database;
    :core:data-->:core:network;
    :core:data-->:core:datastore;

    :core:domain-->:core:model;

classDef app stroke:#00E489
classDef feature  stroke:#FF8A65
linkStyle 0,1 stroke:#00E489,stroke-width:2px;
linkStyle 2,3,4,5 stroke:#FF8A65,stroke-width:2px;
```


## Development
### Required
| Name | Version |
| --- | --- |
| IDE |   *```Android Studio Hedgehog```* | 
| Kotlin |   *```1.9.10```* | 
| MinSdk  |   *```26```* | 
| TargetSdk  |   *```34```* | 


### Libraries
| Name | Version |
| --- | --- |
| Coroutines | *```1.7.3```* |
| Dagger-Hilt | *```2.48.1```* |
| Room | *```2.6.1```* |
| DataStore  | *```1.0.0```* |
| Serialization| *```1.6.0```* |
| Supabase | *```2.1.4```* |
| Logger | *```2.2.0```* |


> [!NOTE]
> 사용한 라이브러리 세부정보는 [libs.versions.toml](https://github.com/haru-mandal-art/haru-mandalart/blob/dev/gradle/libs.versions.toml) 를 참고해 주세요.

## Team

|                                        Android                                         |                                              Android                                               |
|:-------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------:|
| [<img src="https://github.com/coldDelight.png" width="150px"/>](https://github.com/coldDelight) | [<img src="https://github.com/2blue-99.png" width="150px"/>](https://github.com/2blue-99) | 
| <a href="https://github.com/coldDelight">김찬희                                          |     <a href="https://github.com/2blue-99">  이푸름                                                 | 
