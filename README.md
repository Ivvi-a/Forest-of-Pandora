# Forest of Pandora
![logo](assets/Logo.png)

## Index
  - [Introduction](#introduction) 
  - [Technical Stacks](#technical-stacks)
  - [Features](#features)
  - [Documentation](#documentation)
  - [Team](#team)
<br>

## Introduction
### Overview
<p>Pandora's Forest is an anonymous post-sharing service that anyone can use without hesitation.</p>
<p>Our team believes that many users want to share their trivial and secret stories and seek empathy. However, existing social media platforms require users to use fixed nicknames or share their IDs with people around them, making it difficult to guarantee complete anonymity. Moreover, traditional social media often favors users with a larger number of followers, leading to better communication and significant influence on the platform.</p>
<p>Therefore, we aim to create a post-sharing platform where users can share their stories and seek empathy without any burden by assigning random nicknames to each post and eliminating the need for followers or following.</p>

<!--
판도라의 숲은 누구나 부담없이 사용할 수 있는 익명 글 공유 서비스입니다. <br>
저희 팀은 자신의 사소하고 비밀스러운 이야기를 공유하고 공감받고 싶어하는 사용자가 많지만  기존의 SNS는 고정된 닉네임을 사용하거나 주변 사람들과 ID를 공유하며 사용하기 때문에 완벽한 익명성을 보장하기 힘들다고 생각했습니다. 또한 기존의 SNS는 자신의 팔로우 하는 사람이 많을수록 소통이 더 잘 이루어지고, 해당 플랫폼에 영향을 많이 끼치고 있습니다. <br>
따라서 저희는 자신의 이야기를 공유하고 공감받고 싶어하는 사용자가 부담없이 사용할 수 있도록 글 마다 랜덤닉네임을 부여하고 팔로우/팔로워가 없는 글 공유 플렛폼을 만들고자 합니다.
-->


### Duration and Team
<p>Duration: 2024. 01. 08 - 2024. 04. 16 (6 weeks)</p>
<p>Team: 6 members</p>

<br>

## Technical Stacks
|  |  |
|----|---|
| **FE** | <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"> <img src="https://img.shields.io/badge/redux--toolkit-593D88?style=flat&logo=redux&logoColor=white"/> |
| **BE** | <img src="https://img.shields.io/badge/springboot-6DB33F?style=flat&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=flat&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/amazons3-569A31?style=flat&logo=amazons3&logoColor=white"> |
| **Infra** | <img src="https://img.shields.io/badge/amazonec2-FF9900?style=flat&logo=amazonec2&logoColor=white"> <img src="https://img.shields.io/badge/docker-2496ED?style=flat&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/nginx-009639?style=flat&logo=nginx&logoColor=white"> <img src="https://img.shields.io/badge/jenkins-D24939?style=flat&logo=jenkins&logoColor=white"> |
| **IDE** | ![](https://img.shields.io/badge/VSCode-3178C6?style=flat&logo=v&logoColor=white) ![](https://img.shields.io/badge/intelliJ_IDEA-F23920?style=flat&logo=intellij&logoColor=white) |
| **Tools** | <img src="https://img.shields.io/badge/gitlab-FC6D26?style=flat&logo=gitlab&logoColor=white"> <img src="https://img.shields.io/badge/jira-0052CC?style=flat&logo=jira&logoColor=white"> <img src="https://img.shields.io/badge/notion-000000?style=flat&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/swagger-85EA2D?style=flat&logo=swagger&logoColor=white"> <img src="https://img.shields.io/badge/figma-F24E1E?style=flat&logo=figma&logoColor=white"> |

<br>

[back to top](#index)
<br>

## Features

<details>
  <summary><h3>Sign Up and Login</h3></summary> 
  <img src="assets/login.GIF"  width="300"/> <br>
  - You can view posts without creating an account, but need to log in for interactive features. <br>
  - By logging in with the Kakao Login API, you automatically create an account on your first login.
    
</details>

<details>
  <summary><h3>Viewing Posts, Liking, and Saving</h3></summary> 
  <img src="assets/save.GIF"  width="300"/> <br>
  - Posts are displayed in an infinite scroll format, showing content, images, user info, and interaction stats, with a report option for inappropriate content. <br>
  - You can increase the like count on posts you enjoy by clicking the like button. <br>
  - You can bookmark posts you like for easy access later in the My Page section.
    
</details>

<details>
  <summary><h3>Registering, Editing, Deleting, and Temporarily Saving Posts</h3></summary> 
  <img src="assets/writing.GIF"  width="300"/> <br>
  - Register post content along with up to 5 images, with a text limit of 500 characters. <br>
  - Edit or delete your own posts as needed. <br>
  - Temporarily save a post you’re writing, including images, and retrieve it later.
    
</details>

<details>
  <summary><h3>Comments and Replies</h3></summary> 
  <img src="assets/reply.GIF"  width="300"/>  <br>
  - Each post shows random nicknames and profile pictures for comments, and authors get notified when comments are made. <br>
  - Inappropriate comments can be reported, and users can edit or delete their own comments. <br>
  - You can reply to comments, and original authors are notified, with the ability to report, edit, or delete their replies.
    
</details>

<details>
  <summary><h3>My Page</h3></summary> 
  <img src="assets/myWriting.GIF"  width="300"/> <br>
  - You can view your posts sorted by writing date, along with content, images, posting dates, like counts, and comment counts. <br>
  - You can access a list of your saved posts sorted by date, including content, images, posting dates, and author nicknames.
    
</details>

<br>

[back to top](#index)
<br>

## Documentation

### Porting Guide (exec)
👉 [Porting Guide](https://github.com/Ivvi-a/Forest-of-Pandora/tree/main/exec) <br>

### Wireframe
👉 [Figma](https://www.figma.com/design/4yc4GtoT9B4qryWfcK7Scu/%ED%8C%90%EB%8F%84%EB%9D%BC%EC%9D%98-%EC%88%B2?node-id=0-1)

### API Spec
👉 [Notion](https://pumped-square-544.notion.site/API-deac3f36a1ad4c68ac427c155cb63c1e)

### Fuctional Spec
<img src="assets/FunctionalSpecification.jpg" width="700"/>

### ERD
![ERD](assets/ERD.PNG)

### System Architecture
<img width="921" alt="시스템 아키텍처" src="https://github.com/NavyHubb/StudyInitiator/assets/101810007/35cfecf5-eb26-48fd-a921-85b14c16334a">

![시스템아키텍처](assets/SystemArchitecture.png)


[back to top](#index)
<br>

## Team
|  김성재  |  안성재  |  유호정  |  윤정인  |  이서윤  |  조연주  |
| --- | --- | --- | --- | --- | --- |
| <img src="assets/kim.PNG" width="200"/> | <img src="assets/an.PNG" width="200"/> | <img src="assets/yoo.PNG" width="200"/></div> | <img src="assets/yoon.PNG" width="200"/> | <img src="assets/lee.PNG" width="200"/> | <img src="assets/jo.PNG" width="200"/> |
| Backend / Infra | Backend | Frontend | Backend | Frontend | Frontend |
