let price = 750;   

let category = (price >= 1000) ? "Expensive" :  
 (price >= 500) ? "Moderate" :  
 (price > 0) ? "Affordable" :  
 (price === 0) ? "Free" :  
 "Invalid Price";  

console.log(category); 
