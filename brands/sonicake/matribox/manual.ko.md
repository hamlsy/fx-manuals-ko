---
brand: "sonicake"
model: "matribox"
language: "ko"
source: "User-provided text (translated and reorganized)"
firmware: "v1.0.4"
last_updated: "2026-04-17"
---

# SONICAKE Matribox 사용설명서 (한국어)

## 안내
제품 개선을 위해 사전 고지 없이 사양 및 구성(외관, 패키지, 매뉴얼 내용, 액세서리, 크기, 파라미터, 화면 표시 등)이 변경될 수 있습니다. 지역/모델에 따라 사양과 기능(색상, 크기 포함)이 다를 수 있으며, 이미지들은 예시입니다.

- 펌웨어 기준: `v1.0.4`
- 지원 이메일: `support@sonicake.com`
- 소프트웨어 페이지: `www.sonicake.com/products/matribox`

## 목차
1. 주의사항
2. 제품 개요
3. 패널 소개
4. 메인 메뉴
5. 동작 모드
6. 이펙트 편집 메뉴
7. 저장 / 튜너 / 루퍼 / 드럼
8. 글로벌 설정
9. 소프트웨어
10. 이펙트 목록
11. 문제 해결
12. 주요 사양

## 1) 주의사항
### 취급
- 기기를 물에 젖지 않게 하십시오. 액체가 들어가면 즉시 전원을 끄십시오.
- 통풍구를 막지 마십시오.
- 열원 근처에 두지 마십시오.
- 폭풍/낙뢰 시 전원을 분리하십시오.
- 강한 전자기장 환경에서 사용을 피하십시오.

### 전원 및 입출력 연결
- 케이블 연결/해제 전, 본체와 연결 장비 전원을 모두 끄십시오.
- 기기 이동 전, 모든 연결 케이블과 어댑터를 분리하십시오.

### 청소
- 마른 천으로만 청소하십시오.

### 분해/개조
- 기기를 열지 마십시오.
- 사용자가 직접 수리하지 마십시오.
- 섀시를 열면 제조사 보증이 무효가 될 수 있습니다.

### AC 어댑터
- 반드시 `DC 9V 센터 마이너스 500mA` 어댑터를 사용하십시오.
- 규격이 다른 어댑터는 오작동/안전 문제를 유발할 수 있습니다.
- 어댑터 정격 전압에 맞는 콘센트를 사용하십시오.
- 장기간 미사용 또는 낙뢰 시 전원을 분리하십시오.

### 오작동 시
1. AC 어댑터 분리 후 전원을 끄십시오.
2. 연결된 다른 케이블도 모두 분리하십시오.
3. 모델명/시리얼/증상을 정리하십시오.
4. SONICAKE 지원팀에 문의하십시오.

## 2) 제품 개요
Matribox는 컴팩트한 멀티이펙트 프로세서로, 130개 이상의 이펙트를 제공합니다. 일렉기타, 어쿠스틱기타, 베이스, 키보드 등 다양한 악기에 사용할 수 있습니다.

핵심 특징:
- 40개 이상의 앰프 모델
- 9개의 이동 가능한 이펙트 모듈(이펙트 매트릭스)
- 실제 회로 반응을 반영한 디지털 모델링 기반 톤 처리

## 3) 패널 소개
### 상단 컨트롤
1. 마스터 볼륨 조절
2. 화면(프리셋 및 동작 정보 표시)
3. `PARA` 노브: 회전/눌러 파라미터 및 메뉴 조작
4. `GLOBAL` 버튼
5. `DRUM` 버튼 (짧게: 드럼 On/Off, 길게: 드럼 메뉴)
6. `BACK` 버튼(이전 메뉴)
7. `SAVE` 버튼(저장/이름 변경/복사)
8. 화면 하단 3개 노브(메뉴별 파라미터 조절)
9. 풋스위치:
- 프리셋 앞/뒤 전환
- 두 스위치 동시: 튜너
- 두 스위치 길게: 루퍼
10. 익스프레션 페달:
- 지정 파라미터 또는 볼륨 제어
- 토 스위치로 페달 기능 전환

### 입출력 단자
11. 1/4" TS 모노 입력(악기)
12. 1/4" TS 스테레오 출력 2개(L/R)
13. 1/8" TRS 스테레오 입력(AUX)
14. 1/8" TRS 스테레오 출력(헤드폰)
15. USB Type-C(전용 에디터/오디오 인터페이스)
16. DC 9V 센터 마이너스 전원 입력

## 4) 메인 메뉴
메인 화면 정보:
- 프리셋 번호: `P01-P99`(사용자), `F01-F99`(공장)
- 프리셋 상태: 저장되지 않은 변경 여부
- Drum 상태: On/Off 표시
- EXP 상태: On/Off 표시
- 프리셋 정보 영역
- BPM: `40-250`
- 모드: `Preset` 또는 `Stomp`
- P-VOL: 프리셋 볼륨

## 5) 동작 모드
Matribox는 풋스위치 동작이 다른 2가지 모드를 제공합니다.

### Preset 모드
- 풋스위치를 눌러 프리셋을 전환합니다.

### Stomp 모드
- 풋스위치를 눌러 해당 모듈 On/Off를 전환합니다.
- 어떤 모듈을 연결할지는 이펙트 편집 메뉴에서 설정합니다.

### 모드 전환
- 메인 메뉴에서 지정된 풋스위치를 길게 눌러 Preset/Stomp를 전환합니다.

### Tap Tempo
- 지정 풋스위치를 길게 눌러 Tap Tempo를 활성화합니다.
- 탭 입력으로 프리셋 BPM을 설정합니다.
- 다시 길게 눌러 종료합니다.

## 6) 이펙트 편집 메뉴
- 메인 메뉴에서 `PARA`를 눌러 진입합니다.
- `PARA` 회전: 편집할 모듈 선택
- `PARA` 클릭: 현재 모듈 파라미터 페이지 전환
- 하단 3개 노브: 화면 파라미터 바의 3개 항목 제어
- 모듈 On/Off, 이펙트 전환, 파라미터 조정 수행
- Stomp 모드에서는 `FS Switch` 항목으로 풋스위치 할당 가능
- 이 메뉴에서 `PARA` 길게: 이펙트 체인 순서 조정

## 7) 저장 / 튜너 / 루퍼 / 드럼
### 저장(Save)
`SAVE` 버튼으로 저장 메뉴에 들어가 편집 항목을 프리셋에 저장하고, 저장 위치 선택 및 프리셋 이름 변경이 가능합니다.

### 튜너(Tuner)
- 두 풋스위치를 동시에 눌러 튜너 진입
- 모드: `Mute`, `Bypass`, `Thru`
- 기준 피치: `435Hz-445Hz`

### 루퍼(Looper)
- 두 풋스위치를 길게 눌러 루퍼 진입
- 녹음/재생/오버더빙을 풋스위치로 제어
- 정지 풋스위치로 전체 정지, 길게 눌러 전체 삭제
- `PARA` 노브로 프리셋 전환 가능

루퍼 모드:
- `Pre`: 이펙트 없는 모노 녹음, 최대 90초
- `Post`: 이펙트 포함 스테레오 녹음, 최대 45초

### 드럼(Drum)
- `DRUM` 버튼 길게 눌러 드럼 메뉴 진입
- 리듬 스타일, 속도, 볼륨 설정
- `Sync` On 시 프리셋 BPM과 동기화

## 8) 글로벌 설정
`GLOBAL` 버튼으로 진입하며, `PARA` 회전/클릭으로 항목과 페이지를 이동합니다.

### Input/Output
- Input Level: `-20dB ~ +20dB`
- No CAB (L/R): 선택한 출력 채널에서 CAB 모듈 우회(프리셋 설정 무시)

### USB Audio
- Rec Level: `-20dB ~ +20dB`
- Monitor Level: `-20dB ~ +6dB`
- Rec Mode (L/R): 녹음 채널을 Dry/Wet 중 선택

### Tap Tempo Mode
- `FX1`, `FX2`, `DLY`, `MOD`를 프리셋 BPM 강제 동기화 가능

### EXP Setting
- Target: 익스프레션 페달 제어 대상/파라미터 지정
- EXP Range: 최소/최대 값 범위 설정
- VOL Range: 볼륨 제어 범위 및 유효 구간 설정
- Calibrate: 페달 캘리브레이션 실행

### Factory Reset
- 사용자 데이터를 지우고 공장 상태로 복원

### About
- 펌웨어 정보 표시

## 9) 소프트웨어
Matribox를 컴퓨터에 연결하면 전용 소프트웨어로 다음 작업이 가능합니다.
- 기기/프리셋 관리
- 톤 설정 편집
- 파일 전송
- 펌웨어 업데이트
- 설정 복원
- 서드파티 IR 업로드

지원 플랫폼: Windows, macOS

## 10) 이펙트 목록 (상세)
### FX1 & FX2 모듈
| 이름 | 설명 |
|---|---|
| COMP | Ross 계열 컴프레서 성향의 모델입니다. |
| COMP 2 | Keeley C4 4노브 컴프레서 계열 성향입니다. |
| AC Sim | 일렉기타를 위한 어쿠스틱 시뮬레이터. `STD`, `Jumbo`, `ENH`, `Piezo` 모드 제공. |
| Touch-W | 연주 강도에 반응하는 터치 와우(기타/베이스 모드). |
| Auto-W | 속도 기반으로 자동 스윕되는 오토 와우. |
| UK-W | VOX V846 계열 와우 성향. |
| Cry-W | Dunlop CryBaby 계열 와우 성향. |
| Octaver | 폴리포닉 옥타브 이펙트. |
| Dual Melody | 폴리포닉 하모나이저/피치 시프터. |
| Pitch | 폴리포닉 피치 시프터/하모나이저. |
| Tape Mod | 빈티지 테이프 포화감 기반의 따뜻한 질감. |
| Ring Mod | 벨/차임 같은 비조화 배음을 만드는 링 모듈레이터. |
| Filter | 4단계 오토 필터 기반 신스 라이크 톤 생성. |
| Boost | Xotic EP Booster 계열 부스트 성향. |
| Skreamer | Ibanez TS-808 Tube Screamer 계열 오버드라이브. |
| Butter OD | 2노브 옐로우 오버드라이브 계열의 두툼한 드라이브 질감. |
| Super OD | 3노브 옐로우 오버드라이브 계열 성향. |
| Blues OD | 풀레인지 성향의 블루스 계열 오버드라이브. |
| Dist Plus | 기타/베이스 모두에 적용 가능한 기본 디스토션. |
| JP Dist | 오렌지 계열 3노브 디스토션 성향. |
| Shark | MI Audio Crunch Box 계열 디스토션 성향. |
| Dark Mouse | ProCo RAT(LM308 초기 계열) 성향 디스토션. |
| Fuzz Cream | Electro-Harmonix Big Muff Pi 계열 퍼즈/디스토션. |
| Red Fuzz | Dallas-Arbiter Fuzz Face 계열 퍼즈 성향. |
| Bass Dist | 베이스용 톤 범위가 넓은 디스토션. |

공통 파라미터 계열(모델별 상이):
- `Sustain`, `Output`, `Attack`, `Clip`
- `Body`, `Top`
- `VOL`, `Sense`, `Range`, `Q`, `Mix/Blend`
- `Depth`, `Rate`, `Low/Bass`, `High/Treble`, `Sync`
- `Low Oct`, `High Oct`, `Dry`, `Wet`
- `H-Pitch`, `L-Pitch`, `H-Vol`, `L-Vol`
- `Gain/Fuzz`, `H-Cut`, `Freq`, `Fine`, `Tone/Filter`, `Step`, `Bright`

### AMP 모듈
| 이름 | 설명 |
|---|---|
| TWD Deluxe | Fender Tweed Deluxe 계열 앰프 성향. |
| B-Man N | Fender '59 Bassman 노멀 채널 계열 성향. |
| Dark Double | Fender '65 Twin Reverb 계열 성향. |
| Calif Star CL | Mesa/Boogie Lone Star CH1 계열 성향. |
| Voks 30N | VOX AC30HW 노멀 채널 계열 성향. |
| Bog SV CL | Bogner Shiva 20주년 Ch1 계열 성향. |
| Jazz 120 | Jazz Chorus 계열 솔리드스테이트 콤보 성향. |
| Superb CL | Matchless Chieftain 212 클린 계열 성향. |
| Doctor CL | Dr. Z Maz 38 Sr 클린 계열 성향. |
| Brit 45 | Marshall JTM45 노멀 계열 성향. |
| Brit 50JP | Marshall JMP50 점프 연결 계열 성향. |
| Brit 800 | Marshall JCM800 2204 계열 성향. |
| Flyman B1 | Brown Eye 계열 UK 부티크 BE 채널 성향. |
| Doctor OD | Dr. Z Maz 38 Sr 드라이브 계열 성향. |
| Bog SV OD | Bogner Shiva 20주년 Ch2 계열 성향. |
| B-Man B | Fender '59 Bassman 브라이트 채널 계열 성향. |
| Voks 30TB | VOX AC30HW Top Boost 계열 성향. |
| Supero 2 | Supro Dual-Tone 1624T 드라이브 성향. |
| Superb OD | Matchless Chieftain 212 드라이브 계열 성향. |
| Sol 100 OD | Soldano SLO100 크런치 계열 성향. |
| Calif Star OD | Mesa/Boogie Lone Star CH2 계열 성향. |
| Calif IIC+ | Mesa/Boogie Mark II C+ 리드 계열 성향. |
| Dizzy VH | Diezel VH4 계열 성향. |
| Eng 120 | ENGL Savage 120 E610 계열 성향. |
| Halen 51 | Peavey 5150 리드 계열 성향. |
| Sol 100 LD | Soldano SLO100 오버드라이브 채널 성향. |
| Calif IV | Mesa/Boogie Mark IV 리드 계열 성향. |
| Calif DualV | Mesa/Boogie Dual Rectifier 빈티지 성향. |
| Calif DualM | Mesa/Boogie Dual Rectifier 모던 성향. |
| Dragon LD | Grindrod Pendragon PG20C 계열 성향. |
| Flyman B1+ | Brown Eye 계열의 더 공격적인 변형 성향. |
| Tanger R100 | Orange Rockerverb 100 더티 채널 계열 성향. |
| Bog XT Blue | Bogner Ecstasy 블루 채널 계열 성향. |
| Bog XT Red | Bogner Ecstasy 레드 채널 계열 성향. |
| A BassVT | Ampeg SVT 계열 베이스 앰프 성향. |
| A BassFT | Ampeg B-15 Flip Top 계열 베이스 앰프 성향. |
| F-2Bass | Alembic F-2B 계열 베이스 프리앰프 성향. |
| Voks Bass | 빈티지 VOX AC-100 베이스 앰프 계열 성향. |
| Calif Bass | Mesa/Boogie Bass 400 계열 성향. |
| AC Preamp | AER Colourizer 2 계열 어쿠스틱 프리앰프 성향. |

앰프 공통 파라미터 계열:
- `VOL/Gain`, `Output/Master/VOL`, `PRES`
- `Bass`, `Middle`, `Treble`, `Tone`, `Cut`
- `Bright`, `Char`, `MRange`, `Balance`
- `Freq`, `EQ Q`, `EQ Gain`

### NR 모듈
| 이름 | 설명 |
|---|---|
| Gate 1 | ISP Decimator 계열 노이즈 게이트 성향. |
| Gate 2 | `Attack`/`Release` 조절이 가능한 유연한 게이트. |

공통 파라미터: `Thre`, `Attack`, `Rel`

### CAB 모듈
| 이름 | 설명 |
|---|---|
| Supero 1x6 | Supro 계열 1x6 캐비닛(타원형 스피커) 성향. |
| TWD 1x8 | Fender Champ 계열 1x8 캐비닛 성향. |
| TWD-P 1x10 | Fender Princeton 계열 1x10 캐비닛 성향. |
| Bog SV 1x12 | Bogner Shiva 계열 1x12 캐비닛 성향. |
| Viblux 1x12 | Fender Vibrolux 계열 1x12 캐비닛 성향. |
| Voks 1x12 | VOX AC15 계열 1x12 캐비닛 성향. |
| Calif 1x12 | 1980s Mesa/Boogie 계열 1x12 캐비닛 성향. |
| TWD 2x12 | 커스텀 Fender 계열 2x12 캐비닛 성향. |
| Double 2x12 | Fender '65 Twin Reverb 계열 2x12 성향. |
| Star 2x12 | Mesa/Boogie Lonestar 계열 2x12 성향. |
| Rock 2x12 | Two-Rock 계열 2x12 캐비닛 성향. |
| Jazz 2x12 | Jazz Chorus 계열 2x12 캐비닛 성향. |
| BritGN 2x12 | Marshall 2550 계열 2x12 캐비닛 성향. |
| Free 2x12 | Fryette Deliverance 계열 2x12 성향. |
| B-Man 4x10 | Fender '59 Bassman 계열 4x10 성향. |
| Brit75 4x12 | G12T-75 성향의 Marshall 계열 4x12. |
| BritGN 4x12 | Greenback 성향의 Marshall 계열 4x12. |
| BritLD 4x12 | Marshall 1960AV 계열 4x12 성향. |
| BritDK 4x12 | 1968 Marshall 계열 4x12 성향. |
| BritMD 4x12 | 커스텀 Marshall 계열 4x12 성향. |
| Bog 4x12 | Bogner Uberkab 계열 4x12 성향. |
| Dizzy 4x12 | Diezel 계열 4x12 캐비닛 성향. |
| Eng 4x12 | ENGL 계열 4x12 캐비닛 성향. |
| Halen 4x12 | Peavey 6505 계열 4x12 성향. |
| Sol 4x12 | Soldano 계열 4x12 캐비닛 성향. |
| Calif 4x12 | Mesa/Boogie Road King 계열 4x12 성향. |
| Dual 4x12 | Mesa/Boogie Rectifier 계열 4x12 성향. |
| WAM 4x12 | WEM 계열 4x12(Fane 계열 스피커 성향). |
| Tanger 4x12 | Orange PPC412 계열 4x12 성향. |
| Watt 4x12 | Hiwatt SE4123 계열 4x12 성향. |
| Calif 2x10 | Mesa/Boogie 계열 2x10 베이스 캐비닛 성향. |
| Work 4x10 | SWR Workingman's 계열 4x10 베이스 성향. |
| A Bass 4x10 | Ampeg SVT-410HE 계열 4x10 베이스 성향. |
| A Bass 8x10 | Ampeg SVT-810E 계열 8x10 베이스 성향. |
| D | 드레드넛 어쿠스틱 바디 시뮬레이션. |
| OM | OM 타입 어쿠스틱 바디 시뮬레이션. |
| Jumbo | 점보 타입 어쿠스틱 바디 시뮬레이션. |
| GA | GA 타입 어쿠스틱 바디 시뮬레이션. |

공통 파라미터: `VOL`

### EQ 모듈
| 이름 | 설명 |
|---|---|
| Guitar EQ | 기타 대역 중심으로 설계된 이퀄라이저. |
| Bass EQ | 베이스 대역 중심으로 설계된 이퀄라이저. |

공통 제어: 각 대역(`XX Hz`) 부스트/컷, 출력 `VOL`

### MOD 모듈
| 이름 | 설명 |
|---|---|
| Chorus A | Arion SCH-1 계열 스테레오 코러스 성향. |
| Chorus B | 1970년대 후반 앙상블 코러스 계열 성향. |
| Detune | 미세 피치 쉬프트를 원음과 섞는 와이드닝 효과. |
| Flanger | 클래식 플랜저 스윕 성향. |
| Phaser | MXR Phase 90 계열 페이저 성향. |
| Vibrato | BBD 계열 블루 비브라토 페달 성향. |
| Vibe | Voodoo Lab Micro Vibe 계열 성향. |
| Tremolo | Demeter TRM-1 Tremulator 계열 옵토 트레몰로. |
| Sine Trem | 사인파 기반 트레몰로. |
| Bias Trem | 바이어스 파형 기반 트레몰로. |

공통 파라미터: `Depth`, `Rate`, `Tone`, `VOL`, `Detune`, `Wet`, `Dry`, `Pre Delay`, `FdBk`, `Bias`, `Sync`

### DLY 모듈
| 이름 | 설명 |
|---|---|
| Warm | BBD 아날로그 딜레이 계열의 따뜻한 반복감. |
| Pure | 깨끗하고 정확한 딜레이. |
| Mag | 솔리드스테이트 테이프 에코 계열 성향. |
| Tube | 진공관 구동 테이프 에코 계열 성향. |
| 999 Echo | Maxon AD900 계열 아날로그 딜레이 성향. |
| Reverse | 반전 피드백 기반의 특수 딜레이. |
| Slap | 클래식 슬랩백 에코 성향. |
| Rack | 1980s 랙 딜레이 계열의 빈티지 질감. |
| Sweep | 반복음에 필터 스윕이 걸리는 딜레이. |
| Ping Pong | 좌우 채널을 오가는 스테레오 딜레이. |
| Tape | 멀티 테이프 딜레이 계열 성향. |

공통 파라미터: `Mix`, `Time`, `Fdbk`, `Mod`, `Tone`, `S-Depth`, `S-Rate`, `Sync`, `Trail`

### RVB 모듈
| 이름 | 설명 |
|---|---|
| Room | 룸 공간감 리버브. |
| Hall | 홀 공간감 리버브. |
| Church | 교회 규모 공간감 리버브. |
| Plate | 빈티지 플레이트 리버브 성향. |
| Spring | 빈티지 스프링 리버브 성향. |
| Sky | 밝고 풍성한 디케이의 특수 튜닝 리버브. |
| Sea | 깊고 거대한 디케이의 특수 튜닝 리버브. |
| Mod RVB | 모듈레이션이 섞인 리버브 텍스처. |

공통 파라미터: `Mix`, `Pre Delay`, `Decay`, `H-Damp`, `Tone`, `Lo End`, `Hi End`, `Trail`

## 11) 문제 해결
### 전원이 켜지지 않음
- 전원 연결 상태 확인
- 어댑터 정상 동작 확인
- 어댑터 규격(`DC 9V 센터 마이너스 500mA`) 확인

### 소리가 안 나거나 매우 작음
- 케이블 연결 상태 확인
- 출력 볼륨 및 모듈 볼륨 확인
- EXP를 볼륨으로 쓰는 경우 페달 위치/범위 확인
- 프리셋 볼륨, 입력 음소거 상태 확인

### 노이즈 발생
- 케이블 및 악기 출력 잭 확인
- 올바른 전원 어댑터 사용 여부 확인
- 악기 원인 노이즈는 NR 모듈로 보정

### 사운드 이상
- 연결 케이블/외부 페달 설정 확인
- 이펙트 파라미터 과도 설정 여부 확인

### 익스프레션 페달 문제
- EXP On/Off 설정 확인
- 캘리브레이션 수행

## 12) 주요 사양
### 오디오/처리
- A/D/A: 24-bit 고성능 오디오
- 샘플레이트: 44.1 kHz
- SNR: 110 dB
- 동시 이펙트 수: 최대 9

### 프리셋/유틸리티
- 메모리: 사용자 99 + 공장 99
- 루퍼: 최대 90초
- 드럼머신: 100 패턴

### 아날로그 I/O
- 기타 입력: 1/4" TS 언밸런스, 1M Ohm
- AUX 입력: 1/8" TRS 스테레오, 10k Ohm
- L/R 출력: 1/4" TS 언밸런스, 1k Ohm
- 헤드폰 출력: 1/8" TRS 스테레오, 47 Ohm

### USB
- USB 2.0 Type-C
- USB 녹음: 44.1 kHz, 16-bit/24-bit 지원

### 크기/무게
- 크기: 200 (W) x 137.5 (D) x 53.6 (H) mm
- 무게: 732 g

### 전원
- DC 9V 센터 마이너스, 500mA

## 상표 관련 고지
모델링 대상 장비명/제조사명은 각 소유자의 상표이며, 사운드 특성 식별 목적으로만 사용됩니다.

