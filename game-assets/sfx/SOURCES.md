# 소리 출처

웹 판(web/)이 녹음한 소리로 바꾼 자리들의 출처. 웹 판은 이 폴더에 `<자리>.ogg` 가 있으면 그것을 읽고(목록은 web/vite.config.js 가 폴더에서 만든다 — web/src/data/sound.ts 의 RECORDED), 없는 것은 assets/audio 의 합성 소리를 쓴다. assets/audio 는 동결된 Godot 판도 쓰므로 건드리지 않는다. 파일을 넣거나 빼면 아래 표도 고친다(검사 web/tests/sound.test.ts 가 폴더와 표가 같은지 본다).

- 주요 전투·스킬·음성·몬스터·전리품·UI·환경음 및 배경음악 7종은 **Sonniss GDC 2026 Game Audio Bundle** (로열티 프리 상업 사용 가능 스튜디오 96kHz/192kHz 원본)을 `tools/sound/master_sonniss.py` 로 44.1kHz 스테레오 Ogg Vorbis(Q6) 마스터링했다.
- 일부 보조 생활·동물 효과음은 **Freesound CC0** 녹음을 유지한다.

| 자리 | 무엇 | 재료 |
|---|---|---|
| `amb_fire.ogg` | 화로 장작 타닥임(스테레오 루프) | Sonniss GDC 2026 — Ivo Vicic (Campfire - Bonfire FX) |
| `amb_forest.ogg` | 북유럽 고원 숲·새·바람(스테레오 루프) | Sonniss GDC 2026 — Just Sound Effects (Highlands of Norway) |
| `amb_town.ogg` | 중세 마을 | [medieval_village_atmosphere.wav](https://freesound.org/s/578072/) — ramonmineiro |
| `amb_wind.ogg` | 북방 협곡 바람(스테레오 루프) | Sonniss GDC 2026 — 344 Audio (Extreme Winds Vol. 1) |
| `arrow.ogg` | 시위 + 화살 바람 | [Bow_release.wav](https://freesound.org/s/263675/) — PorkMuncher<br>[FX - Swoosh - Light (High Pitch)](https://freesound.org/s/475137/) — bolkmar |
| `bolt.ogg` | 마력 탄 발사 | Sonniss GDC 2026 — Epic Stock Media (Elemental Mutation Whooshes and Impacts) |
| `boss_cast.ogg` | 재의 군주 암흑 영창 | Sonniss GDC 2026 — Alexander Kopeikin (Emotion and Magic) |
| `boss_roar.ogg` | 재의 군주 포효 + 전장 뿔피리 | Sonniss GDC 2026 — 344 Audio (Dinosaurs Vol. 1) + Jake Fielding (Cinematic Horn Braams) |
| `coin.ogg` | 금화 짤랑임 | Sonniss GDC 2026 — Cinematic Sound Design (UI Interaction Elements + Hybrid Game) |
| `dash.ogg` | 구르기·회피 바람 가르기 | Sonniss GDC 2026 — Cinematic Sound Design (Colossal Impacts) |
| `die_boar.ogg` | 낮은 비명 + 쓰러짐 | [Pig - Grunt and Squeal 2 - 96kHz.wav](https://freesound.org/s/233175/) — JarredGibb<br>[Body fall.wav](https://freesound.org/s/417994/) — DylanTheFish |
| `die_bone.ogg` | 뼈 무너짐 + 우르르 | [Falling Bones.wav](https://freesound.org/s/202091/) — spookymodem<br>[Clatter wood_11.wav](https://freesound.org/s/349273/) — deleted_user_2104797 |
| `die_boss.ogg` | 재의 군주 최후 붕괴 | Sonniss GDC 2026 — Federico Soler (Trailer Booms Vol. 2) + Epic Stock Media (Humanoid Creatures) |
| `die_goblin.ogg` | 도깨비 죽음 | [Goblin Death.wav](https://freesound.org/s/249813/) — spookymodem |
| `die_golem.ogg` | 골렘 거석 붕괴 | Sonniss GDC 2026 — Federico Soler (Trailer Booms) + Alexander Kopeikin (Designed Ice) |
| `die_knight.ogg` | 갑주 기사 쓰러짐·방패 쇠붙이 | Sonniss GDC 2026 — 344 Audio (Historical Weapons Vol. 2) + Cinematic Fight |
| `die_wolf.ogg` | 울음 + 쓰러짐 | [Small Dog Cry](https://freesound.org/s/735365/) — haulaway<br>[Body fall.wav](https://freesound.org/s/417994/) — DylanTheFish |
| `enh_fail.ogg` | 강화 실패: 파쇄 + 저음 하강 | Sonniss GDC 2026 — Alexander Kopeikin (100 kHz Designed Ice) + 344 Audio (Bass Drops) |
| `enh_ok.ogg` | 강화 성공: 모루 강철음 + 마법 부여 | Sonniss GDC 2026 — Epic Stock Media (HD Game Materials + Fantasy Game 2) |
| `equip.ogg` | 장비 장착: 가죽·갑주 버클 | Sonniss GDC 2026 — Epic Stock Media (Fantasy Game 2) + 344 Audio (Antique Small Metals) |
| `hit_flesh_1.ogg` | 묵직한 베임·살점 타격 | Sonniss GDC 2026 — Epic Stock Media (Halloween Game) + 344 Audio (Cinematic Fight) |
| `hit_flesh_2.ogg` | 타격 몸통 충격 | Sonniss GDC 2026 — 344 Audio (Cinematic Fight Vol. 1) + Epic Stock Media (Tower Defense) |
| `hit_flesh_3.ogg` | 묵직한 강타 충격 | Sonniss GDC 2026 — 344 Audio (Cinematic Fight Vol. 1) |
| `hit_metal_1.ogg` | 금속 검격 + 공명 | Sonniss GDC 2026 — David Dumais Audio (Melee Weapons Pack 2) |
| `hit_metal_2.ogg` | 중세 검 강철 베임 | Sonniss GDC 2026 — 344 Audio (Historical Weapons Vol. 2) + Cinematic Fight Vol. 1 |
| `hit_metal_3.ogg` | 강철 타격 + 묵직한 충격 | Sonniss GDC 2026 — 344 Audio (Historical Weapons Vol. 2) + Epic Stock Media (HD Game Materials) |
| `hurt.ogg` | 주인공 피격 짧은 신음 | Sonniss GDC 2026 — SoundBits (Vox Bestiae) + 344 Audio (Cinematic Fight) |
| `impact_heavy.ogg` | 거대 지면 강타·충격파 | Sonniss GDC 2026 — Federico Soler (Trailer Booms Vol. 2) + Cinematic Sound Design (Colossal Impacts) |
| `levelup.ogg` | 레벨 업 웅장한 울림 | Sonniss GDC 2026 — Epic Stock Media (Anime Game + Fantasy Game 2) + Federico Soler (Trailer Booms) |
| `loot.ogg` | 일반 전리품 금속 낙하 | Sonniss GDC 2026 — 344 Audio (Antique Small Metals) + Cinematic Sound Design (UI Elements) |
| `loot_rare.ogg` | 희귀·전설 전리품 성종 공명 | Sonniss GDC 2026 — Ivo Vicic (Church Bells) + Epic Stock Media (Fantasy Game 2) |
| `mob_boar.ogg` | 꿀꿀, 낮고 굵게 | [Pig - Grunt and Squeal 4 - 96kHz.wav](https://freesound.org/s/233177/) — JarredGibb |
| `mob_bone.ogg` | 뼈 덜그럭 | [Skeleton bones (game).wav](https://freesound.org/s/381859/) — cribbler |
| `mob_boss.ogg` | 재의 군주 출현 저음 위압 | Sonniss GDC 2026 — Cinematic Sound Design (Ultra Transitions & Impacts) |
| `mob_goblin.ogg` | 고블린 날카로운 포효 | Sonniss GDC 2026 — 344 Audio (Dinosaurs Vol. 1) |
| `mob_golem.ogg` | 골렘 거석 울림 | Sonniss GDC 2026 — 344 Audio (Haunting Ambiences Vol. 3) + Alexander Kopeikin (Designed Ice) |
| `mob_knight.ogg` | 발소리 + 칼 뽑음 | [Knight Right Footstep on Gravel 5 (With Chainmail)](https://freesound.org/s/384890/) — Ali_6868<br>[unsheath_sword.wav](https://freesound.org/s/107589/) — Qat |
| `mob_wolf.ogg` | 늑대 위협 으르렁 | Sonniss GDC 2026 — Epic Stock Media (Halloween Game) |
| `music_boss.ogg` | 우두머리 전투: 암흑 심연 드론 + 전장 뿔피리·전고 | Sonniss GDC 2026 — 344 Audio (Ghostly Presences) + Jake Fielding (Horn Braams) + Federico Soler (Trailer Booms) |
| `music_field.ogg` | 초원 사운드스케이프: 광활한 변경 공명 드론 | Sonniss GDC 2026 — Alexander Kopeikin (Emotion and Magic) + Just Sound Effects (Highlands of Norway) |
| `music_forest.ogg` | 숲 사운드스케이프: 신비로운 어둠 숲 토널 드론 | Sonniss GDC 2026 — Epic Stock Media (Strange Game Ambient Loops 3) |
| `music_ruins.ogg` | 폐허·협곡·제단 다크 앰비언트 사운드스케이프 | Sonniss GDC 2026 — 344 Audio (Ghostly Presences) + Alexander Kopeikin (Emotion and Magic) |
| `music_title.ogg` | 타이틀 다크 판타지 서곡 사운드스케이프 | Sonniss GDC 2026 — Alexander Kopeikin (Emotion and Magic) + 344 Audio + Jake Fielding (Horn Braams) |
| `music_town.ogg` | 마을 사운드스케이프: 먼 성종 + 따뜻한 공명 드론 | Sonniss GDC 2026 — Ivo Vicic (Church Bells) + Epic Stock Media (Ambient Loops 3) + Alexander Kopeikin |
| `music_victory.ogg` | 승리 여운: 평온한 성종 + 광휘 공명 | Sonniss GDC 2026 — Ivo Vicic (Church Bells) + Epic Stock Media (Ambient Loops 3 + Fantasy Game 2) |
| `npc_talk.ogg` | 대화 양피지 넘김 | Sonniss GDC 2026 — 344 Audio (Antique Books) |
| `pickup.ogg` | 천 쥐는 소리 | [GrabItemCloth.wav](https://freesound.org/s/609569/) — CJspellsfish |
| `player_die.ogg` | 주인공 쓰러짐 + 저음 낙하 | Sonniss GDC 2026 — Epic Stock Media (Humanoid Creatures) + 344 Audio (Bass Drops) |
| `potion.ogg` | 마개 + 꿀꺽 | [Cork pop 2](https://freesound.org/s/335358/) — Andre_Desartistes<br>[Potion - drink - swallow.wav](https://freesound.org/s/574077/) — ValentinPetiteau |
| `quest.ogg` | 퀘스트 완료 성종·축복 | Sonniss GDC 2026 — Ivo Vicic (Church Bells) + Epic Stock Media (Fantasy Game 2) |
| `return_cast.ogg` | 귀환 영창 | Sonniss GDC 2026 — Alexander Kopeikin (Emotion and Magic) |
| `revive.ogg` | 부활·회복 축복 | Sonniss GDC 2026 — Epic Stock Media (Fantasy Game 2) |
| `salvage.ogg` | 장비 분해: 결정 파쇄 | Sonniss GDC 2026 — Alexander Kopeikin (Designed Ice) + Epic Stock Media (Elemental Mutation) |
| `skill_arc_strike.ogg` | 연쇄 벼락: 고압 아크 방전 + 실녹음 천둥 | Sonniss GDC 2026 — InMotionAudio (Arc) + Epic Stock Media (Public Spaces Storm Thunder) |
| `skill_cry.ogg` | 전투의 함성: 중후한 전장 뿔피리 + 전사 함성 | Sonniss GDC 2026 — Jake Fielding (Cinematic Horn Braams) + Epic Stock Media (Humanoid Creatures) |
| `skill_ember_bolt.ogg` | 잿불 탄막: 맹렬한 화염 발사 | Sonniss GDC 2026 — Epic Stock Media (Elemental Mutation Whooshes and Impacts) |
| `skill_smash.ogg` | 강타: 지면 분쇄 붐 + 강철 타격 | Sonniss GDC 2026 — Federico Soler (Trailer Booms Vol. 2) + David Dumais Audio |
| `skill_spin.ogg` | 회전 베기: 쌍칼 강철 선풍 | Sonniss GDC 2026 — 344 Audio (Elemental Palette) + David Dumais Audio |
| `skill_wave.ogg` | 검기 방출: 칼날 에너지 파동 | Sonniss GDC 2026 — Epic Stock Media (Tower Defense) + Alexander Kopeikin (Emotion & Magic) |
| `swing_1.ogg` | 장검 고속 베기 | Sonniss GDC 2026 — David Dumais Audio (Melee Weapons Pack 2) |
| `swing_2.ogg` | 날카로운 검 휘두름 | Sonniss GDC 2026 — Epic Stock Media (Tower Defense Game) |
| `swing_3.ogg` | 마무리 강베기 | Sonniss GDC 2026 — David Dumais Audio (Melee Weapons Pack 2) |
| `swing_heavy.ogg` | 양손 대검·망치 중휘두름 | Sonniss GDC 2026 — 344 Audio (Elemental Palette) + David Dumais Audio |
| `ui_click.ogg` | 석조·쇠 걸쇠 버튼 클릭 | Sonniss GDC 2026 — Epic Stock Media (HD Lock & Mechanism) |
| `ui_close.ogg` | 고서 닫음 | Sonniss GDC 2026 — Cinematic Sound Design (Paper Foley) |
| `ui_deny.ogg` | 거절 묵직한 톡 | Sonniss GDC 2026 — Cinematic Sound Design (UI Interaction Elements) |
| `ui_open.ogg` | 고서 양피지 펼침 | Sonniss GDC 2026 — 344 Audio (Antique Books) |
| `ui_toggle.ogg` | 금속 스위치 토글 | Sonniss GDC 2026 — 344 Audio (Antique Small Metals) |
| `wave_fly.ogg` | 검기 비행 잔향 | Sonniss GDC 2026 — Alexander Kopeikin (Emotion and Magic) |
| `waypoint.ogg` | 거점석 순간이동 | Sonniss GDC 2026 — Cinematic Sound Design (Ultra Transitions) + Alexander Kopeikin (Emotion & Magic) |
| `whiff.ogg` | 허공 가르기 | Sonniss GDC 2026 — David Dumais Audio (Melee Weapons Pack 2) |
