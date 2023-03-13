var someVariable : Int?

if someVariable == nil {
    someVariable = 90
}

//값이 비어있는지 확인
if let otherVariable = someVariable {
    //임시 변수에 someVariable 변수의 value값이 할당됩니다.
    print("값이 있다. otherVariable : \(otherVariable)")
} else {
    print("값이 없다.")
}

someVariable = nil
//someVariable에 값이 없으면 기본적으로 저녀석을 넣는다.
let myValue = someVariable ?? 10
print("myValue : \(myValue)")

var emptyVariable : Int?

myFunction(parameter: myValue)
myFunction(parameter: emptyVariable)

func myFunction(parameter: Int?) {
    print("myFunction() called")
    //값이 없으면 리턴
    guard let unWrappedParam = parameter else { return }
    print("unWrappedParam: \(unWrappedParam)")
}


//언레핑하는 법은 if let, guard let이 있다
// if let 임시변수에 현재 변수를 담아서 언래핑한다
// guard let도 똑같은 원리이다
