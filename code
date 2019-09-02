function rot13(str) { // LBH QVQ VG!
  var arr=str.split("");
  var array=[];  
  for (let i=0; i<arr.length; i++){
      var x=str.charCodeAt(i);
      if (x<65 || x>90){
        array[i]=String.fromCharCode(x);
      }else if (x<78){
          array[i]=String.fromCharCode(x+13);
      }else{
          array[i]=String.fromCharCode(x-13);
      }
  }
  console.log(array)
  return array.join("");
}
