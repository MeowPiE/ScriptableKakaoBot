# ScriptableKakaoBot
> 카카오톡 자동응답 봇 시스템

## 사용법

* kbot 폴더를 /sdcard/ 내부에 생성합니다.
* response.js를 /sdcard/kbot/ 에 생성합니다.
* response 함수를 정의합니다.

```js
function response(room, msg, sender, isGroupChat, replier) {

  // 카톡 알림이 오면 호출

  /* room - 방 이름
     msg - 메세지 내용
     sender - 발신자 이름
     isGroupChat - 단체채팅 여부
     replier - 세션 캐싱 답장 메소드 객체
     replier.reply("") - 현재 세션에 답장 */
}
```

* 온/오프 버튼을 통해 봇을 작동시킬지 안할지 결정합니다.
* 권한 설정하러 가기 버튼을 통해 알림 권한을 활성화 할 수 있습니다.
* 스크립트 리로드 버튼을 통해 적용된 스크립트를 업데이트 할 수 있습니다.
