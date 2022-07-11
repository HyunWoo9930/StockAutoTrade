# StockAutoTrade

## 래리 윌리엄스의 변동성 돌파 전략을 참고하여 국내, 미장 주식 매매 프로그램을 개발

###  래리 윌리엄스의 변동성 돌파 전략 : https://quantlive.tistory.com/185 

https://apiportal.koreainvestment.com/intro 한국 투자증권 open api를 참고하여 파이썬으로 개발, 추가 수정작업

2022.07.01 v1 개발\
2022.07.11 https://kr.tradingview.com/markets/stocks-korea/market-movers-most-volatile/ 참고하여 변동성이 큰 주식들로 수정

TODO
 * 오늘 매수 타이밍에 맞아 매수를 하였지만, 변동성이 매우 커 매수 손익율이 -0.5% 이하로 떨어지면 매도주문.
 * discord 봇을 더 만들어, 직접 api로 매수, 매도 봇을 만들기.
 * terminal로 실행시키는 것이 아닌, api를 개발하여 웹에서 request 보내기.
 * java 로 다시 만들어보기.
