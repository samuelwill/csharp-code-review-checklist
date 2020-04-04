## C# Code Review Checklist

### General
- [ ] Access modifiers are made as private as possible

### Maintainence
- [ ] All names are clear, descriptive and accurate. Clear naming is preferred over comments
- [ ] Well-named enums are used instead of magic strings and numbers
- [ ] Functions avoid side effects
- [ ] Conditionals should be positive, not negative
- [ ] Methods do not accept more than 3 parameters
- [ ] All methods and classes do just one thing / follow SRP
- [ ] SOLID principles are adhered to
- [ ] All code has passed linting

### Performance and Scalability
- [ ] Reviewer has stepped through all modified code paths using a performance data set to look for performance / memory / CPU usage issues
- [ ] Appropriate data structures have been used
- [ ] async / await is used for I/O bound code paths
