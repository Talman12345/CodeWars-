# CodeWars-

1   const areaOrPerimeter = function(l , w) {
  return l == w ? l*w: (l*2) + (w*2)
};

2  function pipeFix(numbers){
  let arrNum = []
    for(let i = numbers[0];i<=numbers[numbers.length-1];i++){
        arrNum.push(i)
    }
  return arrNum
}


3  function peopleWithAgeDrink(old) {
  if(old<14){
    return "drink toddy" 
  } else if( old>13 && old<18){
      return "drink coke";
    } else if( old>17 && old<21){
      return "drink beer"
    }else{
      return  "drink whisky"
    }
     
  };


  4  function maps(x){
    let arr = []
    for(let i = 0; i<x.length; i++){
      arr.push(x[i]*2)
    }
    return arr
  }
