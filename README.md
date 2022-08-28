경로추천 및 안내 키오스크

    주요지점마다 키오스크를 설치하고 등반/산책로의 정보는 사전 구성함
    사용자의 휴대폰 블루투스를 통하여 현재 위치를 파악하고
    기존 사용자의 동선정보 등으로 추천경로 정보 제공

목표기능

    1. 비콘 송수신 기능 구현
	
    2. 위치정보 저장 및 동선 정보 구성
	
    3. 추천경로 제안 등 부가 기능 구현
	
    4. 유사시 보호자 알람통지

팀원

	박병철, 송상희, 박지섭, 박수정, 박현섭


구현기능

	1. 비콘 송수신 기능 구현

		1-1. 비콘 송신앱

		키오스크에서 BLE advertising

		참조소스 출처:
		https://altbeacon.github.io/android-beacon-library/index.html

		1-2. 비콘 스캔앱

		휴대폰에서 BLE advertising 신호 스캔 및 DB서버에 logging

		참조소스 출처:
		https://altbeacon.github.io/android-beacon-library/index.html
		

		

