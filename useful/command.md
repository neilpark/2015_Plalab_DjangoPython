CentOS와 Ubuntu에서 apache나 mysql을 실행시키는 명령어가 달라 작성하게 되었음.
# Ubuntu
#### 배포판 확인 방법
> /etc/os-release 에 기록 되어 있음.

```
server:/etc$ cat os-release
NAME="Ubuntu"
VERSION="14.04.2 LTS, Trusty Tahr"
ID=ubuntu
ID_LIKE=debian
PRETTY_NAME="Ubuntu 14.04.2 LTS"
VERSION_ID="14.04"
HOME_URL="http://www.ubuntu.com/"
SUPPORT_URL="http://help.ubuntu.com/"
BUG_REPORT_URL="http://bugs.launchpad.net/ubuntu/"
```
#### Apache2
* 설정파일 Path : /etc/apache2
* 실행 : # service apache2 start
* 종료 : # service apache2 stop
* 설정 적용 : # service apache2 reload

```
server:/etc# service apache2 start
 * Starting web server apache2
 *
server:/etc# 
```

#### MariaDB & MySQL
> 동일한 명령어를 사용.

* 실행 : # service mysql start
* 종료 : # service mysql stop
* 로그인 : # mysql -u 아이디 -p
