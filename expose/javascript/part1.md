## Part 1
1. values added: 20
2. final result: 20
3. values added: 20
4. Line 13 results in an error. It calls result out of scope. Result is declared via let and is only in scope in that specific block. 
5. Line 9 results in an error. Since result is a const, line 7 attempts to change the value of result. This leads to an assignment error.
6. Line 13 results in an error. Since result is a const, line 7 attempts to change the value of result. This leads to an assignment error.