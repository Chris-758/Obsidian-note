
// 배열 등과 함께 사용하는 반복문
for of
for in

// 그냥 범용적으로 사용하는 반복문
for


const 배열 = ['바나나', '사과', '귤']
for (const 요소 of 배열) {
	console.log(요소)   // 바나나 사과 귤
}
for (const 인덱스 in 배열) {
	 console.log(인덱스, 배열[인덱스])  // 0 바나나 1 사과 2 귤
}


for은 let
for of, for in은 const