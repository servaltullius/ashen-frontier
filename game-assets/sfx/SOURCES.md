# 소리 출처

웹 판(web/)이 녹음한 소리로 바꾼 자리들의 출처. 웹 판은 이 폴더에 `<자리>.ogg` 가 있으면 그것을 읽고(목록은 web/vite.config.js 가 폴더에서 만든다 — web/src/data/sound.ts 의 RECORDED), 없는 것은 assets/audio 의 합성 소리를 쓴다. assets/audio 는 동결된 Godot 판도 쓰므로 건드리지 않는다. 파일을 넣거나 빼면 아래 표도 고친다(검사 web/tests/sound.test.ts 가 폴더와 표가 같은지 본다).

- 재료는 모두 **Freesound** 의 **CC0**(조건 없음 — 출처 표기·재배포 제한 없음)이다. 고마움의 뜻으로 올린 사람을 적어 둔다.
- 재료는 Freesound 의 고음질 미리듣기(ogg)로 받아(`downloads/freesound/`, git 밖) 다듬었다: 쓸 덩어리만 떼고, 앞 고요를 자르고,
  필요하면 두 재료를 시간차를 두고 겹치거나 음높이를 바꾸고(늑대·멧돼지는 작은 짐승 녹음을 낮춤, 연타 1·2·3 은 조금씩 달리),
  끝을 줄이고, 지금 소리(합성)의 크기에 맞추고, 순간 최대값은 리미터로 눌렀다. 저장은 Ogg Vorbis(품질 6, 약 190kbps — wav 의 7분의 1).
- 주인공의 목소리(맞음·쓰러짐·함성)는 한 사람(Reitanna)의 녹음으로 맞췄다.

| 자리 | 무엇 | 재료(Freesound) |
|---|---|---|
| `amb_fire.ogg` | 모닥불 | [Bonfire](https://freesound.org/s/364992/) — forfie |
| `amb_forest.ogg` | 봄 오후의 숲 | [sfx_amb_forest_spring_afternoon-01.wav](https://freesound.org/s/385280/) — bajko |
| `amb_town.ogg` | 중세 마을 | [medieval_village_atmosphere.wav](https://freesound.org/s/578072/) — ramonmineiro |
| `amb_wind.ogg` | 잔잔한 들판 바람 | [Looping Gentle Wind Ambience on an Open Desert Plain.wav](https://freesound.org/s/697217/) — dhallcomposer |
| `arrow.ogg` | 시위 + 화살 바람 | [Bow_release.wav](https://freesound.org/s/263675/) — PorkMuncher<br>[FX - Swoosh - Light (High Pitch)](https://freesound.org/s/475137/) — bolkmar |
| `bolt.ogg` | 마법 탄 + 바람 | [Magic Spell](https://freesound.org/s/442774/) — qubodup<br>[woosh.wav](https://freesound.org/s/243400/) — freakinbehemoth |
| `boss_cast.ogg` | 두 주문 겹침 | [Demonic Anger, Dark Spell](https://freesound.org/s/527636/) — LilMati<br>[Necromancy Summoning Magic Spell](https://freesound.org/s/740776/) — qubodup |
| `boss_roar.ogg` | 포효 둘 겹침 | [Monster Roar 2.wav](https://freesound.org/s/398908/) — quadraslayer<br>[Demon_Lion_Monster_Growl_Roar](https://freesound.org/s/469123/) — Manim8 |
| `coin.ogg` | 돈주머니 | [Money Bag](https://freesound.org/s/338260/) — PhilSavlem |
| `dash.ogg` | 옷자락 바람 + 자갈 미끄러짐 | [Whoosh (Clothing Drag)](https://freesound.org/s/496188/) — JonasTisell<br>[Boots Gravel Feet Slide  1_5](https://freesound.org/s/504383/) — Joao_Janz |
| `die_boar.ogg` | 낮은 비명 + 쓰러짐 | [Pig - Grunt and Squeal 2 - 96kHz.wav](https://freesound.org/s/233175/) — JarredGibb<br>[Body fall.wav](https://freesound.org/s/417994/) — DylanTheFish |
| `die_bone.ogg` | 뼈 무너짐 + 우르르 | [Falling Bones.wav](https://freesound.org/s/202091/) — spookymodem<br>[Clatter wood_11.wav](https://freesound.org/s/349273/) — deleted_user_2104797 |
| `die_boss.ogg` | 죽음 + 바위 무너짐 | [Cyan Titan - Giant or Monster death sound 1A](https://freesound.org/s/748550/) — CyanKingstonLBP<br>[Rock Smash](https://freesound.org/s/512243/) — NeoSpica |
| `die_goblin.ogg` | 도깨비 죽음 | [Goblin Death.wav](https://freesound.org/s/249813/) — spookymodem |
| `die_golem.ogg` | 박살 + 쏟아짐 | [Rock Smash](https://freesound.org/s/512243/) — NeoSpica<br>[Bricks/Stones/Rocks/Gravel Falling](https://freesound.org/s/567249/) — iwanPlays |
| `die_knight.ogg` | 신음·쓰러짐 + 쇠붙이 | [Melee Weapon hit with male moan & body fall](https://freesound.org/s/264062/) — Paul368<br>[Metal drop Streetsign 1](https://freesound.org/s/581596/) — SamsterBirdies |
| `die_wolf.ogg` | 울음 + 쓰러짐 | [Small Dog Cry](https://freesound.org/s/735365/) — haulaway<br>[Body fall.wav](https://freesound.org/s/417994/) — DylanTheFish |
| `enh_fail.ogg` | 깨짐 + 쇠 튕김 | [Shatter.wav](https://freesound.org/s/56262/) — Q.K.<br>[Cracking, snapping, and clanging (metal can)](https://freesound.org/s/518731/) — Ashley12275 |
| `enh_ok.ogg` | 모루 + 반짝임 | [Anvil Hit 1](https://freesound.org/s/270589/) — michorvath<br>[Crystal Twinkle](https://freesound.org/s/639429/) — LaurenPonder |
| `equip.ogg` | 버클 + 옷 | [Belt Buckle](https://freesound.org/s/331719/) — IndigoRay<br>[ClothingEquip.mp3](https://freesound.org/s/396429/) — SoundEffEcks |
| `hit_flesh_1.ogg` | 주먹 + 베이는 소리 | [Realistic Punch](https://freesound.org/s/244513/) — JewTwinz<br>[Bloody Blade 2.wav](https://freesound.org/s/323526/) — Kreastricon62 |
| `hit_flesh_2.ogg` | 주먹 + 베이는 소리 | [Punch](https://freesound.org/s/434147/) — NeoSpica<br>[Bloody Blade 2.wav](https://freesound.org/s/323526/) — Kreastricon62 |
| `hit_flesh_3.ogg` | 묵직한 주먹, 낮게 | [Punch_1-2.wav](https://freesound.org/s/94778/) — taylorsyoung |
| `hit_metal_1.ogg` | 칼 부딪힘 + 주먹 타격 | [Sword Impact](https://freesound.org/s/733887/) — velcronator<br>[Punch](https://freesound.org/s/434147/) — NeoSpica |
| `hit_metal_2.ogg` | 칼싸움 부딪힘 + 타격 | [Sword clash 1.wav](https://freesound.org/s/471095/) — spycrah<br>[Realistic Punch](https://freesound.org/s/244513/) — JewTwinz |
| `hit_metal_3.ogg` | 짧은 칼 부딪힘 + 묵직한 주먹 | [Sword_Clash (7).wav](https://freesound.org/s/326868/) — JohnBuhr<br>[Punch_1-2.wav](https://freesound.org/s/94778/) — taylorsyoung |
| `hurt.ogg` | 짧은 신음 1 | [grunt.wav](https://freesound.org/s/242623/) — Reitanna |
| `impact_heavy.ogg` | 박살 + 모루 울림 | [Concrete SMASH 2](https://freesound.org/s/522099/) — magnuswaker<br>[Metallic Slam (Anvil)](https://freesound.org/s/841804/) — OOF9 |
| `levelup.ogg` | 바람 + 반짝임 | [ESE - WHOOSH - EPIC - Level Up.wav](https://freesound.org/s/475889/) — EpicSoundEffects<br>[Crystal Twinkle](https://freesound.org/s/639429/) — LaurenPonder |
| `loot.ogg` | 떨어짐 둘 겹침 | [drop-item-heavy2.mp3](https://freesound.org/s/693582/) — rottako<br>[Iron Bar Drop onto Wood & Straw Floor](https://freesound.org/s/213124/) — dkudos |
| `loot_rare.ogg` | 떨어짐 + 반짝임 | [drop-item-heavy2.mp3](https://freesound.org/s/693582/) — rottako<br>[Crystal Twinkle](https://freesound.org/s/639429/) — LaurenPonder |
| `mob_boar.ogg` | 꿀꿀, 낮고 굵게 | [Pig - Grunt and Squeal 4 - 96kHz.wav](https://freesound.org/s/233177/) — JarredGibb |
| `mob_bone.ogg` | 뼈 덜그럭 | [Skeleton bones (game).wav](https://freesound.org/s/381859/) — cribbler |
| `mob_boss.ogg` | 깊은 으르렁 | [Deep Monster Growl](https://freesound.org/s/222523/) — uagadugu |
| `mob_goblin.ogg` | 사나운 으르렁 | [Aggressive Imp Snarl](https://freesound.org/s/743298/) — ChuckChuckGoof |
| `mob_golem.ogg` | 우르릉 + 돌 갈림 | [Rock Rumble 1](https://freesound.org/s/869566/) — CAT-FOX_ALEX<br>[Stone,Block,Drag,Wood,Grind.wav](https://freesound.org/s/347149/) — Mediaman57 |
| `mob_knight.ogg` | 발소리 + 칼 뽑음 | [Knight Right Footstep on Gravel 5 (With Chainmail)](https://freesound.org/s/384890/) — Ali_6868<br>[unsheath_sword.wav](https://freesound.org/s/107589/) — Qat |
| `mob_wolf.ogg` | 으르렁 겹침 | [Beast Snarling](https://freesound.org/s/342204/) — Christopherderp<br>[Animal Dog Bark And Growl 01.wav](https://freesound.org/s/625501/) — abhisheky948 |
| `npc_talk.ogg` | 종이 바스락 | [Paper Rustle](https://freesound.org/s/353125/) — BenjaminNelan |
| `pickup.ogg` | 천 쥐는 소리 | [GrabItemCloth.wav](https://freesound.org/s/609569/) — CJspellsfish |
| `player_die.ogg` | 긴 신음 + 쓰러짐 | [groan.wav](https://freesound.org/s/242620/) — Reitanna<br>[Body fall.wav](https://freesound.org/s/417994/) — DylanTheFish |
| `potion.ogg` | 마개 + 꿀꺽 | [Cork pop 2](https://freesound.org/s/335358/) — Andre_Desartistes<br>[Potion - drink - swallow.wav](https://freesound.org/s/574077/) — ValentinPetiteau |
| `quest.ogg` | 퀘스트 완료 울림 | [Quest Complete](https://freesound.org/s/878605/) — Qvantor |
| `return_cast.ogg` | 주문 외움 | [Spellcast](https://freesound.org/s/455341/) — russscott1 |
| `revive.ogg` | 종소리 + 회복 | [Healing Spell Chime (Fantasy RPG)](https://freesound.org/s/876169/) — Assetsmith<br>[Heal Restore](https://freesound.org/s/878621/) — Qvantor |
| `salvage.ogg` | 쇠붙이 + 작은 깨짐 | [Metal Object Movement.wav](https://freesound.org/s/359135/) — TheMinkman<br>[Shatter.wav](https://freesound.org/s/56262/) — Q.K. |
| `skill_arc_strike.ogg` | 지직 + 벼락 | [Electrical Shock (Zap).wav](https://freesound.org/s/160421/) — BigKahuna360<br>[Closeup Thunder Strike 01](https://freesound.org/s/840628/) — loganzsound |
| `skill_cry.ogg` | 기합 + 낮은 바람(힘 모음) | [HYAH!.wav](https://freesound.org/s/343950/) — Reitanna<br>[FX - Swoosh - Low Pitch](https://freesound.org/s/475135/) — bolkmar |
| `skill_ember_bolt.ogg` | 불덩이 날아가 터짐 | [Short-Fireball-Woosh.flac](https://freesound.org/s/267887/) — wjl<br>[Fireball Explosion.wav](https://freesound.org/s/431174/) — Blankened |
| `skill_smash.ogg` | 묵직한 타격 + 칼 울림 | [GROSS IMPACT](https://freesound.org/s/641040/) — magnuswaker<br>[Sword Impact](https://freesound.org/s/733887/) — velcronator |
| `skill_spin.ogg` | 소용돌이 + 칼바람 | [FX - Swoosh Swirl](https://freesound.org/s/445963/) — Breviceps<br>[Swish Swipe Short](https://freesound.org/s/877976/) — Qvantor |
| `skill_wave.ogg` | 검기 + 바람 꼬리 | [sword slash energy wave](https://freesound.org/s/724716/) — greyfeather<br>[woosh.wav](https://freesound.org/s/243400/) — freakinbehemoth |
| `swing_1.ogg` | 칼바람 + 쇳소리 끝 | [Swish Swipe Short](https://freesound.org/s/877976/) — Qvantor<br>[FX - Swoosh - Knife (High Pitch)](https://freesound.org/s/475136/) — bolkmar |
| `swing_2.ogg` | 짧은 칼바람, 조금 높게 | [Swish Swipe Short](https://freesound.org/s/877976/) — Qvantor |
| `swing_3.ogg` | 칼바람 둘 겹침(마무리 타) | [Swish Swipe Short](https://freesound.org/s/877976/) — Qvantor<br>[FX - Swoosh - Low Pitch](https://freesound.org/s/475135/) — bolkmar |
| `swing_heavy.ogg` | 무거운 휘두름 + 낮은 바람 | [GASP_Swing_Heavy_3.wav](https://freesound.org/s/542017/) — Rob_Marion<br>[FX - Swoosh - Low Pitch](https://freesound.org/s/475135/) — bolkmar |
| `ui_click.ogg` | 나무 딸깍 | [Wooden Click](https://freesound.org/s/321083/) — BenjaminNelan |
| `ui_close.ogg` | 책 덮기 | [cm_samples_book_close.wav](https://freesound.org/s/123819/) — assrel |
| `ui_deny.ogg` | 나무 두드림 한 번 | [wood_knock.wav](https://freesound.org/s/66397/) — 110110010 |
| `ui_open.ogg` | 책장 넘김 | [Page Turn 01](https://freesound.org/s/397548/) — LilMati |
| `ui_toggle.ogg` | 스위치 딸깍 | [Light Switch (on / off)](https://freesound.org/s/457037/) — Breviceps |
| `wave_fly.ogg` | 바람 + 기운 | [woosh.wav](https://freesound.org/s/243400/) — freakinbehemoth<br>[ENERGY RISER 2](https://freesound.org/s/523057/) — magnuswaker |
| `waypoint.ogg` | 순간이동 | [Teleport](https://freesound.org/s/441225/) — LilMati |
| `whiff.ogg` | 빠른 바람 | [ESE - WHOOSH - QUICK - Movement C.wav](https://freesound.org/s/475896/) — EpicSoundEffects |
