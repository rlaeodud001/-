# zip 파일 압축 풀고 jar 파일 플러그인에 넣으면 됩니다.

name: plugint
version: ${version}
main: org.blog.plugint.TailTagPlugin
api-version: '1.21'
author: YourName
description: 꼬리잡기 게임 플러그인

commands:
  tailtag:
    description: 꼬리잡기 게임 명령어
    usage: /tailtag <start|stop>
    permission: tailtag.admin
    aliases: [tt]
  랜덤tp:
    description: 랜덤 텔레포트

permissions:
  tailtag.admin:
    description: 게임을 시작하고 종료할 수 있습니다
    default: op

위 설명이 사용법도 포함되있습니다.
문의 및 개선사항은 discord dm 부탁드립니다. (daeyoung_ceo)
