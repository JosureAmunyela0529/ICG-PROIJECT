# ICG-PROJECT

#customer relationship management database to serve as a sales tool










HI GUYS HERE IS THE REPOSITORY, I AND JOSUA MADE THE SAME CHOICE I THINK WE SHOULD WORK NOW ON THIS AND FINSIH UP

START
PROMPT items
GET
ItemName=INPUT("Item name:Shampoo, Bangs, Fringes")
IF ItemName=("Shampoo") THEN
          DISPLAY("You have selected Shampoo, it costs NS500")
ELSE
     IF ItemName=("Bangs") THEN
          DISPLAY("You have selected Bangs, it costs NS700")
ELSE 
    IF ItemName=("Fringes") THEN
          DISPLAY("You have selected Fringes, it costs NS100")
ELSE DISPLAY("This Item doesn't exist!")
ENDIF
ENDIF
ENDIF
END

GET 
payement=INPUT("How do you want to pay?:Credit Card, Cash")
IF payement=stg("Credit card") THEN
                DISPLAY("Enter your Credit card number")
 ELSE 
 DISPLAY  (Please feel free to reach our distributors Iscgem Pharmacies Namibia and Pnp Namibia stores")
 ENDIF
 END

Prompt Credit_card_number
 GET Credit_Card_number
 DISPLAY("Thanks")
INPUT ("enter your amount")

 GET Amount
 IF Amount=INT(500)
            DISPLAY("You have bought Shampoo, enter your Home addres")
 ELSE
       IF Amount=INT(700)
            DISPLAY("You have bought Bangs, enter your Home addres")
  ELSE 
       IF Amount=INT(500)
            DISPLAY("You have bought Fringes, enter your Home addres")
     ELSE DISPLAY ("Error")      
            
ENDIF  
ENDIF  
ENDIF  
END

Prompt Address
GET address 
DISPLAY ("Thanks for trusting us, your item will be delivered by tomorrow")
End
           
           
           
           
 #HUMAN RESOURCE1
 #this is Josua 
 
 
 
 
 
 
 
 
 
 
 
 
 START

PROMPT  sellingPrice,costPrice
GET sellingPrice, costPrice

 sellingPrice= sellingPrice - costPrice

IF sellingPrice < costPrice 
THEN
 WRITE ("loss was made")
ELSE
     IF sellingPrice > costPrice
     
     THEN 
 Difference amount = sellingPrice - costPrice
GET difference amount

Financial return percentage = difference amount ÷ costPrice × 100
ENDIF
DISPLAY financial return percentage
END



Desk check

sellingPrice = N$ 9000
costPrice = N$ 3000
Deference amount = N$ 6000
Financial return percentage = 200% expect output.

START

Prompt for sellingPrice
sellingPrice = N$ 9000
Prompt for costPrice
costPrice = N$ 3000
5 If sellingPrice < costPrice then write 'loss was made'
If else sellingPrice > costPrice then difference amount = N$ 9000 - N$ 3000
Get difference amount = N$ 6000
Financial return percentage = N$ 6000 ÷ N$ 3000 × 100
End if
Display financial return percentage = 200%
END

 
 
 
 
 
 
 
 
 




PROMPT product 

Get ItemName=array(Shampoo, ),(Fringes),(Bangs)

DOWHILE( ItemName=0to2)

IF products are >= 35 THEN

Execute'PRODUCT SHOULD BE TRANSPORTED TO DESTINATION'
ELSE
Execute 'THE AMOUNT OF PRODUCT YOU SELECTED DOES NOT MEET THE MINIMUM VALUE,PLEASE WAIT TILL IT DOES'
ELSE
Execute'ERROR,PLEASE TRY AGAIN LATER'
ENDIF
STOP

Write a program to calculate the store values and include the VAT
START
Enter num
For e = 1 to num DO
Enter item(e)
Enter price
Enter Bprice
Enter code
IF code = 1 THEN
Sprice(e)= Bprice * 2.00 * 1.05
ELSE
Sprice(e)= Bprice * 1.00
endif
ENDFOR
For e = 1 to num DO
Print item(e)
ENDFOR
STOP


