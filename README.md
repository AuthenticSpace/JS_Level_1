# JS_Level_1

HomeWork_3

///////////////////////
Task_1

let n = 1;
let nArr = [];

while (n <= 100) {
    if (n == 1) {
        nArr.push(1)
    } else {
        let result = 2;
        let i = 2;
        while (n % i !== 0 ){
            i += 1;
            result +=1;
            } 
        if (result == n) {
            nArr.push(result);
        }
    }
    n += 1;
}

console.log(nArr);

///////////////////////
Task_2-3

var goods = [
    {
        title: "Носки",
        price: 100,
        count: 10,
    },
    {
        title: "Футболки",
        price: 250,
        count: 5,
    },
    {
        title: "Штаны",
        price: 600,
        count: 3,
    }
];

function countBasketPrice(items){
    var s=0;
    for (var item of items){
        s +=  item.price*item.count; //-Умножение цены на кол-во.
    }
    return s;
}
alert(countBasketPrice(goods));

///////////////////////
Task_4

var i;
        for ( i = 0; i <= 9; i++){
            console.log(i);
        }
        
///////////////////////
Task_5


        var arr = [];
        var end = 0;
        while (end < 20){
            end++;
            arr.push('x');
            console.log(arr);
        }
        
///////////////////////
