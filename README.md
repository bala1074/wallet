# wallet
A simple wallet implementation project where users can manage their wallet amount. This project was done using JSP and servlets.

Project Requirements : 

Wallet project requirements:
		
	   1. Sing up page            ("/signup", fields: name, email, password, confirm password, phone number, Method: POST
	   2. Sign in page            ("/login", fields: email, password  Method: POST)
	   3. Add money to wallet     ("/addmoney", fields: cash, tip: just have an upper limit and accept whatever they add, Method: POST)
	   4. View wallet             ("/wallet", information: Name, cash, Method: GET)
	   4. Use money               ("/transact", fields: Usage Comments, Amount Method: POST)
	   
	   
	   Constraints:
		1. Only logged in user can add/use money
		2. Unauthorized to access to URLs should redirect user to Sign in page 
		3. Try to avoid scriptlet tags, use EL and JSTL instead. 
		4. Try to put as much as business away from JSP. Put it in java classes/servlets instead...
		5. Add client and server side validations.
		


Technologies Used :
1. JSP ( with JSTL and EL)
2. Servlets
3. JDBC ( for connecting to MySQL Database)
4. MySQL
5. CSS
6. HTML

Some of the important things to learn from this project : 
1. Usage of JSP with Expression language and JSTL without using JSP scriptlets
2. Usage of Servlets at server side
3. Usage of servlet filter to check whether user authenticated or not.
4. JDBC connection
5. MySQL queries and usage of prepared statements to avoid SQL injection
6. Accessing the resources(JSP's) which are inside the WEB-INF(protected area) using servlets.
7. Session management to provide user login and logout functionality.

