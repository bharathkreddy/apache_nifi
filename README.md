# Apache NIFI learning

1. Apache nifi docker doesnt run properly on M1 Macbook so use the shell script and follow below commands.
    - sh build-nifi.sh 1.16.3
    - docker run --platform=linux/arm64 --name nifi -p 8443:8443 -e SINGLE_USER_CREDENTIALS_USERNAME=admin -e SINGLE_USER_CREDENTIALS_PASSWORD=ctsBtRBKHRAx69EqUghvvgEvjnaLjFEB -d apache/nifi:1.16.3-arm64

2. 