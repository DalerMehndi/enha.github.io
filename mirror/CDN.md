Content Delivery Network  
Content Distribution Network `[1]`

[[edit](http://rigvedawiki.net/r1/wiki.php/CDN?action=edit&section=1)]

## 개요 ¶

음원, 영상파일등의 10메가 이상의 대용량 파일을 안정적으로 제공하기 위해 구상되었고, 이 과정에서 자주 사용되는 파일의
[병목현상](%EB%B3%91%EB%AA%A9%ED%98%84%EC%83%81.md)을 해결할 수 있음이 확인된 전송기술이다.

[[edit](http://rigvedawiki.net/r1/wiki.php/CDN?action=edit&section=2)]

### 기술개발의 배경 ¶

초기 기술개발은 [미국](%EB%AF%B8%EA%B5%AD.md)에서 집중적으로 개발되었는다.  
미국은 땅덩이가 워낙에 넓어, 중간 네트워크에서 서버문제가 발생하거나 전송망에 이상이 생기면 속도가 하염없이 곤두박질치는 상황이었다.

  

또한, 동부와 서부를 연결하는 중부지방에 전송망이 집중되어 형성되는 미들마일 구간`[2]`이 뿜어내는 전송에러와 중간 손실문제를 해결할
필요성이 생겼기 때문이다.

[[edit](http://rigvedawiki.net/r1/wiki.php/CDN?action=edit&section=3)]

## 원리 ¶

[ISP](ISP.md) 네트워크 말단에 캐시서버를 여러대 설치해 사용 요청이 오면, 요청이 온곳에서 제일 가까운 복수의 캐시서버에서
데이터를 끄집어내 제송한다.  
다수로 분산하여 지원제공하는 [P2P](P2P.md)라 착각할수도 있으나, CDN은 캐시서버가 설치된 지역 혹은 국가의 것을 우선적으로
전송하는 것이다.

  

셋팅하게 되면 접속이 몰릴때 발생하는 [병목현상](%EB%B3%91%EB%AA%A9%ED%98%84%EC%83%81.md)이 만드는
전송속도 저하를 막고 타사의 [ISP](ISP.md)를 거치며 발생하는 데이터 손실을 방지할수 있다.

[[edit](http://rigvedawiki.net/r1/wiki.php/CDN?action=edit&section=4)]

## 장점 ¶

[병목현상](%EB%B3%91%EB%AA%A9%ED%98%84%EC%83%81.md)이 해결되고 항상 빠르고 안정적인 전송이
가능해진다.  
또한, ISP의 장애가 발생해도 다른 ISP에 물려있는 캐시서버에서 전송을 함으로 멈추지 않는 전송이 이루어진다`[3]`

[[edit](http://rigvedawiki.net/r1/wiki.php/CDN?action=edit&section=5)]

## 기타 ¶

[[edit](http://rigvedawiki.net/r1/wiki.php/CDN?action=edit&section=6)]

### 세계최초의 서비스업체 ¶

[세기말](%EC%84%B8%EA%B8%B0%EB%A7%90.md)인 [1999년](1999%EB%85%84.md),
[미국](%EB%AF%B8%EA%B5%AD.md)의 아카마이와 디지털 아일랜드, 미러 이미지등의 회사가 CDN 서비스를 시작했다.

  

땅덩이가 넓은 미국에서 세계최초 시작되었다.  
이시기 CDN은 이미지 파일의 인장적인 전송을 위해 시작되었으며 [2002년](2002%EB%85%84.md) 이후 전송기술이 매년
눈부시게 발전해 나가고 고용량 음원과 영상매체의 전송빈도가 늘어나게 되며 빠른전송을 위한 부분이 부각되게 된다.

`\----`

  * `[1]` 초기에는 전자가 주로 사용되었으나, 기술정립이 된 후자의 표기가 자주 사용하게 되었다. 헷갈리면 공통적인 약자로 쓰자.
  * `[2]` ISP끼리 연결된 구간을 말한다
  * `[3]` 물론, 이것은 여러 국가에 분산된 다수의 캐시서버가 필요하다. 캐시 서버가 몇대 안되고 한국가에 몰려 있는 경우 해당 국가의 망이 다운되면 멈춘다

