# 프로그램 구조 설명
프로그램은 5개의 주요 함수로 구성된다.

input_matrix() : 사용자로부터 n×n 행렬 입력, (2차원 배열) 형태로 저장
inverse_by_determinant() : 행렬식(det) 계산
inverse_by_gauss_jordan() : 가우스-조던 소거법으로 역행렬 계산
visualize_matrix() : matplotlib 이용 Heatmap 표시
compare_results() : 두 결과 행렬 비교 및 출력

각 함수는 독립적으로 역할을 수행하며, main() 함수에서 순차적으로 호출되어 전체 프로그램이 실행된다.

compare_results()에서는 두 방법으로 구한 역행렬이 수치적으로 동일한지 비교하고, visualize_matrix()를 통해 Heatmap 형태로 시각적 비교 결과를 출력한다.
