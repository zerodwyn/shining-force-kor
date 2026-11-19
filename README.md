# [MD] 샤이닝 포스 한글패치

메가드라이브 **샤이닝 포스 신들의 유산**(シャイニング・フォース 神々の遺産) 한글패치입니다. 메가드라이브 실기에서 구동하는 것을 목표로 작업했습니다.

- 블로그 소개글: https://dwyn.tistory.com/11
- 최신 버전 다운로드: [Releases](../../releases/latest)
- 버그 제보: [Issues → 버그 제보](../../issues/new/choose)
- 후원: https://litt.ly/dwyn

## 작업 사항 및 변경 이력

주요 작업 사항, 추가 기능, 변경 이력 등 자세한 내용은 **[블로그](https://dwyn.tistory.com/11)** 글을 참조해 주세요.

본 한글패치의 정보를 공유하실 때는 블로그 패치 글로 링크를 걸어 주세요.

## 적용 방법

1. [Releases](../../releases/latest)에서 패치 파일을 받습니다.
2. 직접 가지고 계신 원본 ROM에 패치를 적용합니다.
   - 웹에서 적용: [ROM Patcher JS](https://www.marcrobledo.com/RomPatcher.js/)
   - PC 프로그램: Delta Patcher 등
3. 패치된 ROM을 에뮬레이터나 플래시카트로 실행합니다.

### 체크섬 확인

패치는 **일본판 원본 ROM**(1,572,864바이트)에 적용해야 합니다. 패치 후 ROM은 2,097,152바이트로 커집니다.

| 구분 | CRC32 | MD5 | SHA1 |
|---|---|---|---|
| 원본 ROM (일본판) | `9378FBCD` | `72AB457FD395DA1879ED4F6D29B09AF1` | `EF8AFBDC9AF931D9DA34D72EFC8A76F0D5F4379D` |
| 패치 후 (v0.92, 2,097,152바이트) | `A7F34FDC` | `2EB506F95DB52EF6FDF985554E8A4491` | `EAB33221D0E12EED42EAFD4C87E165DA223B56EB` |

- 원본 파일 이름: `Shining Force - Kamigami no Isan (Japan).md` (확장자가 .bin·.gen이어도 내용이 같으면 적용됩니다)
- ROM Patcher JS에 ROM 파일을 넣으면 CRC32, MD5, SHA1이 바로 표시됩니다.

> 이 저장소에는 패치 파일만 있습니다. ROM 파일이나 패치를 적용한 ROM은 배포하지 않으며, 요청에도 응하지 않습니다.
