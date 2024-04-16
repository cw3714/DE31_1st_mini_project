# Electronic Vehicle Charge Station Data Analysis

## Summary
이 토이프로젝트는 [Playdata](https://playdata.io)에서 진행하는 데이터 엔지니어링 프로젝트 31기 부트 캠프에서 진행하는 프로젝트입니다.

프로젝트에 참여하는 인원들은 다음과 같습니다.
- [최성현](https://github.com/S0rrow)
- [유정연](https://github.com/yjyj989812)
- [김승주](https://github.com/tmdwnabc)
- [이충원](https://github.com/cw3714)
- [신소영](https://github.com/soyoungshin1)

해당 프로젝트의 목적은 대한민국에서 전기차를 운용하기 위한 충전소의 수량이 충분히 보급되었는가를 확인하는 것입니다.


## Development Condition
해당 프로젝트의 개발 환경은 다음과 같습니다.

1. Python 3.10: 데이터를 시각화하고 실행 코드를 작성하기 위해 Python3를 사용했습니다.   
    - Python Modules: Python의 다양한 외부 패키지의 활용과 개발 환경 보존을 위해 pip와 venv를 사용했습니다.
    - 해당 프로젝트에 사용된 PIP 패키지는 다음과 같습니다.
        - ~
2. Github: 프로젝트의 개발 과정과 결과물을 보존하기 위해 Git과 Github를 사용했습니다.
3. MySQL: 프로젝트의 데이터를 저장하고 다시 끌어오기 위해 MySQL을 사용했습니다.


### For Reproduction
본 프로젝트의 개발 환경은 Ubuntu 22.04.4 LTS를 기반으로 구성되었습니다.

모든 명령어는 본 레포지토리의 복제된 로컬 레포지토리에서 실행된다는 가정하에 설명되었습니다.

1. Install Git
```bash
sudo apt install git
```
Git과 그 기반환경이 설치되어 있지 않다면 미리 설치해야 할 필요가 있습니다.

2. Install Python3
```bash
sudo apt install python310
```
프로젝트에서 활용되는 pip 패키지들의 버전 호환과 버그 유발 빈도를 고려해 Python 3.10을 기반으로 개발했습니다.

3. Install Virtual Environment
```bash
python -m venv .venv
```
Python의 설치시에 기본적으로 함께 설치되는 가상환경을 '.venv'라는 이름으로 구성합니다.

```bash
. ./.venv/bin/activate
```
현재 디렉토리에 대해서 가상환경을 구동합니다.

4. Install pip packages
```bash
python -m pip install -r requirements.txt
```
requirements.txt를 통해 개발환경에 필요한 pip 패키지들의 목록을 그대로 재구성할 수 있습니다.

[4](#for-reproduction-4)번까지의 환경 구성을 완료했다면 프로젝트를 재구현하기 위한 환경 구성이 완료된 것입니다.


