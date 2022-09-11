> Payment-intergration-in-erpnext
> ---
> * First go to the intergration, and select the Razorpay setting option
>
> ![image](https://user-images.githubusercontent.com/54163741/189280597-e4c12848-9b80-4a42-abf3-a2f1528f8bad.png)
> ---
> ![image](https://user-images.githubusercontent.com/54163741/189281702-ee666cb3-e0c0-41e4-80f7-dd3dc1c4bca7.png)
>
> ![image](https://github.com/RAGHAVSHARMA01/Payment-intergration-in-erpnext/blob/main/Screenshot%20(3).png)
>
> * To enable RazorPay payment service, you need to configure parameters like API Key, API Secret. Then comes the turn to set the chart of the account, to do this on enabling service, the system will create Payment Gateway record and Account head in the Chart of Account with account type as Bank.
>
> * Now search the option for the payment gateway and the we could see that razorpay gateway will be automatically included and then no changes would be there, just check mark the option to make the razorpay as default gateway
>
> ![image](https://user-images.githubusercontent.com/54163741/189282260-d784ec7f-0ca4-46c6-9950-a9371bd300ef.png)
>
> * Now, all of the users of integration would have the problem and a query that how will the potal open or where would be the link of the potal to pay money, the emails containing the url to the payment potal could be done by add the following:-
>
> * ==href"{{ payment_url }}">click here to pay (use your appopriate tags)==
>
> * You can also add the deafult message in the image shown above to be send through the email by adding the company name using {{doc.company}} or the    perticular a ttritutes you want to put in, this can be done through the location Accounting --> Payment Gateway Account --> Razorpay - INR
>
> **Was a simple procedure to do**
> :smile:









