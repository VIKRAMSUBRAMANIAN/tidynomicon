- Use `for (loop_variable in collection){ ...body... }` to create a loop.
- Use `if (expression) { ...body... } else if (expression) { ...body... } else { ...body... }` to create conditionals.
- Expression conditions must have length 1; use `any(...)` and `all(...)` to collapse logical vectors to single values.
- Use `function(...arguments...) { ...body... }` to create a function.
- Use variable <- function(...arguments...) { ...body... }` to create a function and give it a name.
- The body of a function can be a single expression or a block in curly braces.
- The last expression evaluated in a function is returned as its result.
- Use `return(expression)` to return a result early from a function.
