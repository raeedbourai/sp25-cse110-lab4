# Part 1
1. 20
2. 20
3. We should not use var because it provides function wide scope, which can cause naming conflicts and scoping issues
4. 20
5. This line returns an error because we used keyword _let_ which has block scope, meaning when we call result outside that block, it will not be defined
6. This line returns an error because we are trying to reassign a variable with keyword _const_ after it already has been assigned
7. This line returns an error because keyword _const_ has same scope as let, meaning if we try to access it outside of its block, it will not be defined
