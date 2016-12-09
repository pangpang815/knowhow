## Developing on AWS

### LAB 실습Solution
 - http://bit.ly/dev20-solutions

### Online Book
 - http://online.vitalsource.com
   
### 1-DAY

1. 클라우드 애플리케이션 개발을 위한 모범 사례
  - 느슨함 결합
  - 로그 측정 및 성능 & 보안& 및 제약사항 파악

2. Amazon Resource Name (ARN)
  - DynamoDB: region, resource 정보 필요함
  - S3: bucket id 가 고유하므로, region & resource 정보는 없어도 됨


### 2-DAY
1. Email send system
   SQS, SES
2. free teir로 활용할 수 있는 리소스를 확인하면 무료 운영 가능함
3. Cognito를 활용하여 인증 가능함


### 3-DAY
1. AWS 관리콘솔에서 교차 계정 접근 (Cross-Account Access) 관리
2. 접근 권한 설정 시, 명시적인 deny 권한이 우선시 됨

3. ec2:RunInstances 
   ec2를 생성할 수 있는 권한
4. iam:PassRole
  other user에게 role을 건네줄 수 있는 권한
5. sts:AssumeRole
  other user로부터 role을 건네받을 수 있는 권한

#### Cognito


#### Sticky Session 
