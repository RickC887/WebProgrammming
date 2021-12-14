#task1.
function readNumber() {
  const a = prompt('Enter num:')
  if(a === '' || a === null) return null
  else if(isNaN(+a)) return readNumber()
  else return a
}
console.log(readNumber())


#task2.
function random(min, max) {
  return Math.random() * (max - min) + min
}
for(let i = 0; i < 30; i++) console.log(random(1, 5))


#task3.
const a = +prompt('Enter num1:'),
      b = +prompt('Enter num2:')
alert(a + b)


#task4.
let array=[ 
	" Спочатку JavaScript був створений, щоб зробити веб-сторінки живими ", 
	" Різні двигуни мають різні «кодові імена».",
	" Коли JavaScript створювався, він мав інше ім'я – «LiveScript» ",
	" Повна інтеграція з HTML/CSS "
]
array.forEach(item => item.indexOf('JavaScript') !== -1 ? console.log(item) : undefined)


#task5.
function formatStr(str) {
  return str = str[0].toUpperCase() + str.substr(1).toLowerCase()
}
formatStr('bOoK')
