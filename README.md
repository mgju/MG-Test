소감문(민규) !
===================


우선 **ssh-keygen**은 어렵지 않았습니다. 다만, 파일을 생성한는 도중에 nul이라는 잘못된 MS-DOS파일이 생성<br/>
되는 바람에! 이걸 삭제하려다 파일을 강제로 삭제하는 **RM명령어** 에 대해 다시금 이해하게 되었습니다.

----------


순서
-------------

이 순서는 제가 RM명령어를 통한 오류 **해결!** 까지 도달하는 과정입니다. 

> **시작:**
>
> - 처음엔 Git Bash를 몰라서 Git이 설치되어있으니 cmd에서 작업했습니다 .
> - cmd에서 작업하다 보니 git명령어는 통하는데 ssh-keygen이 안되기에 구글링해서 Git Bash의 실행에 도달합니다.
> - GitBash를 실행하고  **ssh-keygen**과 **clone** 생성까지 마치게됩니다
> 
> **문제:**
>
> - 여기서 실수로 **clone** 생성을 한번 더 하게 됩니다.
> - 갑자기 nul이라는 파일이 생깁니다.
> - 잘못된 MSDOS파일이라고 삭제가 안됩니다.
> - 폴더지우기 등을 시도해보지만 explorer상에서는 삭제가 되지 않는다고 판단했습니다
> - cmd를 켜고 RMDIR명령어를 썻지만 또한 지워지지 않습니다
> 
> **해결:**
> 
> - Git Bash에서 rm명령어를 통해 삭제가 되었습니다.