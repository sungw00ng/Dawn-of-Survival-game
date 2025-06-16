# Dawn-of-Survival-game
- Unity와 AI를 활용한 3D 좀비 아포칼립스 게임 <br>

<img src="https://github.com/user-attachments/assets/ec6b12a1-c519-43d0-a42c-cdabb6311bd4" width="700"/><br>
<img width="700" alt="Image" src="https://github.com/user-attachments/assets/d7db94ae-c70f-4c87-ba62-4e8fd39fbed3" /> <br>

- SF 배경의 좀비 아포칼립스 게임을 제작 중이다.

## 시나리오 및 오브젝트 기획안
- [개발노트](https://github.com/sungw00ng/Dawn-of-Survival-game/blob/main/%EA%B0%9C%EB%B0%9C%20%EB%85%B8%ED%8A%B8.md) <br>


## MAP (구상안)
<image src="https://github.com/user-attachments/assets/18b2c80c-a202-4d26-8088-bf4c2f73427d" width="600"/><br>
- 빨간 원: Enemy Spown Point
- 녹색 원: Start Point


### MAP 1단계
- 타일 깔기 <br>
<img width="600" alt="스크린샷 2025-06-16 오후 5 28 15" src="https://github.com/user-attachments/assets/405e0f23-1369-4c3a-9759-39f2693530bd" /><br>


## player
### player-move
<img width="500" src="https://github.com/user-attachments/assets/7d5c1dea-89ca-4596-9695-40a0737ededb" /><br>
- run에는 헤드밥 효과 등을 넣어 뛸 때 생동감을 부여하였다.
  
### player-Animator
<img width="700" alt="Image" src="https://github.com/user-attachments/assets/6d366fb9-36df-4e47-8b33-ad9ea44b6ec0" /><br>
<img width="700" alt="Image" src="https://github.com/user-attachments/assets/41e1c0d6-cb09-40c8-928b-c4abe0eb18e2" /><br>

- Mixamo에서 .fbx파일로 변환 후에 이미 rig가 있는 캐릭터에 한해서는 <br>
애니메이션 동작을 만들어준다는 점에서 큰 도움을 받고 있다. <br>

## Enemy AI
<img width="500" src="https://github.com/user-attachments/assets/1bd2a23e-1ff3-4965-8d6e-47b125c8af90" /><br>
- Mesh Agent, AI Mesh Navigation-Bake 사용하여, 플레이어 추적 및 공격 범위 설정

## 1. Mutant
<img width="500" src="https://github.com/user-attachments/assets/01384836-251a-4c01-9593-dcb56adad5ee" /><br>
<image src="https://github.com/user-attachments/assets/b50c381b-baa3-4119-8ef9-536c321fb661" width="400"/><br>


## Object
### 탄약 상자
<img width="500" alt="탄약상자" src="https://github.com/user-attachments/assets/3f1eae91-0c3f-4a34-8161-5ce0824aa97f" /><br>
<img width="500" alt="탄약상자2" src="https://github.com/user-attachments/assets/c8b4cf84-2274-4d23-89b9-ac64d3616a75" /><br>

- 현재 사용 가능한 탄약이 100 오른다.
- E 키를 눌러 상호 작용 후 탄약 상자 오브젝트가 파괴됨.

## Assets
### Gun
[Sci-Fi Gun Light](https://assetstore.unity.com/packages/3d/props/guns/sci-fi-gun-light-87916) <br>
[Crosshairs](https://assetstore.unity.com/packages/2d/gui/icons/crosshairs-216732) <br>
[Weapons Pack - Bullets](https://assetstore.unity.com/packages/3d/props/weapons/weapons-pack-bullets-302702) <br>

### Map
[공상 과학 창고 건설 키트 (모듈 식)](https://assetstore.unity.com/packages/3d/environments/sci-fi/sci-fi-construction-kit-modular-159280)

### Character
[Low Poly Medieval Characters Lite](https://assetstore.unity.com/packages/3d/characters/humanoids/low-poly-medieval-characters-lite-316247)

### Sound
[M4 돌격소총 사격, 장전](https://assetstore.unity.com/packages/3d/props/guns/stylized-m4-assault-rifle-with-scope-complete-kit-with-gunshot-v-178197)

### Enemy(Mixamo)
- [Mutant](www.mixamo.com)

