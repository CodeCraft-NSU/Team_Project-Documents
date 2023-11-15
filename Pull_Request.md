Pull Request (PR) 작성 방법
======


- 작업하고자 하는 Repository에 접속해 우측 상단에 있는 Fork 버튼을 클릭한다.
  - PR을 작성하기 전에 해당하는 [Issue 작성](Issues.md)이 반드시 선행되어야 한다.
  - 최초 1회만 Fork 작업을 진행하면 되고, 한 번 Fork 작업을 진행한 Repository는 다시 진행할 필요가 없다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/f4715ca3-7651-4b20-b418-415c3254a608)

- 다른 것은 건들일 필요 없이 Create Fork 버튼을 클릭한다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/76cb7fdd-7fda-4619-8a69-727f1fc0d23e)

- 버튼을 눌렀다면 자동으로 자신의 Repository에 Fork된 페이지로 이동될 것이다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/5c7e3e32-e482-4e95-b78f-f08cdd27bcfc)

- 이제 자신이 수정하고자 하는 파일에 들어가 수정 작업을 진행한다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/ce77acb4-0e0f-45d3-9fe4-c51f70b52f53)

- 수정 작업을 마쳤다면 우측 상단에 있는 Commit changes... 버튼을 클릭한다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/51be9630-4205-418e-8b63-8e65305cdfb0)

- Commit message는 [Commit Rule](https://github.com/kimch0612/Team_Project-Documents/blob/master/Convention.md#commit-rule)에 따라 작성하고, Extended description은 수정사항에 대해 간략한 설명을 작성한다.
- 하단에 있는 branch 파트는 'Commit directly to the master branch'에서 'Create a new branch for this commit and start a pull request'로 변경하고, Branch name을 [Branch Rule](https://github.com/kimch0612/Team_Project-Documents/blob/master/Convention.md#branch-rule)에 맞게 작성해 프로젝트의 분기점을 만들어준다.
  - 이때, 자신이 PR 작업을 진행하면서 분기점을 한 번이라도 만들었다면 (헌재 진행중인 PR에서 위의 작업을 한 번이라도 진행한적이 있다면) 이 옵션을 선택하지 말고 Commit directly to the [branch name] branch 옵션으로 둔다.
  - 이미 Branch를 새로 만들었음에도 수정할 때마다 New Branch를 하게 된다면 불필요한 branch가 생성되며, PR에 자신이 수정한 사항이 전달되지 않는다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/82aee5cd-3a32-46df-973c-f2413fadd5fa)

- Propose changes 버튼을 클릭하면 자동으로 Pull Requests 창으로 넘어올텐데, title과 description을 [작업 협약](https://github.com/kimch0612/Team_Project-Documents/blob/master/Convention.md)에 맞춰서 작성한다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/01718f34-9eb8-4eb0-bc5a-e1e85f30244b)
- 이때, 본문과 댓글에서 Markdown 문법을 통해 글을 작성할 수 있는데, 자세한 작성 방법(문법)은 [Markdown Syntax 문서](Markdown_Syntax.md)를 참고할 것.

![image](https://github.com/kimch0612/OOP2_Project/assets/10193967/f49ec036-e7df-4cfb-ba97-1e66b92fb4c3)
![image](https://github.com/kimch0612/OOP2_Project/assets/10193967/17cb42c7-9949-468b-922d-879b1fc9015e)

- Reviewers에 Project Leader를 선택한다.
  - 만약 자신이 직접 설정할 수 없는 상태라면 Reviewers~Labels 까지의 작업은 스킵해도 된다. 대신 PR 문서를 전부 작성했다면 Project Leader에게 연락을 취할 것.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/54ddc49c-7a55-40e4-bb18-208c7c8e11fc)

- Assignees에는 자신과 Project Leader를 선택한다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/343efb4b-1b5a-4852-818c-f402228d1ae6)

- Labels에는 이 PR이 해당하는 항목을 선택한다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/d3351cf6-070e-4abc-b485-faab01274c13)

- Create Pull Request 버튼을 클릭하면 아래와 같은 페이지가 열릴 것이다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/dc37e60f-652b-484f-b8ed-78191766b9b8)

- PR이 열린 것을 확인했다면 자신이 작성한 Issue로 돌아가서 Development를 수정한다.
  - 톱니바퀴를 누르면 첫번째 사진과 같이 나올텐데, 자신이 작업한 프로젝트를 선택하면 된다.
  - 다음으로는 자신이 작업한 PR의 이름을 선택하고 Apply를 클릭한다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/aaa22acd-59d7-45bf-a008-fd64282602b9)

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/6eccda15-cfe7-4d41-81cd-56b1abb7f19c)

- 완료했다면 자신이 작성한 Issue와 PR이 서로 연동이 될 것이다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/992c07df-9d4c-41c4-aad9-d29a4bc74571)

- 이후 Project Leader가 PR을 확인하고 master branch에 merge했다면 자동으로 Issue와 PR은 닫힐 것이다.
  - 만약 Project Leader가 특정 부분을 수정해달라고 Change Request를 보냈다면, 다시 자신의 Repository로 돌아가 master branch가 아닌 새로 만든 branch를 선택하고, 수정 요청을 받은 파일로 들어가 작업을 진행하면 된다.
  - 수정을 진행하고  Commit directly to the [branch name] branch 옵션으로 Propose changes 버튼을 클릭하면 수정 사항이 저장될텐데, 이는 자동으로 PR로도 전송되니 Propose changes를 했다면 다시 PR 페이지로 돌아가 수정 사항이 연동됐는지 정도만 확인해준다.

![Screenshot_20231115_144721_Samsung Notes](https://github.com/yymin1022/Wa_API/assets/10193967/61dd3210-4e0f-4555-b91b-40e6d4d9b3ed)
- Project Leader가 PR에 관해서 완료됐다고 알려주면 자신의 Repository에 가서 작업한 Branch를 제거해준다.
  - branch 버튼을 클릭하고 View all branches를 클릭한다.
  - master (혹은 main) Branch를 제외한 모든 branch를 휴지통 모양의 버튼을 클릭해서 삭제해준다.

![Screenshot_20231115_142037_Samsung Internet](https://github.com/kimch0612/OOP2_Project/assets/10193967/f202c48a-db30-451b-a34d-8aaebc622c33)
![Screenshot_20231115_142121_Samsung Internet](https://github.com/kimch0612/OOP2_Project/assets/10193967/11a0ca26-7a65-4206-a9a6-109309c92b5d)
- 이후에 다시 수정이나 추가 등 작업을 진행하려면 또 Fork를 할 것이 아니라, 내 계정에 있는 Fork된 Repository에 들어가 Sync fork -> Update branch를 실행해 Repository를 최신화한 뒤 작업을 진행한다.
  - 만약 Up-To-Date와 같은 메세지가 떠있다면 내가 마지막으로 수정한 이후로 Team Project가 수정된 적이 없다는 뜻으로, 이와 같은 메세지를 확인했다면 이 항목은 무시하고 수정 작업부터 다시 시작하면 된다.

![image](https://github.com/kimch0612/Team_Project-Documents/assets/10193967/9881ed8b-30d2-4870-a42e-437d7ae6b5ec)

[PR 예시](https://github.com/kimch0612/OOP2_Project/pull/7)

끝.
