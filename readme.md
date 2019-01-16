
# 1. 아나콘다 

### Anaconda Prompt

아나콘다 버전 확인
```shell
> conda --version
```
아나콘다 업데이트
```shell
> conda update conda
```
가상환경 정보 확인
```shell
> conda info --envs
```

가상환경 설치
```shell
> conda create --name test1 python=3.4  # 최초설치
> conda create --name test1 python=3.4 simplejson pillow # 패키지도 같이 설치
```

가상환경 삭제
```shell
> conda remove --name test1 --all
> conda remove --name test1 -a
```

가상환경 활성화
```shell
> activate test1
```

가상환경 비활성화
```shell
> deactivate test1
```

아나콘다 패키지 설치정보
```shell
> conda list
```

해당 가상환경에 simplejson 패키지 설치
```shell
> pip install simplejson
```
```shell
> pip uninstall simplejson
> pip install --ignore-installed simplejson
```
아나콘다 사용로그나 캐시 삭제
```shell
> conda clean --all
```

