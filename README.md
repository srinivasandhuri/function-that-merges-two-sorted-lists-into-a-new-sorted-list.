# function-that-merges-two-sorted-lists-into-a-new-sorted-list.




var arr1=[1,4,6];
var arr2=[2,3,5];

function newArray(arr1,arr2) {
var arr3=[];
arr3=arr1.concat(arr2).sort();

return arr3;

          }
console.log(newArray(arr1,arr2));

output:[1,2,3,4,5,6]

