Adobe ColdFusion variables are the most frequently used operands in ColdFusion expressions. Variable values can be set and reset, and can be passed as attributes to CFML tags. Variables can be passed as parameters to functions, and can replace most constants.
To create and use ColdFusion variables, you should know the following:

- How variables can represent different types of data
- How the data types get converted
- How variables exist in different scopes.

You create most ColdFusion variables by assigning them values. (You must use the ArrayNew function to create arrays.) Most commonly, you create variables by using the cfset tag. You can also use the cfparam tag, and assignment statements in CFScript. Tags that create data objects also create variables. For example, the cfquery tag creates a query object variable.
ColdFusion automatically creates some variables that provide information about the results of certain tags or operations. ColdFusion also automatically generates variables in certain scopes, such as Client and Server. For information on these special variables, see Reserved Words and Variables in the CFML Reference and the documentation of the CFML tags that create these variables.
ColdFusion generates an error when it tries to use a variable before it is created. This can happen, for example, when processing data from an incompletely filled form. To prevent such errors, test for the variable's existence before you use it. For more information on testing for variable existence.

VARIABLE CHARACTERISTICS
You can classify a variable using the following characteristics:
- The data type of the variable value, which indicates the kind of information a variable represents, such as number, string, or date
- The scope of the variable, which indicates where the information is available and how long the variable persists.
