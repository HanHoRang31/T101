### [3주차 과제] 파일 레이아웃을 이용한 격리 file layout 구현 

#### 디렉토리 구성 
```
.
├── global
│   └── s3
│       ├── main.tf
│       ├── outputs.tf
│       └── terraform.tfstate
├── index.html
├── nohup.out
└── stage
    ├── data-stores
    │   └── mysql
    │       ├── main-vpgsg.tf
    │       ├── main.tf
    │       ├── outputs.tf
    │       ├── terraform.tfstate
    │       └── variables.tf
    └── services
        └── webserver-cluster
            ├── main-asg.tf
            ├── main-vpc.tf
            ├── main.tf
            └── user-data.sh
```


#### 구현 테스트 

![스크린샷 2022-10-30 오후 9 05 14](https://user-images.githubusercontent.com/117359361/199969094-ba27d498-162b-41fe-8afb-ff7e6351d6fc.png)
