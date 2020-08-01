<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <link rel="stylesheet" href="Technical Documentation Page.css">
    <title>JS Documentation</title>
  </head>
  <body>
      <main id="main-doc">
        <div class="row">
              <div class="col-lg-3">
                <nav id="navbar">
                    <header>
                    <h1>JS Documentation</h1>
                </header>
                    <ul id="content">
                        <li><a class="nav-link" href="#introduction">Introduction</a></li>
                        <li><a class="nav-link" href="#what_you_should_already_know">What you should already know</a></li>
                        <li><a class="nav-link" href="#javascript_and_java">Javascript and Java</a></li>
                        <li><a class="nav-link" href="#hello_world">Hello world</a></li>
                        <li><a class="nav-link" href="#variables">Variables</a></li>
                        <li><a class="nav-link" href="#declaring_variables">Declaring variables</a></li>
                        <li><a class="nav-link" href="#variable_scope">Variable scope</a></li>
                        <li><a class="nav-link" href="#global_variables">Global variables</a></li>
                        <li><a class="nav-link" href="#constants">Constants</a></li>
                        <li><a class="nav-link" href="#data_types">Data types</a></li>
                        <li><a class="nav-link" href="#if_else_statement">if else statement</a></li>
                        <li><a class="nav-link" href="#while_statement">While statement</a></li>
                        <li><a class="nav-link" href="#function_declarations">Function declarations</a></li>
                        <li><a class="nav-link" href="#reference">Reference</a></li>
                    </ul>
                </nav>
            </div>
            <div class="col-lg-9">
                <!-- One -->
                <section class="main-section" id="introduction">
                    <header>
                        <h3>Introduction</h3>
                    </header>
                    <p>JavaScript is a cross-platform, object-oriented scripting language. It is a small and lightweight language. Inside a host environment (for example, a web browser), JavaScript can be connected to the objects of its environment to provide programmatic control over them.
                        <br> <br>
                        JavaScript contains a standard library of objects, such as Array, Date, and Math, and a core set of language elements such as operators, control structures, and statements. Core JavaScript can be extended for a variety of purposes by supplementing it with additional objects; for example:
                    <ul>
                        <li>Client-side JavaScript extends the core language by supplying objects to control a browser and its Document Object Model (DOM). For example, client-side extensions allow an application to place elements on an HTML form and respond to user events such as mouse clicks, form input, and page navigation.</li>
                        <li>Server-side JavaScript extends the core language by supplying objects relevant to running JavaScript on a server. For example, server-side extensions allow an application to communicate with a database, provide continuity of information from one invocation to another of the application, or perform file manipulations on a server.</li>
                    </ul>
                    </p>
                </section>
                <!-- Two -->
                <section class="main-section" id="what_you_should_already_know">
                    <header>
                        <h3>What you should already know</h3>
                    </header>
                    <p>
                        This guide assumes you have the following basic background:
                        <ul>
                            <li>A general understanding of the Internet and the World Wide Web (WWW).</li>
                            <li>Good working knowledge of HyperText Markup Language (HTML).</li>
                            <li>Some programming experience. If you are new to programming, try one of the tutorials linked on the main page about JavaScript.</li>
                        </ul>
                    </p>
                </section>
                <!-- Three -->
                <section class="main-section" id="javascript_and_java">
                    <header>
                        <h3>JavaScript and Java</h3>
                    </header>
                    <p>JavaScript and Java are similar in some ways but fundamentally different in some others. The JavaScript language resembles Java but does not have Java's static typing and strong type checking. JavaScript follows most Java expression syntax, naming conventions and basic control-flow constructs which was the reason why it was renamed from LiveScript to JavaScript.
                        <br> <br>
                        In contrast to Java's compile-time system of classes built by declarations, JavaScript supports a runtime system based on a small number of data types representing numeric, Boolean, and string values. JavaScript has a prototype-based object model instead of the more common class-based object model. The prototype-based model provides dynamic inheritance; that is, what is inherited can vary for individual objects. JavaScript also supports functions without any special declarative requirements. Functions can be properties of objects, executing as loosely typed methods.
                        <br> <br>
                        JavaScript is a very free-form language compared to Java. You do not have to declare all variables, classes, and methods. You do not have to be concerned with whether methods are public, private, or protected, and you do not have to implement interfaces. Variables, parameters, and function return types are not explicitly typed.</p>
                </section>
                <!-- Four -->
                <section class="main-section" id="hello_world">
                    <header>
                        <h3>Hello World</h3>
                    </header>
                    <p>
                        To get started with writing JavaScript, open the Scratchpad and write your first "Hello world" JavaScript code: <br> <br>
                        <code>function greetMe(yourName) { alert("Hello " + yourName); }
                            greetMe("World");</code> <br> <br>
                            Select the code in the pad and hit Ctrl+R to watch it unfold in your browser!
                    </p>
                </section>
                <!-- Five -->
                <section class="main-section" id="variables">
                    <header>
                        <h3>Variables</h3>
                    </header>
                    <p>
                        You use variables as symbolic names for values in your application. The names of variables, called identifiers, conform to certain rules.
                        <br> <br>
                        A JavaScript identifier must start with a letter, underscore (_), or dollar sign ($); subsequent characters can also be digits (0-9). Because JavaScript is case sensitive, letters include the characters "A" through "Z" (uppercase) and the characters "a" through "z" (lowercase).
                        <br> <br>
                        You can use ISO 8859-1 or Unicode letters such as å and ü in identifiers. You can also use the Unicode escape sequences as characters in identifiers. Some examples of legal names are Number_hits, temp99, and _name.
                    </p>
                </section>
                <!-- Six -->
                <section class="main-section" id="declaring_variables">
                    <header>
                        <h3>Declaring Variables</h3>
                    </header>
                    <p>
                        You can declare a variable in three ways: <br> <br>
                        With the keyword var. For example, <br> <br>
                        <code>var x = 42.</code> <br> <br>
                        This syntax can be used to declare both local and global variables.
                        <br> <br>
                        By simply assigning it a value. For example, <br> <br>
                        <code>x = 42.</code> <br> <br>
                        This always declares a global variable. It generates a strict JavaScript warning. You shouldn't use this variant.
                        <br> <br>
                        With the keyword let. For example, <br> <br>
                        <code>let y = 13.</code> <br> <br>
                        This syntax can be used to declare a block scope local variable. See Variable scope below.
                    </p>
                </section>
                <!-- Seven -->
                <section class="main-section" id="variable_scope">
                    <header>
                        <h3>Variable scope</h3>
                    </header>
                    <p>When you declare a variable outside of any function, it is called a global variable, because it is available to any other code in the current document. When you declare a variable within a function, it is called a local variable, because it is available only within that function.
                        <br> <br>
                        JavaScript before ECMAScript 2015 does not have block statement scope; rather, a variable declared within a block is local to the function (or global scope) that the block resides within. For example the following code will log 5, because the scope of x is the function (or global context) within which x is declared, not the block, which in this case is an if statement.
                        <br> <br>
                        <code>if (true) { var x = 5; } console.log(x); // 5</code> <br> <br>
                        This behavior changes, when using the let declaration introduced in ECMAScript 2015. <br> <br>
                        <code>if (true) { let y = 5; } console.log(y); // ReferenceError: y is not
                            defined</code> <br> <br>
                    </p>
                </section>
                <!-- Eight -->
                <section class="main-section" id="global_variables">
                    <header>
                        <h3>Global variables</h3>
                    </header>
                    <p>
                        Global variables are in fact properties of the global object. In web pages the global object is window, so you can set and access global variables using the window.variable syntax.
                        <br> <br>
                        Consequently, you can access global variables declared in one window or frame from another window or frame by specifying the window or frame name. For example, if a variable called phoneNumber is declared in a document, you can refer to this variable from an iframe as parent.phoneNumber.
                    </p>
                </section>
                <!-- Nine -->
                <section class="main-section" id="constants">
                    <header>
                        <h3>Constants</h3>
                    </header>
                    <p>You can create a read-only, named constant with the const keyword. The syntax of a constant identifier is the same as for a variable identifier: it must start with a letter, underscore or dollar sign and can contain alphabetic, numeric, or underscore characters. <br> <br>
                        <code>const PI = 3.14;</code> <br> <br>
                        A constant cannot change value through assignment or be re-declared while the script is running. It has to be initialized to a value.
                        <br> <br>
                        The scope rules for constants are the same as those for let block scope variables. If the const keyword is omitted, the identifier is assumed to represent a variable.
                        <br> <br>
                        You cannot declare a constant with the same name as a function or variable in the same scope. For example: <br> <br>
                        <code>// THIS WILL CAUSE AN ERROR function f() {}; const f = 5; // THIS WILL
                            CAUSE AN ERROR ALSO function f() { const g = 5; var g; //statements
                            }</code> <br> <br>
                            However, object attributes are not protected, so the following statement is executed without problems. <br> <br>
                            <code>const MY_OBJECT = {"key": "value"}; MY_OBJECT.key = "otherValue";</code>
                    </p>
                </section>
                <!-- Ten -->
                <section class="main-section" id="data_types">
                    <header>
                        <h3>Data types</h3>
                    </header>
                    <p>The latest ECMAScript standard defines seven data types:
                        <ul>
                            <li>Six data types that are primitives:
                                <ul>
                                    <li>Boolean. true and false</li>
                                    <li>null. A special keyword denoting a null value. Because JavaScript is case-sensitive, null is not the same as Null, NULL, or any other variant.</li>
                                    <li>undefined. A top-level property whose value is undefined.</li>
                                    <li>Number. 42 or 3.14159.</li>
                                    <li>String. "Howdy"</li>
                                    <li>Symbol (new in ECMAScript 2015). A data type whose instances are unique and immutable.</li>
                                </ul>
                            </li>
                            <li>and Object</li>
                        </ul>
                        Although these data types are a relatively small amount, they enable you to perform useful functions with your applications. Objects and functions are the other fundamental elements in the language. You can think of objects as named containers for values, and functions as procedures that your application can perform.
                    </p>
                </section>
                <!-- Eleven -->
                <section class="main-section" id="if_else_statement">
                    <header>
                        <h3>if else statement</h3>
                    </header>
                    <p>
                        Use the if statement to execute a statement if a logical condition is true. Use the optional else clause to execute a statement if the condition is false. An if statement looks as follows: <br> <br>
                        <code>if (condition) { statement_1; } else { statement_2; }</code> <br> <br>
                        condition can be any expression that evaluates to true or false. See Boolean for an explanation of what evaluates to true and false. If condition evaluates to true, statement_1 is executed; otherwise, statement_2 is executed. statement_1 and statement_2 can be any statement, including further nested if statements.
                        <br> <br>
                        You may also compound the statements using else if to have multiple conditions tested in sequence, as follows: <br> <br>
                        <code>if (condition_1) { statement_1; } else if (condition_2) { statement_2;
                        } else if (condition_n) { statement_n; } else { statement_last; }</code> <br> <br>
                        In the case of multiple conditions only the first logical condition which evaluates to true will be executed. To execute multiple statements, group them within a block statement ({ ... }) . In general, it's good practice to always use block statements, especially when nesting if statements: <br> <br>
                        <code>if (condition) { statement_1_runs_if_condition_is_true;
                            statement_2_runs_if_condition_is_true; } else {
                            statement_3_runs_if_condition_is_false;
                            statement_4_runs_if_condition_is_false; }</code> <br> <br>
                            It is advisable to not use simple assignments in a conditional expression, because the assignment can be confused with equality when glancing over the code. For example, do not use the following code: <br> <br>
                            <code>if (x = y) { /* statements here */ }</code> <br> <br>
                            If you need to use an assignment in a conditional expression, a common practice is to put additional parentheses around the assignment. For example: <br> <br>
                            <code>if ((x = y)) { /* statements here */ }</code>
                    </p>
                </section>
                <!-- Twelve -->
                <section class="main-section" id="while_statement">
                    <header>
                        <h3>While statement</h3>
                    </header>
                    <p>
                        A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows: <br> <br>
                        <code>while (condition) statement</code> <br> <br>
                        If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
                        <br> <br>
                        The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops and control is passed to the statement following while.
                        <br> <br>
                        To execute multiple statements, use a block statement ({ ... }) to group those statements.
                        <br> <br>
                        Example: <br> <br>
                        The following while loop iterates as long as n is less than three: <br> <br>
                        <code>var n = 0; var x = 0; while (n < 3) { n++; x += n; }</code> <br> <br>
                        With each iteration, the loop increments n and adds that value to x. Therefore, x and n take on the following values: <br> <br>
                        <ul>
                            <li>After the first pass: n = 1 and x = 1</li>
                            <li>After the second pass: n = 2 and x = 3</li>
                            <li>After the third pass: n = 3 and x = 6</li>
                        </ul>
                        After completing the third pass, the condition n < 3 is no longer true, so the loop terminates.
                    </p>
                </section>
                <!-- Thirteen -->
                <section class="main-section" id="function_declarations">
                    <header>
                        <h3>Function declarations</h3>
                    </header>
                    <p>
                        A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by: 
                        <ul>
                            <li>The name of the function.</li>
                            <li>A list of arguments to the function, enclosed in parentheses and separated by commas.</li>
                            <li>The JavaScript statements that define the function, enclosed in curly brackets, { }.</li>
                        </ul>
                        For example, the following code defines a simple function named square: <br> <br>
                        <code>function square(number) { return number * number; }</code> <br> <br>
                        The function square takes one argument, called number. The function consists of one statement that says to return the argument of the function (that is, number) multiplied by itself. The return statement specifies the value returned by the function. <br> <br>
                        <code>return number * number;</code> <br> <br>
                        Primitive parameters (such as a number) are passed to functions by value; the value is passed to the function, but if the function changes the value of the parameter, this change is not reflected globally or in the calling function.
                    </p>
                </section>
                <!-- Fourteen -->
                <section class="main-section" id="reference">
                    <header>
                        <h3>Reference</h3>
                    </header>
                    <p>
                        <ul>
                            <li>All the documentation in this page is taken from <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide" target="__blank">MDN</a></li>
                        </ul>
                    </p>
                </section>
            </div>
        </div>
</main>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
  </body>
</html>
