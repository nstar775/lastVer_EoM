<pre>※ 주의 사항 : 새로 추가된 요소에는 【♨】가 붙어있습니다. </pre>
# ProJect Name : 《Escape in Memory》  :  Progress
##### [index로 돌아가기](/index.md)

## ▶목차
#### A. [개발일정](#-development-schedule)    

#### B. [요구 사항](#-requirements)

#### 1. [1주차](#-1st-week-progress)    
 > [1주차 목표](#1주차-목표)    
 > [1주차 작업결과](#1주차-작업-결과)     
       
#### 2. [2주차](#-2st-week-progress)         

#### 3. [3주차](#-3st-week-progress)         

#### 4. [4주차](#-4st-week-progress) 

#### 4. [5주차](#-5st-week-progress) 

#### 4. [6주차](#-6st-week-progress) 

_________________________________________________________________________________
# ▷ Development Schedule
 ![image](https://user-images.githubusercontent.com/63893895/139181974-c682eb1b-64b8-40ba-acde-3b16de658fcd.png)

    
# ▷ Requirements
#### 게임 요구사항
   ~~1. 시작화면,게임화면,엔딩화면으로 3개의 화면이 있다.~~    
   2. 엔딩 수는 10개 이므로 총 12개의 Scean으로 구성된다. (시작화면,게임화면,엔딩화면,Bad End 4개, Nomal End 2개, Another End 5개)    
   ~~3. 시작화면에는 Start,Ending, Exit 총 3개의 버튼이 있다.~~    
   4. Ending을 누르면 현재까지 본 엔딩항목을 볼수 있다.    
   5. Ending 화면에서 볼수있는 엔딩 항목에는 해금된 엔딩은 엔딩제목이 흰색 글씨로표시 되고, 미해금된 엔딩은 미해금 엔딩이라고나온다.    
   6. Ending 화면에서는 엔딩 항목에 있는 해금된 엔딩을 누르면 엔딩장면을 다시 볼 수 있다.    
   7. Ending 화면에서 우측상단의 돌아가기버튼을 누르면 시작화면으로 돌아온다.    
   ~~8. Exit를 누르면 게임 프로그램이 종료된다.~~    
   ~~9. 시작 화면에서 Start버튼을 클릭하면 게임화면으로 변경된다.~~    
   10. 게임화면에는 기본적으로 아무것도 나오지 않으나, 특정 오브젝트와 일정한 거리 다가갈시 상호작용메세지가 중앙에 작게 나온다.         
   ~~11. 스테이지는 있으나, 특별한 구별은 없고 모든 스테이지 맵은 이어져있고, 특정 조건을 맞출시 막혀있는 문이 열리는 구조이다.~~     
   ~~12. 스테이지에 진입하면 문이 닫힌다.~~     
   ~~13. 조작은 키보드의 WASD로 W는 전진, S는 후진하며, A는 좌, D는 우측 방향으로 이동이가능하다.~~             
   ~~14. 마우스로 플레이어가 보고 있는 시점이동이 가능하며, 마우스 휠을 드래그하면 확대, 축소 또한 가능하다.~~         
   15. ~~Shift는 달리기이고 속도가 3증가하고, Space Bar는 점프이며, F키는 상호작용키 이다.~~     
   16. NPC오브젝트와 상호작용시, 게임화면 하단에 대화창이 출력된다. 이때, F키를 누르면 대화창을 넘길 수 있다.        
   17. 단서는 특정 이벤트 달성시, 자동으로 해금(습득) 한다.      
   18. 단서를 모두 모으면 히든 엔딩을 볼수 있는 길로 가는 숨겨진 통로로 가는 길이 열린다. 하지만 통과할수 있는 벽으로 그냥 지나칠 수도 있게한다.     
   ~~19. 2스테이지에서 일정 구간 동안은 시아를 어둡게 제한한다.~~      
   ~~20. 1스테이지에서 주는 횃불이 어두운 구간에서 일정 범위만 길을 빛추게 한다.~~     
   21. 구간에 진입시 이벤트가 발생하는 구간이 있다.     
   22. 엔딩장면까지 다 보면 시작화면으로 돌아오고, 엔딩화면에 있는 엔딩항목에 엔딩장면이 해금된다.     
   ~~23. 카메라는 플레이어의 3인칭으로 하며, 마우스로 카메라 회전이 가능하다.~~     
   ~~24. 카메라가 회전했을 때, W를 눌러 앞으로 가면 카메라가 보는 방향으로 케릭터가 회전하며, 케릭터가 이동하도록한다.~~     
    
#### 그래픽 요구사항
   ~~1. 횃불은 플레쉬 장난감이라는 설정이므로 불부분이 무드등 같이 빛나는 효과를 주도록 한다.~~     
   2. 게임의 엔딩에서는 2D 그림을 보여주며 간단한 만화형식으로 한장한장 지나가는 식으로 한다.      
   3. 케릭터는 3D캐릭터로 구현한다.     
   ~~4. 아이템은 3D로 구현하되 아이콘은 따로없다.~~     
   ~~5. 메인화면과,  게임 로고가 있다.~~     
    
#### 추가 요구사항
   ~~1. Loading Scean을 추가, 게임 시작할때, 로딩이나오며 로딩이 끝나면 아무키를 눌러 게임화면을 보이게 합니다.~~
   ~~2. 아이콘을 추가합니다.~~
   ~~3. 카메라를 3인칭에서 1인칭으로 바꿉니다.~~
   4. 유저가 스토리를 유추해낼만한 단서 및 오브젝트 추가
   5. 스토리 요소 추가
    
_________________________________________________________________________________
    
# ★ 1st week progress

## 1주차 목표
### 작업명 : 메인화면 구성 및, 플레이어 이동및 간단한 조작.

#### 해당 요구사항 :
    1. 시작화면,게임화면,엔딩화면으로 3개의 화면이 있다.
    3.시작화면에는 Start,Ending, Exit 총 3개의 버튼이 있다
    8. Exit를 누르면 게임 프로그램이 종료된다.
    9. 시작 화면에서 Start버튼을 클릭하면 게임화면으로 변경된다.
    13. 조작은 키보드의 WASD로 W는 전진, S는 후진하며, A는 좌, D는 우측 방향으로 이동이가능하다.
    15. Shift는 달리기이고 속도가 3증가하고, Space Bar는 점프이며, F키는 상호작용키 이다.
    

#### 작업내용 :
    1, Scean을 3개 만든다. (Scean의 이름은 각각 Main, Start, Ending_Gallery로한다.) 엔딩은 엔딩을 구현할때 만들도록 한다.

    2. Main Scean에서 게임 로고와 Start, Ending, Exit 버튼을 만들어준다. (게임로고는 후작업이므로 텍스트로 대체한다.)

    3. Start를 누르면 Start Scean으로 이동하게 하고, Ending을 누르면  Ending_Gallery Scean으로 이동하게 하며, Exit를 누르면 프로그램이 종료 되도록 한다.

    4. 플레이어의 이동을 구현한다. W를 누르면 플레이어가 보는 방향의 앞으로, S를 누르면 뒤로, A를 누르면 왼쪽으로, D를 누르면 우측으로 이동하게 한다.

    5. Shift를 눌렀을 때, 보통 속도 보다 조금 더 빠르게 한다.

    6. Space Bar를 눌렀을 때는 점프를 하되, 공중에서는 비활성화, 땅의 착지했을 시에 다시 활성화 하는 형식을 띄게 한다.

## 1주차 작업 결과 

### 작업 이미지 및 코드
#### ○ 메인 화면
 ![Main](https://user-images.githubusercontent.com/63893895/139079899-9dacecda-55c0-409e-ad82-35bd8b0c719f.png)
 
##### ▼〔 MainMenu.cs 〕▼
```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;

public class MainMenu : MonoBehaviour
{
    public void OnClickStart()
    {
        Debug.Log("게임을 시작합니다.");
        SceneManager.LoadScene("Loading");
    }

    public void OnClickEnding()
    {
        Debug.Log("엔딩 겔러리를 엽니다.");
        SceneManager.LoadScene("Ending_Gallery");
    }

    public void OnClickExit()
    {
        Debug.Log("게임을 종료합니다.");
        Application.Quit();
    }
}
```

#### ○ 로딩♨    
 ![Loading_Scene](https://user-images.githubusercontent.com/63893895/139085141-440aaac8-55d7-4cc6-b25e-b5c03ec12a7c.gif)

##### ▼〔 SceneLoader.cs 〕▼
```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.UI;
using UnityEngine.SceneManagement;

public class SceneLoader : MonoBehaviour
{
    public Slider progressbar;
    public Text loadtext;
    public static string loadScene;

    private void Start()
    {
        StartCoroutine(LoadScene());
    }

    IEnumerator LoadScene()
    {
        yield return null;
        AsyncOperation operation = SceneManager.LoadSceneAsync("Start");
        operation.allowSceneActivation = false;

        while (!operation.isDone)
        {
            yield return null;
            if (progressbar.value < 0.9f)
            {
                progressbar.value = Mathf.MoveTowards(progressbar.value, 0.9f, Time.deltaTime);
            }else if(operation.progress >= 0.9f)
            {
                progressbar.value = Mathf.MoveTowards(progressbar.value, 1f, Time.deltaTime);
            }

            if(progressbar.value >= 1f)
            {
                loadtext.text = "Press AnyKey";
            }

            if (Input.anyKeyDown && progressbar.value>= 1f && operation.progress >= 0.9f)
            {
                operation.allowSceneActivation = true;
            }
        }
    }
}
```
                         
#### ○ 카메라 움직임 관련       
 ![카메라 ](https://user-images.githubusercontent.com/63893895/139088751-6390b093-4194-416c-bfd5-43b8eb064ca2.gif)

##### ▼〔 CameraController.cs 〕▼
```csharp
using UnityEngine;

public class CameraController : MonoBehaviour
{
    [SerializeField]
    private Transform target;
    [SerializeField]
    private float minDistance = 3;
    [SerializeField]
    private float maxDistance = 30;
    [SerializeField]
    private float wheelSpeed = 500;
    [SerializeField]
    private float xMoveSpeed = 500;
    [SerializeField]
    private float yMoveSpeed = 250;

    private float yMinLimit = 5;
    private float yMaxLimit = 80;
    private float x, y;
    private float distance;

    private void Awake()
    {
        distance = Vector3.Distance(transform.position, target.position);

        Vector3 angles = transform.eulerAngles;
        x = angles.y;
        y = angles.x;
    }

    private void Update()
    {
        if (target == null) return;

       //카메라 움직임
            x += Input.GetAxis("Mouse X") * xMoveSpeed * Time.deltaTime;
            y -= Input.GetAxis("Mouse Y") * yMoveSpeed * Time.deltaTime;

            y = ClampAngle(y, yMinLimit, yMaxLimit);

            transform.rotation = Quaternion.Euler(y, x, 0);
        distance -= Input.GetAxis("Mouse ScrollWheel") * wheelSpeed * Time.deltaTime; //마우스 휠로 줌 인/아웃
        distance = Mathf.Clamp(distance, minDistance, maxDistance);
    }
    
    private void LateUpdate()
    {
        if (target == null) return;

        transform.position = transform.rotation * new Vector3(0, 0, -distance) + target.position;
    }

    private float ClampAngle(float angle,float min, float max) //앵글 락
    {
        if (angle < -360) angle += 360;
        if (angle > 360) angle -= 360;

        return Mathf.Clamp(angle, min, max);
    }
}
```            
    
#### ○ 이동관련    
![이동1](https://user-images.githubusercontent.com/63893895/139097241-4b538dd8-5eb6-4fa5-8ec1-8eb87ae1eff1.gif)
![이동2](https://user-images.githubusercontent.com/63893895/139097235-10c05584-533f-4030-925a-6854be5f8789.gif)

##### ▼〔 Movement3D.cs 〕▼    
```csharp
     using UnityEditor;
     using UnityEngine;

     public class Movement3D : MonoBehaviour
     {
         [SerializeField]
         private float moveSpeed = 5;
         private Vector3 moveDirection;
     
         [SerializeField]
         private float gravity = -9.81f;
         [SerializeField]
         private float jumpForce = 3.0f;

         private CharacterController CharCtrler;

         public float MoveSpeed 
         {
             set => moveSpeed = Mathf.Clamp(value, 4.0f, 9.0f);
         }

         private void Awake()
         {
             CharCtrler = GetComponent<CharacterController>();
         }
     
         private void Update()
         {   
             if( CharCtrler.isGrounded  == false)
             {
                 moveDirection.y += gravity * Time.deltaTime;
             }

             CharCtrler.Move(moveDirection * moveSpeed * Time.deltaTime);
         }
      
         public void MoveTo (Vector3 direction)
         {
             moveDirection = new Vector3(direction.x, moveDirection.y, direction.z);
         }
     
         public void JumpTo()
         {
             if(CharCtrler.isGrounded == true)
             {
                 moveDirection.y = jumpForce;
             }
         }

     }
```


##### ▼〔 PlayerCtrler.cs 〕▼

```csharp
  using UnityEngine;

public class PlayerCtrler : MonoBehaviour
{
    [SerializeField]
    private KeyCode jumpKeyCode = KeyCode.Space;
   [SerializeField]
    private Transform cameraTransform;
    private Movement3D movement3D;

    private void Awake()
    {
        Cursor.visible = false;
        Cursor.lockState = CursorLockMode.Locked;

        movement3D = GetComponent<Movement3D>();
    }

    private void Update()
    {
        float x = Input.GetAxis("Horizontal");
        float z = Input.GetAxis("Vertical");

        if (Input.GetKeyDown(KeyCode.LeftShift))
        {
            movement3D.MoveSpeed = z > 0 ? 8.0f : 7.0f;
        }
        else if (Input.GetKeyUp(KeyCode.LeftShift))
        {
            movement3D.MoveSpeed = z > 0 ? 5.0f : 4.0f;
        }

        movement3D.MoveTo(cameraTransform.rotation * new Vector3(x, 0, z));

        //회전설정
        transform.rotation = Quaternion.Euler(0, cameraTransform.eulerAngles.y, 0);

        if( Input.GetKeyDown(jumpKeyCode))
        {
            movement3D.JumpTo();
        }
    }

}
``` 

#### ※ 추가 및 변경 된 사항
- 요구사항에 따로 없던 Loading Scene을 추가 하였습니다. Start버튼을 누르면 Loading Scene으로 이동하며, 다음 맵을 로드 합니다.    
  로딩이후 아무 키를 누르면, 게임 화면(Start Scene)으로 이동합니다.
- 요구사항 14번 항목이 이동하는 요소에 포함 되어 이번주차에 미리 구현 하였습니다.
<pre>14.마우스로 플레이어가 보고 있는 시점이동이 가능하며,마우스 휠을 드래그하면 확대, 축소 또한 가능하다.</pre>
  _________________________________________________________________________________
    
# ★ 2st week progress
### 2주차 목표

### 작업명 : 메인화면 구성 및, 플레이어 이동및 간단한 조작.

#### 해당 요구사항 :
2. 게임의 엔딩에서는 2D 그림을 보여주며 간단한 만화형식으로 한장한장 지나가는 식으로 한다.    
4. 아이템은 3D로 구현한다.    
5. 로고 구현    

#### 작업내용 :
1. 게임 로고를 작성한다. (80%)
2. 아이템을 3D로 직접 만들거나, 오픈소스를 찾는다.(50%)
3. 2번항목에 필요한 엔딩 일러스트를 그린다. (10%)

### 2주차 작업 결과 :

  -그래픽 작업    
  ![image](https://user-images.githubusercontent.com/63893895/140087629-6eb9dac9-9842-4e92-99e4-b85c795adb07.png)    
  > 스케치 단계로, 추후 제목이 "Escape of Memory"에서 "Escape in Memory" 변경됨.
  >> 이유: 영어 뜻이 이상해 지기 때문에, 변경하였음.   
  
  ![image](https://user-images.githubusercontent.com/63893895/140088146-32e4c3e4-b976-4515-930b-921afb2dc51f.png)
  ![image](https://user-images.githubusercontent.com/63893895/140238059-6e6bee5a-becf-4a16-a543-75791c4c6b5a.png)

 출처
 > [에셋스토어] | [Torchlight](https://assetstore.unity.com/packages/3d/props/old-hand-torch-156928#description)    
 > [에셋스토어] | [Piano](https://assetstore.unity.com/packages/3d/props/15-low-poly-models-202061)    

_________________________________________________________________________________
    
# ★ 3st week progress
### 3주차 목표   

#### 작업명 : 맵과 케릭터 구현    

 - 게임
     10. 게임화면에는 기본적으로 아무것도 나오지 않으나, 특정 오브젝트와 일정한 거리 다가갈 시 상호 작용 메세지가 중앙에 작게 나온다.
     11. 스테이지로 구분되나, 특별한 구별은 없고 모든 스테이지 맵들은 이어져있고, 특정 조건을 맞출 시 막혀있는 문이 열리는 구조이다.
     19. 2스테이지에서 일정 구간 동안은 시야를 어둡게 제한한다.
     20. 2스테이지에서 주는 횃불이 어두운 구간에서 일정 범위만 길을 비추게 한다. 

 - 그래픽
     3. 케릭터는 3D캐릭터로 구현한다.
     4. 아이템은 3D로 구현하되 아이콘은 따로없다.
     5. 메인화면과,  게임 로고가 있다.

#### 작업 내용 : (구체적 작업)

    1. 3D 프로그램으로 케릭터를 구현하는 작업을 시작한다. (0%)
    2. 맵을 구상하고 만든다. (15% - 전체 4스테이지 중 1스테이지)
    3. 특정 구간에서 시야를 어둡게 만든다. (0% 2스테이지 내용이므로 다음 주차)
    4. 엔딩 2D 일러스트 씬을 계속해서 구상하도록한다. (50% 스케치뿐이므로 미루어짐.)
    5. 일부 아이템에 상호작용이 되게 한다. (5% 아직 스크립트 작성 중)

### 3주차 작업 결과 :

![image](https://user-images.githubusercontent.com/63893895/141150809-4d366fc2-779a-4122-a838-a621539b0f75.png)

<iframe width="1020" height="574" src="https://www.youtube.com/embed/yNXEv3_3xY4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

_________________________________________________________________________________
    
# ★ 4st week progress
### 4주차 목표

#### 작업명 : 아이템 간 상호작용 및 퍼즐 제작

##### 해당 요구사항 : 
<pre>
    6. 게임화면에는 기본적으로 아무것도 나오지 않으나, 특정 오브젝트와 일정한 거리 다가갈시 상호작용메세지가 중앙에 작게 나온다.    
    7. 스테이지는 있으나, 특별한 구별은 없고 모든 스테이지 맵은 이어져있고, 특정 조건을 맞출시 막혀있는 문이 열리는 구조이다.    
    11. 단서는 특정 이벤트 달성시, 자동으로 해금(습득) 한다.
    </pre>

##### 작업 내용 :
  - 첫번째 스테이지의 첫번째 방의 퍼즐 구상 및 구현
  - 첫번째 스테이지의 두번째 방의 피아노 퍼즐 구현 
  - 첫번째 스테이지의 세번째 방의 퍼즐을 구현
  - 저번 주차에서 미흡했던 부분 보안 ( 엔딩 일러스트 구현 , 카메라가 벽을 통과하는 문제 해결)
  - 두번째 스테이지 맵 구상 및 구현 ( 맵에 대한 이벤트는 다음 주차 )

##### 작업결과
  1. 첫번째 방 퍼즐을 구상 했으나 완벽히 구현 하지는 못함. => 필요한 물리와 온트리거엔터 이벤트를 제대로 활용하지 못함.    
  2. 방의 문을 구현 하였습니다.    
  3. 두번째 스테이지의 절반 정도를 구상하였고, 나머지 절반은 구상중입니다.    
       
 ![image](https://user-images.githubusercontent.com/63893895/142281487-722f312f-fb8f-4670-b15f-7ac4cbb2dde7.png)    <br>
   - 2스테이지 구상도. 노란화살표는 가짜 길, 붉은 색은 진행로, 흰색은 숨겨진 길입니다. 50%정도 입니다.    <br>    

<iframe width="1020" height="574" src="https://www.youtube.com/embed/nzb07veJ-Fw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  - 카메라는 1인칭으로 변경예정입니다. 현재 개발의 편의를 위해 당장 바꾸지 않을 예정입니다.
  - 숨겨진 길은 투명한 길로 이루어져 있습입니다. 추후 숨겨놓은 방으로 가는 투명한 길에 낙하방지 투명벽을 설치 할 예정이며, 해당 길은 콜라이더가 존재하지 않는 벽으로 막아 숨겨 놓을 예정입니다.
  - 중간의 가늘고 긴 발판이 많은 구간에는 중간 중간 가짜 발판이 숨겨져 있습니다.
  - 물리적용이 이상하여 퍼즐을 풀떄 필요한 큐브가 잘 뭄직이지 않으나 아예 움직이지 않는 것은 아닙니다.

_________________________________________________________________________________
    
# ★ 5st week progress
### 5주차 목표
##### 작업명 : 마무리 전 단계(1스테이지 마무리)

##### 해당 요구사항 : 
<pre>
  6. 게임화면에는 기본적으로 아무것도 나오지 않으나, 특정 오브젝트와 일정한 거리 다가갈시 상호작용메세지가 중앙에 작게 나온다. 
  7. 스테이지는 있으나, 특별한 구별은 없고 모든 스테이지 맵은 이어져있고, 특정 조건을 맞출시 막혀있는 문이 열리는 구조이다.
  10. 게임화면에는 기본적으로 아무것도 나오지 않으나, 특정 오브젝트와 일정한 거리 다가갈 시 상호 작용 메세지가 중앙에 작게 나온다.
  11. 스테이지로 구분되나, 특별한 구별은 없고 모든 스테이지 맵들은 이어져있고, 특정 조건을 맞출 시 막혀있는 문이 열리는 구조이다.
  17. 단서는 특정 이벤트 달성시, 자동으로 해금(습득) 한다.
  19. 2스테이지에서 일정 구간 동안은 시야를 어둡게 제한한다.
  20. 2스테이지에서 주는 횃불이 어두운 구간에서 일정 범위만 길을 비추게 한다.
   </pre>

##### 작업 내용 :
 1. 월드를 어둡게 하고, 전구로 밝히는 형식을 취한다. 횃불도 파티클과 발광이벤트를 활용하여 빛이 나게 한다. (98%)
 2.  2스테이지 맵를 완성 시킨다. (100%)
 3.  1스테이지의  퍼즐(첫번째방,피아노방, 횃불방)을 완성시킨다. (95%)
 4.  카메라를 1인칭으로 바꾼다. (0%)
 5.  몬스터를 구현하고 특정 발판을 만들어 그 발판을 누름으로써 스테이지 문이 열리고, 몬스터가 멈추게 한다 (0%)


##### 작업결과 :
 
 1. 월드를 최대한 어둡게 하고, point light 를 이용하여 맵을 밝히고 같은 방식으로 횃불에도 해당 작업을함.
 2. 첫번째 방은 Cube에서 Sphere로, 갯수는 4개에서 1개로, 버튼은 그대로 4개로 하여 공을 굴려 버튼을 밟게 하도록 하는 퍼즐로 변경하였음.
 3. 피아노 퍼즐을 완성하였으나, 아직 BGM관련 Audio는 아직까지 출력은 안되며, 세번째 방, 눈사람을 근처에 가서 횃불을 나타나게 하는 건 되었으나, 아직 드는 것 까진 구연하지 못함.

<iframe width="1020" height="574" src="https://www.youtube.com/embed/ADv0NI-d6T0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

##### ▼〔 Piano.cs 〕▼

```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Piano : MonoBehaviour
{
    [SerializeField]
    GameObject PianoPanel;

    [SerializeField]
    GameObject gameManager;

    [SerializeField]
    GameObject player;

    Stage01_2 stg01_2;

    bool isPlayPiano = false;
    public int openCount = 0;


    private void Start()
    {
        player = GameObject.FindGameObjectWithTag("Player");
        stg01_2 = gameManager.GetComponent<Stage01_2>();
        
    }


    private void OnTriggerStay(Collider other)
    {
        if (other.gameObject == player)
        {
            if (Input.GetKey(KeyCode.F))
            {
                if (!PianoPanel.activeInHierarchy)
                {
                    PianoPanel.SetActive(true);
                    player.SetActive(false);
                    isPlayPiano = true;
                }
            }
        }
    }


    private void Update()
    {
        if (isPlayPiano == true)
        {
            if (Input.GetKeyDown(KeyCode.Escape))
                isPlayPiano = false;

            if (Input.GetKeyDown(KeyCode.A)) //C (도)
            {
                if (openCount >= 0)
                {
                    openCount = 0;
                }
            }

            if (Input.GetKeyDown(KeyCode.S)) //D (레)
            {
                if (openCount >= 0)
                {
                    openCount = 0;
                }
            }

            if (Input.GetKeyDown(KeyCode.D)) // E (미)
            {
                if (openCount == 1)
                    openCount += 1;
                else
                    openCount = 0;
            }

            if (Input.GetKeyDown(KeyCode.F)) // F (파)
            {
                if (openCount == 2)
                    openCount += 1;
                else if (openCount == 5)
                    openCount += 1;
                else
                    openCount = 0;
            }

            if (Input.GetKeyDown(KeyCode.J)) //G (솔)
            {
                if (openCount == 0)
                    openCount += 1;
                else if (openCount == 3)
                    openCount += 1;
                else
                    openCount = 0;
            }

            if (Input.GetKeyDown(KeyCode.K)) //A (라)
            {
                if (openCount == 4)
                {
                    openCount += 1;
                }
                else
                    openCount = 0;
            }

            if (Input.GetKeyDown(KeyCode.L)) //B (시)
            {
                if (openCount >= 0)
                {
                    openCount = 0;
                }
            }

            if (Input.GetKeyDown(KeyCode.Semicolon)||Input.GetKeyDown(KeyCode.Colon)) // C (높은 도)
            {
                if (openCount >= 0)
                {
                    openCount = 0;
                }
            }

            if(openCount >= 6)
            {
                isPlayPiano = false;
                stg01_2.OpenDoor();
            }
        }
        if( isPlayPiano == false)
        {
            PianoPanel.SetActive(false);
            player.SetActive(true);
        }
    }
}
``` 

##### ▼〔 Stage01_2.cs 〕▼

```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Stage01_1 : MonoBehaviour
{
    [SerializeField]
    GameObject door1;
    [SerializeField]
    GameObject door2;

    [SerializeField]
    Vector3 door_pos = new Vector3(0, -15, 0); 
    int puzzle_count = 4;

    bool isOpened = false;

    [SerializeField]
    int OpenCount = 0;

    private void FixedUpdate()
    {
        if (OpenCount >= puzzle_count)
        {
            if (isOpened == false)
            {
                isOpened = true;

                door1.transform.position += door_pos;
                door2.transform.position += door_pos;
            }
        }
    }

    public void AddOpenCount()
    {
        OpenCount += 1;
    }
}
```    


##### ▼〔 Stage01_2.cs 〕▼

```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Stage01_2 : MonoBehaviour
{
    [SerializeField]
    GameObject door1;
    [SerializeField]
    GameObject door2;

    [SerializeField]
    Vector3 door_pos = new Vector3(0, -15, 0);

    bool isOpened = false;

    public void OpenDoor()
    {
        if (isOpened == false)
        {
            isOpened = true;

            door1.transform.position += door_pos;
            door2.transform.position += door_pos;
        }
    }
}

```    


##### ▼〔 giftTorch.cs 〕▼

```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class giftTorch : MonoBehaviour
{
    [SerializeField]
    GameObject torchLight;

    GameObject Player;

    //PlayerStates playerStates;

    private void Awake()
    {
        Player = GameObject.FindWithTag("Player");
    }

    private void OnTriggerEnter(Collider other)
    {
        if(other.gameObject == Player) 
        {
            if (!torchLight.activeInHierarchy)
                torchLight.SetActive(true);
        }
    }
}
```    
_________________________________________________________________________________
# ★ 6st week progress
### 6주차 목표
##### 작업명 : 마무리 (1스테이지 마무리작업 및 2스테이지 퍼즐 완성 및 엔딩)

##### 해당 요구사항 :      
<pre>
  //시스템
  21. 구간에 진입시 이벤트가 발생하는 구간이 있다.
  
  //그래픽
  2. 게임의 엔딩에서는 2D 그림을 보여주며 간단한 만화형식으로 한장한장 지나가는 식으로 한다.
</pre>

##### 작업 내용 :     
  1. 횃불을 들수 있게끔 한다. (100%)
  2. 카메라를 1인칭으로 바꾼다. (100%)
  3. 피아노를 칠때, 도레미파솔라시도 각 음계의 맞는 소리가 나게 한다. (100%)
  4. 2스테이지의 퍼즐을 구현한다. 구상도는 텍스트로 구상해 놓음. (100%)
  5. 2스테이지의 두번째 방에서 버튼과 몬스터를 구현한다. (100%)
  6. 이때, 이몬스터는 플레이어를 쫒아오는 것이 아닌, 정해진길로만 다닌다. (100%)

###### 2스테이지 구상
 > 첫번째 방은 어두운 곳에서 횃불 만을 의지해 설치된 발판형 함정을 피해, 함정을 무력화 시키는 버튼을 찾는다.
 > 두번쨰 방에 들어가면 꺼져있던 몬스터들이 켜진다. 각 몬스터들은 아주 미약한 불빛이 나며, 오직 정해진 길로만 다니며, 역시 위와 같이 세개의 버튼을 찾아서 몬스터들을 무력화 시킨다.

##### 작업결과 : 
 1. 게임의 엔딩, 게임오버 신과 메인페이지로 돌아가게끔 만듦.
 2. 전반적인 스크립트 아주약간 수정 (문, 상호작용등)
 3. 버튼, 동상 등에 오디오 상호작용 추가함. 
 4. 피아노 소리 추가.
 5. 2스테이지 첫번째, 두번째방 기믹 완성.
 6. 게임 UI이미지와 엔딩,아이콘 이미지를 추가함.
 7. 게임 내 오브젝트와 부딪히면 UI생성.
 8. 몬스터 네비맵 생성
 9. 가짜 버튼과 진짜 버튼을 생성.

###### 플레이 영상     
<iframe width="560" height="315" src="https://www.youtube.com/embed/y8UvbV-vmWw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

###### 아이콘과 엔딩 이미지
  > ![12 02 ICON](https://user-images.githubusercontent.com/63893895/144347369-c1d26dad-d9bd-4f2b-a65b-ba72203a7dab.png)

  > ![12 2](https://user-images.githubusercontent.com/63893895/144347396-47e9b877-e122-4cd2-8020-dd110307ed41.png)

    
    
 
