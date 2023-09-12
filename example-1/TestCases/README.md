# Test Case

Test Cases provides more information to the Developers/System engineers working with the system. 
Together with the Requirements and Use Cases they should be enough for the Development team to understand without
interpretation what we want.

## Test Case possibilities
Usability testing will provide a fairly simple way of evaluating the solution. 

If the User (Actor) can do their task, the application works. Obviously we need to dress our test cases with other
scenarios as well, like performance or conformance to regulations.

```
tip: There are no hard rules, if you need to write a Test Case that isn't in the below list then do so!
The objective is to "Get What We Want"
```

Here are 5 ways to test for quality:
1. Reliability test
2. Performance test `example: T2`
3. Supportability test
4. Functional test
5. Usability test `example: T1`

Tests 1-4 are mostly done by Developers/QA/Systems administrators and is out of sight for normal users, and the Test Case 
itself will have to be written by the technical staff

## Coverage Map

Is as simple as taking all the Requirements, Use Cases and mapping them to a Test Case.

I like to map my UseCases 1:1 to TestCase numbers, but it doesn't really matter.

| R or U | T  |
|--------|----|
| U1     | T1 |
| R1     | T2 |
| R2,R5  | T3 |
