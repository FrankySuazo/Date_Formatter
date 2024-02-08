# Date_Formatter
Working with dates in JavaScript can be challenging. Need to navigate various methods, formats, and time zones. In this project, I have learn how to work with the JavaScript Date object, including its methods and properties. You'll also learn how to correctly format dates.

This project will cover concepts such as the getDate(), getMonth(), and getFullYear() methods.

Start by getting the #current-date element using the .getElementById() method and assign it to a const variable called currentDateParagraph.

Use the .getElementById() method to get the #date-options element and use const to assign it to a variable named dateOptionsSelectElement.

Create a new const variable called date and assign it a Date object with new Date().

Using const, create a variable named day and assign it the day of the month from date with the .getDate() method.

Using const, create a variable named month and assign it the month from date with the .getMonth() method.

Remember to add 1 to the number returned by .getMonth().

Using const, create a variable named year and assign it the year from date with the .getFullYear() method.

Create a const variable named hours and assign it the hour from date with the .getHours() method.

Create a const variable named minutes and assign it the minutes from date with the .getMinutes() method.

Next, create a const variable named formattedDate and assign it empty template literals.

Inside the template literal, add an embedded expression that contains the day variable.

After the day variable, add a dash (-) followed by another embedded expression that contains the month variable.

After the month variable, add a dash followed by another embedded expression that contains the year variable.

To see the results of the formattedDate variable, add a console.log() statement and pass in the formattedDate variable as an argument.

Use the textContent property on currentDateParagraph to set its text content to the value of the formattedDate variable.

Also, make sure to remove console.log(formattedDate); line.

Attach the addEventListener method to the dateOptionsSelectElement. The first argument of the event listener should be the string change and the second argument should be an empty arrow function.

Create a switch statement and use dateOptionsSelectElement.value as the expression.

Add a case where the value is yyyy-mm-dd. Inside the case, set the text content of currentDateParagraph to the value of formattedDate.

Split formattedDate into an array of substrings with the .split() method and use a "-" as the separator.

Chain the .reverse() method to the end of .split() method.

Use the .join() method to join the reversed array elements into a string and use a "-" for the separator.

Add a break statement to the end of your case block.

Add another case with the value mm-dd-yyyy-h-mm. Inside that case, set the text content of currentDateParagraph to empty template literals.

Also, made sure to include a break statement to terminate the switch statement.

Inside the case for mm-dd-yyyy-h-mm, set the textContent property of currentDateParagraph to ${month}-${day}-${year} ${hours} Hours ${minutes} Minutes.

For the default case, set the text content of currentDateParagraph to the value of formattedDate.

And with that, your date formatter is complete! You can now format the current date three different ways.



