---
title   : '팀에 기여할 수 없는 순간, 그래도 할 수 있는 것' 
slug  :  '/when-you-cant-contribute'
layout  : wiki 
excerpt : '기여하기 어렵다고요? 할일이 없다고요?'
date    : 2020-03-20 10:09:53 +0900
updated : 2020-04-07 15:05:20 +0900
tags    : 
parent  : 
---

# 이게 왜 문제에요? 
  자기 효능감과 관련이 있습니다. 냉정하게 생각해보면 조직은 당신을 뽑았고, 기여를 할 수 있는 인재라고 판단해서 돈을 줍니다. 당신이 기여를 못하는 상황에 놓인 것은 당신의 잘못만은 아닙니다. 환경이 마련되면 누구보다 기여를 많이 하지만 가이드가 아예 없는 경우 길을 잃는 경우도 있을 수 있고요. 몇번의 기여 시도 후에도 피드백이 없으면 또한 기분이 안좋아집니다. 결국, 'Why they hire me?' 로 돌아가게 됩니다. 
  
  즉, 대단히 똑똑하고 빠르게 움직이는 사람들이 있다고해서 개인에게 좋은 조직인 것은 아닙니다. 적절한 온보딩과 피드백이 갖춰진 조직에서는 더욱 효과적으로 일할 수 있습니다. 조직의 환경은 어떻고, 이런 기능을 하며, 당신은 이런 역할을 하게 될 거다. 라는 얘기를 듣고 시작하는 것. 그리고 그냥 그 팀에 던져져 '질문할 수 있는 타이밍만 호시탐탐 노려야하는 사람이 되는 것. 
  
  그리고 2주에 한번씩 매니저와 면담해서 방향을 정할 수 있는 기회가 마련되어있는 팀과, 겨우 평가 기간에만 면담하는 팀은 확실히 다르니까요.
  
  저는 특히나 자기 효능감이 요동치는 사람이어서, 팀에서는 '자기 Pull Request가 안올라와 있으면 불안해하는 신입' 정도로 통하고 있습니다. 앗, 이런 평가는 지난  두번의 인턴 평가와는 조금 다릅니다. 
  
  인턴시절에는 명확한 프로젝트가 있고요, 목적이 있습니다. 상대적으로 짧은 기간안에 프로젝트를 완성시키고, 그것을 발표합니다. 기능이 잘 동작하고 읽기 좋은 코드라면 대체로 좋은 평가를 받죠. 인턴 종료로 마무리가 지어지고 성장 가능성이 괜찮은 새싹이라는 평가를 받습니다. 
  
  업무에 들어오니 다릅니다. 평가가 있지만, 조금 다른 기분입니다. 신입에게 맡기기에는 프로젝트는 기한이 있고요, 신입의  코딩 실력은 대개 그리 뛰어나지 않습니다.  공통 구조와 로직을 최대한 제공해서 기본적인 코드의 퀄리티를 보장해주지만, 창의적인 방법으로 스파게티를 짜옵니다. 
  
  이걸 지적하고 고치도록 기다려주는데는 시간이 듭니다. 선배 개발자들은 조금 쉬운 컴포넌트만 맡깁니다. CRUD 나 다른 코드를 참고하여 금방 짤 수 있는 것들이 대상이 됩니다. 쉬운 일은 금방 없어지고, 쉬운 걸 조금씩만 처리하는 신입(=저) 는 나의 자리가 없다는 생각에 가벼운 우울에 빠집니다.
  
  장황하게 적었지만 어쨌든 이런 경로로 저는 자기효능감 저하와 우울의 하강나선에 들어서곤 합니다. 그래도 계속 걸어야합니다.  이럴 때 도움이 된 일들을 몇가지 소개합니다.
  
  
## 회의록 작성하기 

잘 작성된 회의록은 모두에게 도움이 됩니다. 강의 듣던 시절 속사포로 교수님 강의를 정리하던 실력을 발휘하는 건 어떨까요? 부족한 점이 있어도 좋습니다. 부족한 점은 팀원들에게 고쳐달라고 할 수 있도록 github 이슈에 정리합니다. 저의 경우 
- 일시 / 참석자 
- 목적 
- 내용
- TODO
의 포맷으로 정리하고 있습니다.

참석한 회의만 적어도 도움이 됩니다. 구조에 대한 회의였다면 이해한 바를 도식화해서 그림으로 옮겨봅시다. 

## checkstyle에 맞춰서 코드 수정하기 
프로젝트에 checkstyle이 있어서 걱정 없다구요? checkstyle을 한번만 전체 프로젝트에 돌려보세요. 엄청나게 쏟아져나오는 checkstyle 오류를 확인할 수 있습니다. 마이너한 것부터 고쳐서 PR을 올려보세요.

- no new line in the file 
- indentation 
- no new line between method definition 

제일 많이 나타나는 checkstyle 은 이런 것들이었습니다. 

팀에 checkstyle이 없다면 checkstyle 을 적용하고 가이드를 주는것도 좋겠죠! 

## 신입 온보딩 문서 손보기 
아무리 큰 회사이고 공통의 온보딩이 있다고해도, 팀만의 특색이 있기 마련입니다. 사용되는 기술 스택, 플랫폼, 서버 자원, 위키페이지 등을 보기좋게 정리합니다.
이 문서는 비단 신입뿐 아니라 이 팀에 새로오는 모든 사람들에게 유용합니다. 이 문서는 팀바팀이기 때문입니다. 

## 설거지하기 
열심히 얘기하다가 무슨 설거지냐 할 수 있겠지만 꽤 도움이 됩니다. 일이 없을 때보다, 스스로 해결하기 조금 어려운 일을 맡았고 벽에 부딪혔을 때 유용합니다. 

설거지는, 
- 해결 가능한
- 작은 문제 
- 그리고 해결해야만 하는 문제 
- 미래의 나에게 도움이 되며 나를 위로하는 것 
- 밥만 먹으면 생기므로 자주 사용 가능 
  
이라는 속성을 띄고 있는 문제이기때문입니다. 실제로 저는 문제를 해결하지 못해서 화가 날 때 폭풍 설거지를 하며 해법을 정리해봅니다. 안되면, 생각한 것들을 정리해서 사수님한테 어떻게 물어볼지를 구상합니다. 코드는 팀의 것이니까 언제든 물어봅니다. 
