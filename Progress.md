<pre>※ 주의 사항 : 새로 추가된 요소에는 【♨】가 붙어있습니다. </pre>
# ProJect Name : 《Escape to Memory》  :  Progress
##### [index로 돌아가기](/index.md)

## ▶목차
#### 0. [요구 사항](#-requirements)
#### 1. [1주차](#-1st-week-progress)
 - [1주차 목표](#1주차-목표)
 - [1주차 작업결과](#1주차-작업-결과)
#### 2. [2주차](#-2st-week-progress)
#### 3. [3주차]

_________________________________________________________________________________
    
# ▷ Requirements
#### 게임 요구사항
    1. 시작화면,게임화면,엔딩화면으로 3개의 화면이 있다. 
    2. 엔딩 수는 10개 이므로 총 12개의 Scean으로 구성된다. (시작화면,게임화면,엔딩화면,Bad End 4개, Nomal End 2개, Another End 5개)
    3. 시작화면에는 Start,Ending, Exit 총 3개의 버튼이 있다.
    4. Ending을 누르면 현재까지 본 엔딩항목을 볼수 있다.
    5. Ending 화면에서 볼수있는 엔딩 항목에는 해금된 엔딩은 엔딩제목이 흰색 글씨로표시 되고, 미해금된 엔딩은 미해금 엔딩이라고나온다.
    6. Ending 화면에서는 엔딩 항목에 있는 해금된 엔딩을 누르면 엔딩장면을 다시 볼 수 있다.
    7. Ending 화면에서 우측상단의 돌아가기버튼을 누르면 시작화면으로 돌아온다.
    8. Exit를 누르면 게임 프로그램이 종료된다.
    9. 시작 화면에서 Start버튼을 클릭하면 게임화면으로 변경된다.
    10. 게임화면에는 기본적으로 아무것도 나오지 않으나, 특정 오브젝트와 일정한 거리 다가갈시 상호작용메세지가 중앙에 작게 나온다. 
    11. 스테이지는 있으나, 특별한 구별은 없고 모든 스테이지 맵은 이어져있고, 특정 조건을 맞출시 막혀있는 문이 열리는 구조이다.
    12. 스테이지에 진입하면 문이 닫힌다.
    13. 조작은 키보드의 WASD로 W는 전진, S는 후진하며, A는 좌, D는 우측 방향으로 이동이가능하다.
    14. 마우스로 플레이어가 보고 있는 시점이동이 가능하며, 마우스 휠을 드래그하면 확대, 축소 또한 가능하다.
    15. Shift는 달리기이고 속도가 3증가하고, Space Bar는 점프이며, F키는 상호작용키 이다.
    16. NPC오브젝트와 상호작용시, 게임화면 하단에 대화창이 출력된다. 이때, F키를 누르면 대화창을 넘길 수 있다.
    17. 단서는 특정 이벤트 달성시, 자동으로 해금(습득) 한다.
    18. 단서를 모두 모으면 히든 엔딩을 볼수 있는 길로 가는 숨겨진 통로로 가는 길이 열린다. 하지만 통과할수 있는 벽으로 그냥 지나칠 수도 있게한다.
    19. 2스테이지에서 일정 구간 동안은 시아를 어둡게 제한한다.
    20. 1스테이지에서 주는 횃불이 어두운 구간에서 일정 범위만 길을 빛추게 한다.
    21. 구간에 진입시 이벤트가 발생하는 구간이 있다.
    22. 엔딩장면까지 다 보면 시작화면으로 돌아오고, 엔딩화면에 있는 엔딩항목에 엔딩장면이 해금된다.
    23. 카메라는 플레이어의 3인칭으로 하며, 마우스로 카메라 회전이 가능하다.
    24. 카메라가 회전했을 때, W를 눌러 앞으로 가면 카메라가 보는 방향으로 케릭터가 회전하며, 케릭터가 이동하도록한다.
    
#### 그래픽 요구사항
    1. 횃불은 플레쉬 장난감이라는 설정이므로 불부분이 무드등 같이 빛나는 효과를 주도록 한다.
    2. 게임의 엔딩에서는 2D 그림을 보여주며 간단한 만화형식으로 한장한장 지나가는 식으로 한다. 
    
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
<pre><code>
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
</code></pre>  

#### ○ 로딩♨    
 ![Loading_Scene](https://user-images.githubusercontent.com/63893895/139085141-440aaac8-55d7-4cc6-b25e-b5c03ec12a7c.gif)

##### ▼〔 SceneLoader.cs 〕▼
<pre><code>
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

</code></pre>                           

#### ○ 카메라 움직임 관련    
  ![카메라 ](https://user-images.githubusercontent.com/63893895/139088751-6390b093-4194-416c-bfd5-43b8eb064ca2.gif)

##### ▼〔 CameraController.cs 〕▼
<pre><code>
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
</code></pre>             
    
#### ○ 이동관련    
![이동1](https://user-images.githubusercontent.com/63893895/139097241-4b538dd8-5eb6-4fa5-8ec1-8eb87ae1eff1.gif)
![이동2](https://user-images.githubusercontent.com/63893895/139097235-10c05584-533f-4030-925a-6854be5f8789.gif)

##### ▼〔 Movement3D.cs 〕▼    
<pre><code> 
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

</code></pre>

##### ▼〔 PlayerCtrler.cs 〕▼
<pre>
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
</pre>  


 #### ※ 추가 및 변경 된 사항
- 요구사항에 따로 없던 Loading Scene을 추가 하였습니다. Start버튼을 누르면 Loading Scene으로 이동하며, 다음 맵을 로드 합니다.    
  로딩이후 아무 키를 누르면, 게임 화면(Start Scene)으로 이동합니다.
- 이동과 관련이 있는 요구사항 14번 항목{14.마우스로 플레이어가 보고 있는 시점이동이 가능하며,    
  마우스 휠을 드래그하면 확대, 축소 또한 가능하다.}을 이번주차에 구현 하였습니다.
  
  _________________________________________________________________________________
    
# ★ 2st week progress
## 2주차 목표
  -추후 추가 예정
