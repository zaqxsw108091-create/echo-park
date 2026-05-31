# ECHO_PARK (에코 파크) 프로젝트

## 개요
1~6인 협동 퍼즐 플랫포머 게임.
Phaser 3 기반, PWA + Electron 크로스플랫폼.

## 기술 스택
- Phaser 3 (게임 엔진, CDN)
- HTML/CSS/JavaScript (단일 파일)
- Electron (데스크탑 배포)
- PWA (브라우저/모바일)

## NPC 캐릭터 5명
- 루나, 리코, 모카, 블레이즈, 피치

## 핵심 시스템
- EchoRec: 녹화 슬롯 3개, 루프 재생
- 동시 버튼 눌러 출구 열기 (협동 퍼즐)
- 우정 포인트 & 레벨업
- 수동 세이브 슬롯 3개

## 기술적 주의사항
- 렌더러: Phaser.CANVAS (WebGL 컨텍스트 손실 방지)
- 출구 위치: row 16 (floor level)
- 멀티플레이어 미구현 (Colyseus 또는 PeerJS 검토 중)
