# Months To Years (M2Y)
Change Months To Years &amp; Months.  
Easy convert months into years &amp; months with javascript.   
```sh
if(months >= 12){
    years = parseInt(months / 12);
    months = parseInt(months % 12);
}
```

# Days into Years, Months & Days
Change Days To Years, Months &amp; Days.  
Easy convert days into years, months &amp; days with javascript.   
```sh
// How many years
years  = parseInt(days / 365)  

// How many months          
days   = parseInt(days % 365)            
months = parseInt(days / 30)  

// How many days
days   = parseInt(days % 30)
```