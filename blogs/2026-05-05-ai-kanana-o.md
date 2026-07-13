---
title: "음성 AI 모델을 프로덕션에 올리기까지: Kanana-O 서빙 최적화 여정"
url: "https://tech.kakao.com/posts/821"
date: "2026-05-05"
author: "hulk.5 / steve.ai"
feed_url: "https://tech.kakao.com/feed/"
---
TL;DR kanana-o는 텍스트·이미지·오디오를 종합적으로 이해하고 자연스러운 텍스트와 음성으로 응답하는 멀티모달 모델입니다(자세히 알아보기). 모델을 학습하는 것과 사용자에게 서비스하는 것은 전혀 다른 문제입니다. 이 글에서는 Kanana-O를 실시간 음성 대화 서비스로 제공하기 위해 마주한 엔지니어링 문제들과, 이를 해결하며 만든 서빙 서버 Kanana-Omni Server의 핵심 최적화 기법들을 공유합니다.
