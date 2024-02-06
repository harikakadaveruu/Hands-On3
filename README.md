
3. The polynomial regression model reveals the upper and lower bound polynomials on the curve. With a positive leading coefficient in our quadratic polynomial, it assumes a U-shape and establishes its minimum value at n= -b/(2a). Here, 'a' represents the coefficient of quadratic terms while 'b' stands for linear ones.
We can identify the upper and lower bounds on the curve through a polynomial regression model. This quadratic polynomial exhibits a U-shape due to its positive leading coefficient, with its minimum value occurring at n= -b/(2a), where 'a' refers to quadratics terms' coefficients and 'b' denotes linear term’s coefficient; 
indeed this is an intriguing feature of such polynomials. When we substitute the estimated coefficients from our polynomial regression model, we obtain: n_0= -0.0002/(2*0.0001)=1000.
The data fits a polynomial of the form: t=0.0001n^2-0.0002n+0.0005, where 't' signifies the time consumed by our function and 'n' represents input value; notably, this quadratic equation hits its lowest point at n=1000 with a minimum value of 0.0005.
We observe that The leading coefficient--a constant factor differentiating our algorithm's operation count(n^2) from it--equals to 0.001 Therefore, the big-O, big-Omega, and big-theta notations for the algorithm are all Θ(n^2).

After modification of function

4. The time taken to run the function will increase slightly, as an additional operation is performed in each iteration of the inner loop. However, this alteration won't impact the algorithm's overall time complexity, which continues to be O(n^2).
5. The polynomial fit to the time vs n data will also remain the same, as the additional operation does not change the number of iterations of the inner loop.
