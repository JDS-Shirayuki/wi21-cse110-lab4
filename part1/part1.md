1. The length of prices will be printed to console since var does not have block scope
2. The last update of discountedPrice value will be printed to console since var does not have block scope
3. The final updated value of finalPrice will be printed to console since the value of finalPrice is assigned and updated before printing within the function discountPrices()
4. It will return [50, 100, 150] since the for loop of the function will do a 50% discount on every element of the input array prices
5. It will be an error since i is defined inside the for loop
6. It will be an error since discountedPrice is defined inside the for loop
7. The final updated value of finalPrice will be printed to console correctly since the value of finalPrice is assigned and updated before printing within the function discountPrices()
8. It will return [50, 100, 150] since the for loop of the function will do a 50% discount on every element of the input array prices
9. It will be an error since i is defined inside the for loop
10. The first assignment of discountedPrice will be printed to console since the discountedPrice is declared as a constant var
11. The first update of finalPrice will be printed to console since the finalPrice is calculated based on discountedPrice each iteration, and discountedPrice keeps constant always
12. It will return [50, 50, 50]. The returned value of discountPrices() is discounted. And discounted is calculated based on finalPrice and discountedPrice. Since finalPrice and discountedPrice doesn't change, elements of discounted also keep the same after the first update of element 50.
13. A: student.name
    B: student[Grad Year]
    C: student.greeting()
    D: student[Favorite Teacher].name
    E: student.courseLoad[0]
