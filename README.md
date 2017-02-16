# Months To Years (M2Y)
Change Months To Years &amp; Months.
Easy convert months into years &amp; months with javascript. 
```sh
if(months < 12){     
    months = months;
} else if (months % 12 == 0) {
    years = parseInt(months / 12);
    months = 0;    
} else {
    years = parseInt(months / 12);
    months = parseInt(months % 12);
}
```