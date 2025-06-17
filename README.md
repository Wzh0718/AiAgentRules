# AiAgentRules
This is a collection of some AI agent rules that I have debugged and optimized personally, covering practical rules that I use in daily life. All rules have been tested in practice and have stable effects. I recommend you to refer to and use them.
## [Cursor Rules](https://github.com/Wzh0718/AiAgentRules/tree/main/cursor_rules)
### Notes
1. Mcp Server needs to use context7 and server-sequential-thinking
2. In Cursor Rules, I actually use a combination of problem memory and project memory provided by Cursor version 1.0.
  - Use sequential splitting to evaluate whether memory is needed based on scores, which can constrain the thinking of the AI ​​model and solve the problem based on the latest doc
  - Standardize the link problem in the problem memory to solve the problem of excessive modification and repeated modification in the cursor process of large projects
  - In daily simple questions, AI actively calls Mcp server to summarize and think about the problem, which can reduce the model's own hallucination problem to a greater extent.
### Version
  The current version is v0.2.1
  
  update Log
   - New development process requires the conversion of code logic into SQL logic
