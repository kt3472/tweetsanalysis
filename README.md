## 트위터 트윗 분석(Tweets Analysis)



**■ Summary**
 - (목표) 트위터 트윗에 기반한 키워드 분석
 - 분석 프로세스 요약
 
 ![dataset](./tweets_process.jpg)

 - 크롤링방법 : Python tweetpy 라이브러리 사용(트위터 API서비스 이용)
 - 크롤링피쳐 : 트위터유저ID, 트윗날짜, 좋아요수, 리트윗 수, 해시태크, 트윗링크 주소 등
 - 빈도분석 : 단어 클라우드 출력
 - 상관분석 : 단어 네트워크 출력
 
**■ Reference** 
 - https://github.com/tweepy/tweepy
 - https://rachelsdotcom.tistory.com/72
 - https://lovit.github.io/nlp/2018/04/17/word_cloud/
