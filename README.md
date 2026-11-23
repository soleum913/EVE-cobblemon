# EVE Cobblemon

EVE 동아리 포켓몬(Cobblemon) 서버용 클라이언트 모드팩입니다. [packwiz](https://packwiz.infra.link/) 형식이며, Prism Launcher에서 게임을 켤 때마다 이 저장소의 최신 목록으로 자동 업데이트됩니다.

* Minecraft 1.21.1 / Fabric Loader 0.19.5
* 서버 주소와 접속 방법은 동아리 안에서만 안내합니다.

## 모드 파일에 대하여

이 저장소에는 **모드 jar 파일이 들어 있지 않습니다.** `mods/`·`resourcepacks/`의 `.pw.toml` 파일은 "어느 모드의 어느 파일을 받을지"와 파일 해시만 기록한 것이고, 실제 파일은 설치할 때 각 원작자의 배포처(Modrinth, CurseForge)에서 직접 받습니다. 모든 모드의 권리는 각 원작자에게 있습니다.

## 출처를 밝혀 쓰는 모드

| 모드 | 작가 | 내용 | 라이선스 |
|---|---|---|---|
| [Cobblemon: AllTheMons x Mega Showdown](https://modrinth.com/datapack/allthemons-x-mega-showdown-legacy) | **AllTheMons** · **Lvnatic** 외 기여자들 | Cobblemon에 없는 포켓몬(크레세리아·울트라비스트·패러독스 등)의 모델과 애니메이션 | AllTheMons License v3.3. 2026-11-24 ATM 공식 Discord에서 "수익 없는 대학 동아리 비공개 서버는 따로 신청할 필요 없다"는 답을 받았습니다 |
| [Cobblemon: Mega Showdown](https://modrinth.com/mod/cobblemon-mega-showdown) | Yajat Kaul 외 | 메가진화·Z기술·다이맥스·테라스탈·폼 변화 | MEGA SHOWDOWN LICENSE v2.1 (비상업 서버는 별도 허락 불필요) |

예전에 잠시 쓴 [Complete Cobblemon Collection](https://modrinth.com/mod/complete-cobblemon-collection-myths-and-legends-compat)(Xcavalier)에도 감사드립니다. Mega Showdown과 그림 파일이 겹쳐 AllTheMons x Mega Showdown으로 바꾸었습니다.

## 이 저장소에서 직접 배포하는 파일

| 파일 | 내용 | 권리·라이선스 |
|---|---|---|
| `global_packs/required_resources/EVE_lang_ko.zip` | 여러 모드의 비공식 한국어 번역 리소스팩 | 원문은 각 모드 원작자의 것입니다. 팩 안 `CREDITS.txt` 참조 |
| `resourcepacks/EVE_font_*.zip` | 한글 도트 글꼴 리소스팩 | 각 글꼴의 SIL Open Font License (팩 안 `OFL.txt`) |
| `config/` | 모드 설정 파일 | 동아리 서버용 설정 |
| `config/fancymenu/` | 메인 메뉴 레이아웃과 그림 | 동아리 자체 제작 |

## 번역·자료 내림 요청

이 저장소의 번역이나 파일에 권리를 가진 분이 내림을 원하시면 GitHub 이슈로 알려 주세요. 확인하는 대로 내리겠습니다.
