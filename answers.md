Hi, My self muhammed sinan and i from wayanad and i have one year experiance in laravel and angular at vandalay buisnes solutions kochi.
my OS is both linux and windows,my ide is visual studio code

Question No 2:
<?php
 function fu($number) {
     $arr = array();
     $number = (string)$number;
     for($i=0;$i< strlen($number);$i++){
         array_push($arr,$number[$i]);
     }
     return $arr;
 }
 $answer = fu(111);
 print_r($answer);
?>

Question No 3:
<?php
 function fu($string) {
     $arr = explode(' ',$string);
     $newarr = array();
     foreach($arr as $val){
         $first = substr($val,0,1);
         $string = ltrim($val,$first).$first.'ay';
         array_push($newarr,$string);
     }
     return $newstring = implode(' ',$newarr);
 }
 $answer = fu('hello sinan');
 echo $answer;
?>

Question No 4:

<?php
 function rotate(){
     $arr = [1,2,3,4,5];
     $length = count($arr);
     $new = array();
     $k = 3;
     
     for($i=0;$i<$k;$i++){
         $last = $arr[$length -1];
         
         for ($j=$length -1;$j>0;$j--){
             $arr[$j] = $arr[$j -1];
             //echo $arr[$j];
         }
         $arr[0] = $last;
     }
     print_r($arr);
 }
 rotate();
?>



