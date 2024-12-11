Break point :

Name                Class-Name (Size)    Minimum-Size    Maximum         Screen-Device-Name
Extra extra large   xxl                  ≥1400px         >1400px         Laptop
Extra large         xl                   ≥1200px         1399px          laptop
Large               lg                   ≥992px          1199px          laptop
Medium              md                   ≥768px          991px           tabs
Small               sm                   ≥576px          757px           tabs
Extra small         None                 0px             <576px          Mobile



Jab hum kisi tag ko class-Name denge to we apne se badi class pe bhi lag jaygi par choti par nhi lage gi 
    for example : text-lg-center to yeh xl and xxl pr bhi text center hoga 
    for example : text-xxl-end to yeh xxl pr override ho jayga and text-center se text-end ho jayga 


---------------------------------------------------------------------------------

Container :
                    <576px      ≥576px      ≥768px      ≥992px      ≥1200px     ≥1400px
.container	        100%	    540px	    720px	    960px	    1140px	    1320px
.container-fluid	100%	    100%	    100%	    100%	    100%	    100%


agr aapko ko container y kisi bhi boostrap ki class ko change kr na hu ta aap uski class name ko same he apne custum css me likhe ke override kr de. 



--------------------------------------------------------------------------------

12-Column Layout :


row => col-1 => col-12
row => col-sm-1 => col-12


--------------------------------------------------------------------------------

Auto Column Layout :


--------------------------------------------------------------------------------

Gutter Classes :

gx-0 => for padding left - right   || gx-1 === 2px right, 2px left 
gy-0 => for margin top - bottom    || gy-1 === 2px right, 2px left 


--------------------------------------------------------------------------------

Margin :

m   - All round
my  - top-bottm
mx  - left-right
mt  - top
mb  - bottom
ms  - left
me  - right


m-0 => 0rem     =>  0px  
m-1 => 0.25rem  =>  4px
m-2 => 0.5rem   =>  8px
m-3 => 1rem     => 16px
m-4 => 1.5rem   => 24px
m-5 => 3rem     => 48px



------------------------------------------------------------


Padding : 

p   - All round
py  - top-bottm
px  - left-right
pt  - top
pb  - bottom
ps  - left
pe  - right


p-0 => 0rem     =>  0px  
p-1 => 0.25rem  =>  4px
p-2 => 0.5rem   =>  8px
p-3 => 1rem     => 16px
p-4 => 1.5rem   => 24px
p-5 => 3rem     => 48px

pt-md-2 , p-lg-3