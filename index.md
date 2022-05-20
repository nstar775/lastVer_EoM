# ProJect Name : 《Estate Escape》   

## ▶목차
#### 1. [컨셉](#-concept)
#### 2. [관련 이미지/영상](#-related-images--videos)
#### 3. [대표이미지](#-representative-image)
#### 4. [작품묘사](#-describe-the-concept--representative-image)
#### 5. [게임 요소](#-escape-to-memorys-ingredients)
   - [메커니즘](#1mechanism)
   - [스토리](#2story)
   - [미적요소](#3art-factor)   
       
#### 6. [기술](#-technology)
#### 7. [시스템](#-system)
#### 8. [스토리보드](#-storyboard)

_________________________________________________________________________________
    
# ▷ Concept
### ☞ Main Concept
 - Escape (탈출)
   <pre>설명 : 단서를 수집하고 추리하여 퍼즐을 풀어 탈출합니다.</pre>    
			
### ☞ Sub concept1
 - Old mansion (오래된 저택)
     <pre>설명 : 게임 내 공간적 배경으로 플레이어가 탈출할 장소입니다.</pre>     
			
### ☞ Sub concept2
 - Puzzle (퍼즐)
     <pre>설명 : 게임을 진행하기 위해 여러 난관이 되는 퍼즐을 풀어 해쳐 나가는 게임입니다.</pre>        
			
### ☞ Sub concept3
 - Reasoning (추리)
     <pre>설명 : 유저는 퍼즐을 풀기위해 게임 중 얻은 여러 단서들을 통해 추리해야만 합니다.</pre>

    
-------------------------------------------------------------------------------
    
# ▷ Related Images & Videos

> - Images   
![image](https://user-images.githubusercontent.com/63893895/168222054-f4a2e242-9197-4217-850a-7210e88acf29.png)

   
> - Videos   
 <iframe width="632" height="356" src="https://www.youtube.com/embed/-pHsFDiRqOM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 
  
------------------------------------------------------------------------------

# ▷ Representative image
![image](https://user-images.githubusercontent.com/63893895/139111967-f8332f51-23b3-49bc-9e1b-6a987f91a88b.png)

------------------------------------------------------------------------------

# ▷ Describe the concept & representative image
  - 한줄묘사 :  숨겨진 단서와 이야기를 찾아 닫힌 문을열고 나아가는 퍼즐게임 (수정중)
------------------------------------------------------------------------------    

# ▷ 《Escape in Memory》's Ingredients
### 1.Mechanism    
  [도전과제]    
  <pre> 
① 숨겨진 퍼즐들을 찾아보아라!
② 퍼즐들을 풀어가며, 앞으로나아가라!
③ 숨겨진 단서들을 이용하여 눈앞의 시련을 뛰어넘어라!
④ 숨겨진 이야기를 찾아보아라
</pre>   

  [재미요소]   
<pre> ① 숨겨진 이야기의 대한 단서들을 따라가 새로운 이야기를 유추해 볼 수도 있다.
② 여러 단서들과 기믹들로 퍼즐을 풀수 있다.
③ 퍼즐을 얼마나빠르고 정확하게 푸는지 시험해 볼 수 있다.</pre>    
 
  [카메라 관점]
<pre>3인칭 3D게임으로 전지적시점이 베이스로 캐릭터의 뒷모습을 보며 이동합니다.
마우스를 통해 유저 케릭터를 중심으로 카메라를 이동시킬수 있습니다.</pre>
  
  [키 조작]
  <pre> WASD키 = 이동
 Space Bar = 점프
 F키 = 상호작용키
 Shift키 = 달리기</pre>

### 2.Story
  [만들게 된 배경]
  <pre> 쉽고 누구나 즐길 수있는 3D 방탈출이 있을까? 하고 생각하며,
  가볍게 스토리도 함께 즐기며, 하나의 엔딩이 아닌 여러 엔딩이 있는 가벼운 방탈출을 생각해내어
  만들어 보게 되었습니다.</pre>

 [참신함]
 <pre> ① 단일 다른 방탈출과는 다른 엔딩이 여러가지인 방탈출 게임
② 아이템을 저장하여 그때그때 사용하는 것이 아닌 필드 위 단서들을 풀어 나아가며, 상호작용을 하여 퍼즐을 해결하는 점. </pre>

### 3.Art factor
 [디자인]
 - 시각적요소 
 <pre>① 저택의 분위기에 어울리도록 고급스러운 인테리어 디자인.
③ 현대적, 미래적이면서도 중대시대를 걷는 느낌의 분위기 연출</pre>    

 - 청각적 요소    
 <pre> ① 약간의 공포감혹은 몽환적인 사운드 구성 예정.
 ② 주로 실사 사운드로 구성합니다. </pre>

------------------------------------------------------------------------------   

# ▷ Technology
<pre> Unity Engine을 기반으로한 1인칭 솔로 플레잉 게임으로 진행</pre> 

------------------------------------------------------------------------------     

# ▷ System
 - 게임 오브젝트 분해 (구성 요소 분석)

|이름|이미지|
|-----|-----|
|키아이템|[준비예정]|
|캐릭터|[준비예정]|
|장해물|![제목 없음](https://user-images.githubusercontent.com/63893895/145313792-33e34c45-ea75-47da-a542-f0e7396cc0fb.png)|

- 파라미터(속성) 뽑아 보기

|이름|영어명칭|설명|비고|
|------|----|----|----|
|키아이템|item_OOO|스테이지당 핵심이 될수 있는 아이템.|
|캐릭터|Player/NPC_OOO|캐릭터 오브젝트는 플레이어와  NPC로 나뉘며, 캐릭터는 유저가움직일수 있으며,  NPC와는 상호작용을 할 수 있다.||
|장해물|Trap_OOO|플레이어에게 피해를 입히거나 진행에 방해를 주는 요소이다.||

------------------------------------------------------------------------------     

# ▷ [Storyboard](/Storybord.md)
   - [스토리보드 개별 문서 참고](/Storybord.md)
  
