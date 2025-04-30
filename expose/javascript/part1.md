1. values added: 20
2. final result: 20
3. You should not use var because var variables are not restricted to the block that they are defined in and have function scope, so it makes code less predicatble and more confusing.
4. values added: 20
5. ReferenceError: result is not defined. This errors because let has block scope so it is only in the if block and the variable does not exists where it is being called in line 13.
6. TypeError: Assignment to constant variable. This errors because const variables cannot be reassigned after it is assigned the first time and result is assigned in line 5 but then reassigned in line 7.
7. ReferenceError: result is not defined. This would throw this error because const has block scope so the so it is only in the if block and the variable does not exists where it is called in line 13. However, this error is not actually reached because the code would have already errored at line 7 with the TypeError.