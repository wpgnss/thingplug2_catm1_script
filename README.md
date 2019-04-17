# thingplug_script
thingplug script, postman과 mqttfx에서 사용되는 thingplug script


## http_postman_script
#### [Script]_ThingPlug20_API.postman.json

ThingPlug API 테스트를 위한 script. postman 툴에서 import 해서 사용한다.


#### [Env]_ThingPlug2.0.postman.json

[Script]_ThingPlug20_API.postman.json 파일의 API를 실행하기 위한 환경변수가 정의된 파일. postman 툴에서 import 해서 사용한다.



## mqtt_script

#### 01 Telemetry 조회.txt
디바이스의 Telemetry를 조회하는 용도로 사용된다. 기간과 갯수를 지정할 수 있다.

#### 02 최신 Telemetry 조회.txt
디바이스의 최신 Telemetry만을 조회하는 용도로 사용된다. telemetry를 지정할 수 있다.

#### 02 최신 Telemetry 조회.txt
디바이스의 최신 Telemetry만을 조회하는 용도로 사용된다. Telemetry를 지정할 수 있다.

#### 03 Attribute 조회.txt
디바이스의 Attribute 조회하는 용도로 사용된다. Attribute를 지정할 수 있다.

#### 04 Attribute 변경요청.txt
디바이스로 Attribute 변경을 요청하는 용도로 사용한다. 디바이스 명세에서 commandable이 true로 설정 되어 있어야 한다.

#### 05 RPC 요청.txt
디바이스로 RPC 명령을 전달하는 용도로 사용한다. 사용자 데이터를 전달할 때 사용한다.

#### 06 Enlist 구독 요청.txt
디바이스의 최신 Telemetry를 자동으로 구독하기 위해 사용한다.

#### 07 Enlist 구독 해지.txt
등록되어 있는 Enlist를 해지하기 위해 사용한다.

