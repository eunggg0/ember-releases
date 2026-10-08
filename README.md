# Ember 다운로드·업데이트 배포 저장소

Ember(애플 실리콘 맥용 윈도우 게임 런처)의 **설치 파일과 자동 업데이트 피드**를 올리는 곳입니다. 소스 코드는 여기 없습니다.

- **다운로드**: 늘 최신 — `https://eunggg0.github.io/ember-releases/download/` ([Releases](https://github.com/eunggg0/ember-releases/releases), 아직 정식 출시 전이라 비어 있습니다)
- **자동 업데이트 피드**(앱이 읽는 주소): `https://eunggg0.github.io/ember-releases/appcast.xml`
  - 앱 안에서 새 버전을 알려 주고, 바뀐 파일만 받는 변경분(delta) 업데이트를 씁니다. 설정·게임 데이터는 그대로 유지됩니다.
  - 모든 업데이트 파일은 EdDSA(Ed25519)로 서명되어 있고, 앱에 박힌 공개키와 맞지 않으면 설치하지 않습니다.
- **요구 사항**: Apple Silicon(M1 이상), macOS 14 이상.

---

# Ember downloads & update feed

Distribution repository for **Ember** (a Windows game launcher for Apple silicon Macs): installers and the Sparkle update feed. No source code lives here.

- **Downloads**: always the newest — `https://eunggg0.github.io/ember-releases/download/` ([Releases](https://github.com/eunggg0/ember-releases/releases), empty until the first public release)
- **Update feed** read by the app: `https://eunggg0.github.io/ember-releases/appcast.xml`
  - Delta updates download only changed files; settings and game data are kept.
  - Every update archive is EdDSA (Ed25519) signed and verified against the public key built into the app.
- **Requirements**: Apple silicon (M1 or later), macOS 14 or later.
