---
title: WSL2 Windows 10 2004 GA
date: 2020-03-16 10:08:00
category: windows
draft: false
---

WSL2(Windows Subsystem for Linux 2)는 Windows 10 2004와 함께 릴리즈 된다고 MS가 공식으로 발표했습니다. [Windows Command Line 블로그](https://devblogs.microsoft.com/commandline/wsl2-will-be-generally-available-in-windows-10-version-2004/)

이와 함께 WSL2에 새로이 바뀐 구조에 대한 내용도 추가되었는데, 기존 발표때 Windows 10에 MS가 WSL에 최적화된 Linux Kernel을 탑재해서 배포한다고 하여서, 예전 엣지 브라우저(Spartan)과 같이 OS에 종속되어 OS의 SAC 릴리즈 사이클에 맞춰 리눅스 커널도 업데이트 되는 그런 구조였으나, 약 반년 넘게 인사이더 테스트를 하는 동안 이러한 부분에 있어서 많은 피드백이 있었고, MS가 이 피드백을 받아들여 긍정적인 변화를 만들어냈습니다.

정식 출시될 Windows 10 버전 2004(20H1)에서는, 더이상 리눅스 커널이 Windows OS 이미지에 포함되지 않고, 대신 Windows Update를 통해 배포/업데이트 되며, 이 덕분에 훨씬 더 유연하고 빠르게 리눅스 커널을 업데이트 할 수 있습니다.
