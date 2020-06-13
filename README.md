# Open Source Software Lab Final Term Project
본 프로젝트는 [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader)를 기반으로 진행되었습니다. 기존 기능에 대한 자세한 설명과 설정 방법은 원본 프로젝트를 참고해주세요.
* 발표 영상: [Click Here](https://www.youtube.com/watch?v=GIZjR5F5Rrc)


## Dropbox-Uploader의 장점
* **Shell Script 기반**: BASH 명령어를 사용하기 때문에 shell script 문법만 안다면 필요한 기능들을 자유롭게 추가할 수 있다.
* **Security**: Dropbox의 계정을 필요로 하지 않고, Dropbox API에서 보장하는 권한 확인 과정을 거치므로 안전하다.


## 추가된 기능
* **reset**:연결된 Dropbox repository를 변경하기 위해서는 **unlink** 후 다시 등록하는 과정을 거쳐야 했는데, 이를 간소화하기 위한 기능을 만들었다.
* **list_file / list_directory**: Dropbox repository 내의 모든 파일과 디렉토리를 보여주는 list 명령어를 세분화해 파일만 보여주는 **list_file**과 **list_directory**를 추가하였다.
