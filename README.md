# Number To Word Conversion Package.

Installating Package via Composer.

composer require deepkishore/num-to-words

 In Controller 
 
 namespace App\***;
 
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
