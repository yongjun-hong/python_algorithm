# RGB거리
1번 집의 색은 2번 집의 색과 같지 않아야 한다.
N번 집의 색은 N-1번 집의 색과 같지 않아야 한다.
i(2 ≤ i ≤ N-1)번 집의 색은 i-1번, i+1번 집의 색과 같지 않아야 한다.
일단 DP문제는 거의 입력 받는 배열 제외하고 문제를 풀 배열이 하나 더 필요하다. RGB거리 문제에서는 ans배열이다.
문제의 규칙을 잘 보면서 min,max함수를 잘 사용해야한다.
https://www.acmicpc.net/board/view/101509
보면 도움이 될만한 링크를 남긴다.

# 신나는 함수 실행
이 문제에서 어려운점을 하나 꼽자면 밑의 공식이다.
if ans[a][b][c]:
    return ans[a][b][c]   
문제에 있는 식들만 코드로 적으면 큰 수를 계산할때 너무 시간이 오래 걸린다.
그러므로 리스트가 존재하면 바로 리스트를 반환하는 식이 필요하다.
코딩 문제는 풀면서 실력이 증진하는 것을 느낄수 있다. 다양한 경험이 필요한것 같다.
