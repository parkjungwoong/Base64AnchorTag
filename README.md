# Base64AnchorTag
a태그에서 스트링 쿼리를 base64로 인코딩해서 전송는 커스텀 속성 입니다.

> **How To Use:**  
> - Jquery Plugin이 필요합니다.
> - 아래와 같이 자바스크립트 함수를 호출해 주세요.
> - 앵커 태그에 base64 커스텀 속성을 넣어주세요. 
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script type="text/javascript" src="../base64AnchorTag.js"></script>
<script>
    $(document).ready(function() {
        base64AnchorTag.init();
    });
</script>
```


```
<a href="yourLink?name1=value1&name2=value2" base64>test</a>
```
