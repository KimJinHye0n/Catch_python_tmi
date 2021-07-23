# 실패율

신규 사용자가 급감했다. 원인은 신규 사용자와 기존 사용자 사이에 스테이지 차이가 너무 큰 것이었다.

개발자는 이를 해결하기 위해 동적으로 게임 시간을 늘려서 난이도를 조절하기로 했다. 실패율을 구하는 코드를 완성하여라

실패율은 스테이지에 도달했으나 아직 클리어하지 못한 플레이어의 수 / 스테이지에 도달한 플레이어의 수

전체 스테이지의 개수를 N, 게임을 이용하는 사용자가 현재 멈춰있는 스테이지의 번호가 담긴 배열 stages가 매개 변수로 주어질 때, 실패율이 높은 스테이지부터 내림차순으로 스테이지의 번호가 담겨있는 배열을 return 하라.