You are tasked with writing unit tests for a given piece of code. Your
goal is to create a comprehensive suite that verifies the functionality
and robustness of the code.

Here is the code you need to test:
```xml
<code_to_test>
{{CODE_TO_TEST}}
</code_to_test>
```

The code is written in the following programming language and
framework:
```xml
<language>
{{LANGUAGE}}
</language>
<framework>
{{FRAMEWORK}}
</framework>
```

Follow these instructions to create the tests:
```xml
<instructions>
1. Analyze the code and identify the main functions,
methods, or components that need to be tested.
2. For each identified element, create multiple test cases
that cover various scenarios, including:
- Normal expected inputs
- Edge cases
- Invalid inputs
- Boundary conditions
3. Write your tests using the testing framework:
<testing_framework>
{{TESTING_FRAMEWORK}}
</testing_framework>
4. Present each test in the following format:
<test>
<name>[Brief description of what the test is
checking]</name>
<code>
[Your test code here]
</code>
<explanation>
Explain why this test is important and what specific aspect
of the code it's verifying.
</explanation>
</test>
5. Ensure your tests cover at least 80% of the code's
functionality, including all major code paths and decision
points.
6. Pay special attention to potential edge cases and error
conditions. Include tests that verify the code handles
these situations correctly.
7. For each test, provide a clear explanation of what the
test is checking and why it's important. This will help
others understand the purpose and coverage of your tests.
8. After writing all the tests, provide a brief summary of
your testing approach and any areas of the code that might
require additional testing or consideration.
</instructions>
```

Present your final output in the following structure:
```xml
<response>
<testing_summary>
[Briefly describe your overall approach to testing this
code and any key considerations]
</testing_summary>
<tests>
[Include all your individual tests here, formatted as
specified above]
</tests>
<additional_notes>
[Include any additional thoughts, potential improvements,
or areas that might need further testing]
</additional_notes>
</response>
```

Remember to tailor your tests to the specific language and any
particular requirements or conventions of that language's testing
frameworks.
