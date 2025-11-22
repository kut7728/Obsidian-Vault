# 개요
- provider를 사용하기 위해 필요한 ref
- 하지만 가끔 어디서는 Ref ref, 어디서는 WidgetRef ref 인 경우가 있다
- 둘의 차이는 뭐고, 왜 같이 사용할 수 없는 걸까

> [!info] 요약
> Ref : Provider 내부에서 다른 provider와 소통할 때 사용
> WidgetRef : Widget 내부에서 provider와 소통할 때 사용

# Ref


consumerState 에서는 WidgetRef