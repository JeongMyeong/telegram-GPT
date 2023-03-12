
# telegram-GPT
<p align="center">
  <img src="https://user-images.githubusercontent.com/44393016/224552738-0e8e0d48-13ce-4760-bba8-8534be735a10.jpg" />
</p>

telegram에서 OpenAI의 chagGPT를 사용할 수 있습니다.  
JMGPT는 JM(재미)GPT 이면서 제 이름인 JM(정명)GPT를 의미합니다.  
이름처럼 재미로 만들었기 때문에 ```비용 문제```로 언제 조기 종료될지 모릅니다.

# 사용
<p align="center">
  <img src="https://user-images.githubusercontent.com/44393016/224554095-eac4aa1e-9b90-4050-8bb0-09e6977f9a16.png" />
</p>   

- telegram 검색 : ```JMGPT```
- 링크 : https://t.me/JMGPT_bot
- 한 달간 총 요청은 100회로 제한되며, 이미지 생성 요청은 10회로 제한됩니다.
- 더 많은 요청이 필요하면 issue에 등록바랍니다.

# Contents
### 대화
- ChatGPT 서비스의 전반적인 기능을 수행합니다.
### 이미지생성
- OpenAI의 DALL·E model을 사용하여 이미지를 생성합니다.
- 메시지의 앞부분에 ```이미지생성``` 이라는 단어를 사용합니다.
- 예시 :  ```이미지생성 puppy sitting on a tree```
- ![스크린샷 2023-03-13 오전 12 05 42](https://user-images.githubusercontent.com/44393016/224553445-956367ff-f3f7-455f-a6fc-04ef7b257efa.png)

### Image Description
- salesforce-lavis 를 사용하여 이미지를 설명할 수 있습니다.
- telegram에서 이미지를 전송하면 이미지에 대한 설명을 응답받을 수 있습니다.

# 데이터 관리
- 사용자가 JMGPT_bot에 전송하는 데이터는 telegram Bot이 실행되고 있는 서버, 일부 데이터는 OpenAI에 전송됩니다.
- 그러므로 민감한 정보의 텍스트나 이미지 전송은 삼가해주시기 바랍니다.
- 저장된 데이터는 서비스 개선 목적으로 사용될 수 있음을 미리 고지합니다.
- 삭제하기를 원하는 텍스트나 이미지가 있을경우 issue 등록바랍니다.
