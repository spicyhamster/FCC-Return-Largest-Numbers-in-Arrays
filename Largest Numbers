//Return an array consisting of the largest number from each provided sub-array. For simplicity, the provided array will contain exactly 4 sub-arrays.

function largestOfFour(arr) {
  var newArr = [];
  for(var i = 0; i< arr.length; i++) {
    var biggest = arr[i][0];
    for(var j = 1; j<=arr.length; j++){
      if (arr[i][j] > biggest){
        biggest = arr[i][j];
      }
      newArr[i] = biggest;
    }
  }
  return newArr;
}
