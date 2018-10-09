# Stop doing code reviews.

Don't just look at the code.

Look at what we're trying to accomplish holistically:

- Is the problem well-defined? 
- Is the defined problem the right problem?
- Is the proposed solution a good one?
- Is there a good test plan?
- Will this change create other problems?

Look at artifacts aside from the code:
- Are the commit messages well-written?
- Are the commits cohesive and iterative?
- Have appropriate automated tests been written?
- Have appropriate manual tests been executed?

Then, and only then, look at the code:
- Is the code written to be read?
- Is the code in better shape than it was found?
- Are the code changes functionally correct?
- Will these changes introduce non-functional issues? (performance, security, scalability) 

As much as possible, talk about these things before coding to avoid wasting time and energy across the team.