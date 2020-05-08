ESP01
==========================
  Texting.....
  ----------------------

    ESP01은 WiFi 통신을 위한 소형 모듈입니다.
    
    저는 제가 진행한 프로젝트를 기반으로 아두이노와 연결하여 통신하는 것을 소개해드리고자 합니다.
    
    ![사진](https://postfiles.pstatic.net/MjAyMDAyMThfMjAy/MDAxNTgxOTg5MjczODM0.F-NJqHhsQlusdKY5STi90Oz95EOTVbORn35i8J7mc3sg.7WysADOcWmuP0IdwzZ33ppMDlnQFovZNhPG9gIyJplwg.JPEG.wngustnf/esp01.jpg?type=w580)  

    ESP01과 아두이노를 연결한 후 처음 해야할 것은 ESP01의 통신속도를 수정하는 것입니다.
    
    /connecting_first/connecting_first.ino 파일을 통해 최초 아두이노와 ESP01의 통신이 가능합니다.
    
    아두이노의 기본 터미널에 "AT" 명령어를 입력하고 전송하면
    
   ![사진](https://postfiles.pstatic.net/MjAyMDA1MDhfMTAy/MDAxNTg4OTMwMTkyNDcx.eiWuKPfaPYvjvGIcWhgYkN0NGWH66cibRusmotZkWGog.cAN4uDnO4Cvb7r-NusODO8QfCwxFDNeutstVliIxbrwg.PNG.wngustnf/AT_OK.png?type=w580)
    
    위와 같이 "OK"라는 응답을 받을 수 있습니다.
    
    만약 응답이 오지 않는 경우 연결상태를 다시 확인하시기 바랍니다.
    
