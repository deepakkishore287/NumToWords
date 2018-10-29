# Number To Word Conversion Package.

Installing Package via Composer.

composer require deepkishore/num-to-words

 In Controller 
 
 namespace App\Http\Controllers;
 
 use kishore\NumToWords\NumToWordServiceProvider;

 class Controller 
 
 {
  
   public function abc()                
 {
   
        $num = 1234;
        $words = NumToWordServiceProvider::getIndianCurrency($num);
        echo words;
    
    }
  
 }
