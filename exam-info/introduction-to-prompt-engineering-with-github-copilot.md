---


---

<h2 id="github-copilot-across-environments-ide-chat-github.com-and-command-line-—-summary">GitHub Copilot Across Environments: IDE, Chat, <a href="http://GitHub.com">GitHub.com</a>, and Command Line — Summary</h2>
<p>GitHub Copilot is an advanced AI-powered coding assistant designed to significantly improve developer productivity across <strong>the entire development lifecycle</strong>. By automating repetitive tasks, providing intelligent code completion, and generating full code blocks, Copilot enables developers to focus on higher-level problem solving, design, and innovation—from writing the first line of code to completing pull requests.</p>
<p>Copilot is built to <strong>meet developers where they work</strong>, offering flexible interaction modes that integrate seamlessly into different environments. Understanding how and when to use these interaction methods is essential to unlocking Copilot’s full potential and accelerating the delivery of high-quality code.</p>
<h3 id="multi-environment-interaction-model">Multi-Environment Interaction Model</h3>
<p>GitHub Copilot supports multiple workflows and environments:</p>
<ul>
<li>
<p><strong>IDE (e.g., VS Code)</strong><br>
Context-aware code completion, inline suggestions, and refactoring support directly while coding.</p>
</li>
<li>
<p><strong>Copilot Chat</strong><br>
Conversational, natural-language interactions for:</p>
<ul>
<li>Generating complex code</li>
<li>Debugging issues</li>
<li>Explaining unfamiliar code</li>
<li>Refactoring and improving existing logic</li>
</ul>
</li>
<li>
<p><strong><a href="http://GitHub.com">GitHub.com</a></strong><br>
Repository-aware assistance for:</p>
<ul>
<li>Code exploration</li>
<li>Pull request summaries and reviews</li>
<li>Agent-driven tasks</li>
<li>Collaborative workflows during code reviews</li>
</ul>
</li>
<li>
<p><strong>Command Line (CLI)</strong><br>
AI-assisted terminal workflows including:</p>
<ul>
<li>Command explanations</li>
<li>Command suggestions</li>
<li>Executing and automating CLI tasks</li>
</ul>
</li>
</ul>
<h3 id="what-you-will-learn-in-this-module">What You Will Learn in This Module</h3>
<p>By completing this module, you will learn how to:</p>
<ul>
<li>Use <strong>auto-suggestions</strong> and the <strong>multiple suggestions pane</strong> to accelerate coding while adapting to different coding styles</li>
<li>Provide effective <strong>context</strong> through inline comments, block comments, docstrings, and structured prompts to improve code generation accuracy</li>
<li>Interact with GitHub Copilot using <strong>natural language</strong> to generate code, debug, and understand existing implementations</li>
<li>Improve chat responses using <strong>scope referencing</strong>, <strong>slash commands</strong>, and <strong>agents</strong> for faster task completion</li>
<li>Leverage Copilot on <strong><a href="http://GitHub.com">GitHub.com</a></strong> for pull request assistance, repository insights, and collaborative review workflows</li>
<li>Use <strong>GitHub Copilot CLI</strong> to understand, generate, and execute terminal commands</li>
<li>Configure Copilot CLI settings, aliases, and <strong>privacy options</strong>, including opting out of usage data collection</li>
</ul>
<h3 id="key-takeaway">Key Takeaway</h3>
<p>GitHub Copilot is not limited to code completion—it is a <strong>cross-environment AI assistant</strong> that enhances productivity in the IDE, chat interfaces, <a href="http://GitHub.com">GitHub.com</a>, and the command line. Mastering these interaction modes allows developers to work faster, smarter, and more confidently across the entire development workflow.</p>
<h1 id="code-completion-with-github-copilot">Code Completion with GitHub Copilot</h1>
<p>GitHub Copilot code completion features live directly inside your <strong>IDE</strong>, where you write, review, and refactor code. Copilot integrates seamlessly with editors such as <strong>Visual Studio Code</strong> and <strong>JetBrains IDEs</strong>, providing intelligent auto-suggestions, a multiple suggestions pane, and adaptive support for different coding styles.</p>
<p>Understanding how these features work—and when to use them—helps you maximize Copilot’s ability to generate accurate, context-aware code and significantly speed up your development workflow.</p>
<hr>
<h2 id="what-this-unit-covers">What This Unit Covers</h2>
<ul>
<li>GitHub Copilot supported languages</li>
<li>Auto-suggestions (ghost text)</li>
<li>Multiple suggestions pane</li>
<li>Support for different coding styles</li>
<li>How GitHub Copilot uses coding comments for better suggestions</li>
</ul>
<hr>
<h2 id="github-copilot-supported-languages">GitHub Copilot Supported Languages</h2>
<p>GitHub Copilot offers strong, production-ready support for many popular programming languages and frameworks, including:</p>
<ul>
<li><strong>Python</strong></li>
<li><strong>JavaScript</strong></li>
<li><strong>TypeScript</strong></li>
<li><strong>Java</strong></li>
<li><strong>C#</strong></li>
<li><strong>C++</strong></li>
<li><strong>Go</strong></li>
<li><strong>Ruby</strong></li>
</ul>
<h2 id="while-these-languages-receive-the-most-advanced-support-copilot-can-also-assist-with-many-other-languages-and-frameworks.">While these languages receive the most advanced support, Copilot can also assist with many other languages and frameworks.</h2>
<h2 id="auto-suggestions">Auto Suggestions</h2>
<p>GitHub Copilot provides <strong>real-time code suggestions</strong> as you type. These suggestions may:</p>
<ul>
<li>Complete the current line</li>
<li>Add multiple lines</li>
<li>Generate an entire block or function</li>
</ul>
<p>You can:</p>
<ul>
<li>Accept the suggestion fully</li>
<li>Accept part of it</li>
<li>Ignore it and continue typing</li>
</ul>
<p>This dramatically reduces time spent on syntax lookup, repetitive patterns, and boilerplate code.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/auto-completion-ghost-text.png" alt="Auto completion ghost text"></p>
<hr>
<h2 id="multiple-suggestions-pane">Multiple Suggestions Pane</h2>
<p>When Copilot shows a gray ghost-text suggestion, you can explore <strong>alternative implementations</strong> using the multiple suggestions pane.</p>
<p>Hover over the suggestion to reveal the <strong>Copilot control panel</strong>, which lets you browse different solutions to the same problem.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/multiple-suggestion-auto-completion-ghost-text.png" alt="Multiple suggestion ghost text"></p>
<h3 id="navigation-shortcuts">Navigation Shortcuts</h3>
<ul>
<li><strong>macOS</strong>:
<ul>
<li>Next: <code>Option (⌥) + ]</code></li>
<li>Previous: <code>Option (⌥) + [</code></li>
</ul>
</li>
<li><strong>Windows / Linux</strong>:
<ul>
<li>Next: <code>Alt + ]</code></li>
<li>Previous: <code>Alt + [</code></li>
</ul>
</li>
</ul>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/suggestions-pane.gif" alt="Suggestions pane screen recording"></p>
<p>This feature allows you to compare approaches instantly without breaking your flow or searching for examples online.</p>
<hr>
<h2 id="adapting-to-different-coding-styles">Adapting to Different Coding Styles</h2>
<p>GitHub Copilot learns and adapts to your project’s conventions, including:</p>
<ul>
<li><strong>Method implementations</strong><br>
Suggests full method bodies based on how your project is structured.</li>
<li><strong>Naming conventions</strong><br>
Matches variable, function, and class naming styles.</li>
<li><strong>Formatting</strong><br>
Follows indentation, spacing, and brace placement.</li>
<li><strong>Comment style</strong><br>
Adapts to inline comments, block comments, or docstrings.</li>
<li><strong>Design patterns</strong><br>
Aligns with patterns already used in the codebase.</li>
</ul>
<p>This ensures suggestions feel native to your project rather than generic.</p>
<hr>
<h2 id="using-coding-comments-for-better-suggestions">Using Coding Comments for Better Suggestions</h2>
<p>Comments are a powerful way to guide GitHub Copilot. By reading comments, Copilot understands <strong>developer intent</strong> and produces more accurate code.</p>
<h3 id="how-copilot-understands-comments">How Copilot Understands Comments</h3>
<ul>
<li><strong>Natural Language Processing (NLP)</strong><br>
Interprets the meaning and intent of comments.</li>
<li><strong>Contextual Analysis</strong><br>
Analyzes comments in relation to surrounding code.</li>
</ul>
<hr>
<h2 id="types-of-comments-used-by-copilot">Types of Comments Used by Copilot</h2>
<p>Copilot leverages many comment types, including:</p>
<ul>
<li><strong>Inline comments</strong> – Explain a single line</li>
<li><strong>Block comments</strong> – Describe a function or class</li>
<li><strong>Docstrings</strong> – Formal documentation (e.g., Python)</li>
<li><strong>TODO comments</strong> – Planned work</li>
<li><strong>API documentation</strong> – Usage and parameters</li>
</ul>
<hr>
<h2 id="comment-driven-code-generation">Comment-Driven Code Generation</h2>
<h3 id="function-implementation-from-comments">Function Implementation from Comments</h3>
<p>When comments describe what a function should do, Copilot can generate the full implementation.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/multiple-line-code-completion-ghost-text.png" alt="Multi-line function completion"></p>
<hr>
<h3 id="whole-function-auto-completion">Whole Function Auto Completion</h3>
<p>Copilot can generate an entire function body based on a short description.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/whole-function-auto-completion-ghost-text.png" alt="Whole function auto completion"></p>
<p><strong>Example:</strong><br>
A comment describing “reverse a string” often results in an efficient implementation using Python slice notation (<code>[::-1]</code>).</p>
<hr>
<h3 id="variable-naming-from-comments">Variable Naming from Comments</h3>
<p>Comments influence variable naming, producing clearer and more descriptive names.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/variable-name-auto-completion-ghost-text.png" alt="Variable name auto completion"></p>
<h2 id="algorithm-selection-via-comments">Algorithm Selection via Comments</h2>
<p>When code comments describe a <strong>specific algorithm or approach</strong>, GitHub Copilot can infer the intended logic and generate code that closely follows that method. By understanding both the natural language description and the surrounding code context, Copilot aligns its suggestions with the algorithm you have in mind.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/algorithm-auto-completion-ghost-text.png" alt="Algorithm auto completion ghost text"></p>
<p>In the example above, the comments clearly outline the steps of the <strong>bubble sort algorithm</strong>. Based on this guidance, GitHub Copilot is able to suggest an implementation that mirrors the described steps—iterating through the list, comparing adjacent elements, and swapping them when necessary—resulting in code that matches both the intent an</p>
<h1 id="github-copilot-chat">GitHub Copilot Chat</h1>
<p>GitHub Copilot Chat is an advanced conversational AI assistant integrated directly into your IDE. It allows developers to interact with their code using natural language, helping with code generation, debugging, explanations, and overall workflow optimization.</p>
<p>To access GitHub Copilot Chat in your IDE (for example, Visual Studio Code), click the <strong>Chat icon</strong> in the left navigation bar.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/chat.png" alt="Copilot Chat interface"></p>
<hr>
<h2 id="what-this-unit-covers-1">What This Unit Covers</h2>
<ul>
<li>Generating code using GitHub Copilot Chat</li>
<li>Debugging code with Copilot Chat</li>
<li>Getting code explanations</li>
<li>Using slash commands</li>
<li>Improving prompts with Copilot agents</li>
</ul>
<hr>
<h2 id="code-generation-with-github-copilot-chat">Code Generation with GitHub Copilot Chat</h2>
<p>Copilot Chat is especially useful when generating <strong>complex code</strong>, such as:</p>
<ul>
<li>Algorithms and data structures</li>
<li>Regular expressions</li>
<li>SQL queries</li>
<li>Boilerplate code for design patterns</li>
</ul>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/chat-code-generation.png" alt="Chat code generation"></p>
<hr>
<h2 id="debugging-assistance">Debugging Assistance</h2>
<p>GitHub Copilot Chat can analyze error messages, identify logical problems, and suggest potential fixes.</p>
<h3 id="debugging-with-inline-chat">Debugging with Inline Chat</h3>
<ol>
<li>Select the code that contains the error</li>
<li>Right-click and choose <strong>Copilot → Inline Chat</strong></li>
<li>Ask Copilot to help debug the issue</li>
</ol>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/selection-code-chat-debugging.png" alt="Selection code chat debugging"></p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/generating-code-chat-debugging.png" alt="Generating code chat debugging"></p>
<p><strong>Example prompt:</strong><br>
I’m getting a NullReferenceException in this method. Can you help me debug it?</p>
<h2 id="code-explanations">Code Explanations</h2>
<p>Copilot Chat can explain complex or unfamiliar code by breaking it down into simple terms and suggesting best practices or optimizations.</p>
<h3 id="example-explaining-asyncawait-code">Example: Explaining async/await Code</h3>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/chat-code-explanations.png" alt="Chat code explanations"></p>
<p><strong>Example prompt:</strong><br>
Can you explain how this async/await code works in JavaScript?</p>
<p>Copilot responds with a structured explanation describing how asynchronous functions work, how <code>await</code> pauses execution until a promise resolves, and how errors are handled.</p>
<hr>
<h2 id="improving-github-copilot-chat-responses">Improving GitHub Copilot Chat Responses</h2>
<p>The quality of Copilot Chat responses improves significantly when you provide proper <strong>scope</strong> and <strong>intent</strong>.</p>
<hr>
<h2 id="scope-referencing">Scope Referencing</h2>
<h3 id="file-references">File References</h3>
<p>You can scope your question to a specific file using <code>#file:</code>.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/chat-scope-file-referencing-pick.png" alt="File reference picker"></p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/chat-scope-file-referencing.png" alt="File referencing"></p>
<h2 id="examplefilecontroller.js-explain-this-file"><strong>Example:</strong><br>
#file:controller.js explain this file</h2>
<h3 id="workspace-references">Workspace References</h3>
<p>Use <code>@workspace</code> to give Copilot access to the entire project.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/chat-scope-workspace-referencing.png" alt="Workspace referencing"></p>
<p><strong>Example:</strong><br>
@workspace where is the calculate function implemented?</p>
<hr>
<h2 id="slash-commands">Slash Commands</h2>
<p>Slash commands allow you to clearly specify intent and receive more accurate responses.</p>
<h3 id="doc-—-add-documentation">/doc — Add Documentation</h3>
<p>Adds comments or docstrings to selected code.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/doc-slash-commands.png" alt="Doc slash command"></p>
<hr>
<h3 id="explain-—-explain-code">/explain — Explain Code</h3>
<p>Explains selected code or files.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/explain-slash-commands.png" alt="Explain slash command"></p>
<hr>
<h3 id="fix-—-fix-issues">/fix — Fix Issues</h3>
<p>Suggests fixes for problems in selected code.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/fix-slash-commands.png" alt="Fix slash command"></p>
<hr>
<h3 id="generate-—-generate-code">/generate — Generate Code</h3>
<p>Creates new code based on your request.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/generate-slash-commands.png" alt="Generate slash command"></p>
<hr>
<h3 id="optimize-—-improve-performance">/optimize — Improve Performance</h3>
<p>Analyzes and improves runtime efficiency.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/optimize-slash-commands.png" alt="Optimize slash command"></p>
<hr>
<h3 id="tests-—-generate-unit-tests">/tests — Generate Unit Tests</h3>
<p>Automatically creates unit tests for selected code.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/tests-slash-commands.png" alt="Tests slash command"></p>
<hr>
<h2 id="copilot-agents">Copilot Agents</h2>
<p>Copilot agents provide specialized context for different workflows.</p>
<h3 id="workspace-agent">@workspace Agent</h3>
<p>Uses the entire project as context.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/workspace-agent-command.png" alt="Workspace agent"></p>
<p>You can also generate a new project:</p>
<p>@workspace /new generate new HTML pages and JavaScript for advanced calculations</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/workspace-new-agent-command.png" alt="Workspace new agent"></p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/new-generated-workspace-project.png" alt="New generated workspace"></p>
<hr>
<h3 id="terminal-agent">@terminal Agent</h3>
<p>Useful for command-line related questions and terminal output analysis.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/terminal-agent-command.png" alt="Terminal agent"></p>
<hr>
<h3 id="vscode-agent">@vscode Agent</h3>
<p>Helps with Visual Studio Code usage and IDE settings.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/vscode-agent-command.png" alt="VS Code agent"></p>
<hr>
<h2 id="sharing-feedback">Sharing Feedback</h2>
<p>You can provide feedback on Copilot Chat suggestions directly from your IDE.</p>
<h3 id="helpful-suggestions">Helpful Suggestions</h3>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/thumbs-up-helpful-buttons.png" alt="Thumbs up"></p>
<hr>
<h3 id="unhelpful-suggestions">Unhelpful Suggestions</h3>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/thumbs-down-unhelpful.png" alt="Thumbs down"></p>
<hr>
<h2 id="key-takeaway-1">Key Takeaway</h2>
<p>GitHub Copilot Chat is a powerful AI assistant that supports <strong>code generation, debugging, explanations, and project-wide reasoning</strong>. By effectively using scope references, slash commands, and agents, developers can significantly improve productivity and code quality.</p>
<h1 id="github-copilot-on-github.com">GitHub Copilot on <a href="http://GitHub.com">GitHub.com</a></h1>
<p>GitHub Copilot extends beyond your local development environment to provide AI-powered assistance directly on <strong><a href="http://GitHub.com">GitHub.com</a></strong>. When working with repositories, issues, pull requests, discussions, and workflows in the GitHub web interface, Copilot helps streamline workflows, improve collaboration, and reduce manual effort.</p>
<hr>
<h2 id="what-this-unit-covers-2">What This Unit Covers</h2>
<ul>
<li>Accessing GitHub Copilot on <a href="http://GitHub.com">GitHub.com</a></li>
<li>GitHub Copilot agent tasks on <a href="http://GitHub.com">GitHub.com</a></li>
<li>Repository exploration and documentation</li>
<li>Pull request assistance</li>
<li>Issue management</li>
<li>Code review and collaboration</li>
<li>Explaining errors in GitHub Actions</li>
</ul>
<hr>
<h2 id="accessing-github-copilot-on-github.com">Accessing GitHub Copilot on <a href="http://GitHub.com">GitHub.com</a></h2>
<p>GitHub Copilot is integrated throughout the GitHub web interface. It appears as a <strong>chat button</strong> or <strong>inline assistance</strong> in multiple areas, including:</p>
<ul>
<li><strong>Repository pages</strong> – Explain code, documentation, and project structure</li>
<li><strong>Issues &amp; Pull Requests</strong> – Generate summaries, suggest solutions, and draft responses</li>
<li><strong>Discussions</strong> – Help formulate technical responses</li>
<li><strong>Code Reviews</strong> – Analyze changes and suggest improvements</li>
</ul>
<p>Copilot works directly in the browser, requiring no local IDE.</p>
<hr>
<h2 id="github-copilot-agent-tasks-on-github.com">GitHub Copilot Agent Tasks on <a href="http://GitHub.com">GitHub.com</a></h2>
<p>On <a href="http://GitHub.com">GitHub.com</a>, Copilot supports <strong>agent-driven tasks</strong> that can run in the background while you focus on other work.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-agent-tasks-overview.png" alt="Copilot agent tasks overview"></p>
<p>These tasks include repository exploration, pull request assistance, issue analysis, and code review support.</p>
<hr>
<h2 id="repository-exploration-and-documentation">Repository Exploration and Documentation</h2>
<p>GitHub Copilot helps you understand and document repositories faster.</p>
<h3 id="capabilities">Capabilities</h3>
<ul>
<li><strong>Code explanation</strong> – Explain functions, files, or complex sections</li>
<li><strong>Project overview</strong> – Generate summaries of repository purpose and architecture</li>
<li><strong>Documentation generation</strong> – Create or improve README files, API docs, and comments</li>
</ul>
<p><strong>Example prompt:</strong><br>
Explain the main functionality of this repository and its key components.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-repository-exploration.png" alt="Repository exploration"></p>
<hr>
<h2 id="pull-request-assistance">Pull Request Assistance</h2>
<p>GitHub Copilot significantly accelerates pull request workflows by automating review and documentation tasks.</p>
<h3 id="key-features">Key Features</h3>
<ul>
<li><strong>PR summaries</strong> – Automatically summarize changes and their impact</li>
<li><strong>Review suggestions</strong> – Highlight potential issues before review</li>
<li><strong>Merge conflict guidance</strong> – Help resolve conflicts between branches</li>
<li><strong>Documentation updates</strong> – Suggest README or changelog updates</li>
</ul>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-pull-request-assistance.png" alt="Pull request assistance"></p>
<p><strong>Example prompt:</strong><br>
Summarize the changes in this pull request and highlight any potential concerns.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-pull-request-assistance-summary.png" alt="Pull request summary"></p>
<blockquote>
<p>⚠️ <strong>Note</strong><br>
Pull request summaries and advanced PR assistance consume <strong>Premium Request Units (PRUs)</strong>.<br>
Typically, PR summaries use <strong>1–2 PRUs</strong>, depending on size and complexity.</p>
</blockquote>
<hr>
<h2 id="issue-management">Issue Management</h2>
<p>Copilot assists with analyzing and managing GitHub issues.</p>
<h3 id="capabilities-1">Capabilities</h3>
<ul>
<li><strong>Issue analysis</strong> – Break down complex issues into actionable tasks</li>
<li><strong>Solution brainstorming</strong> – Suggest implementation approaches</li>
<li><strong>Reproduction steps</strong> – Generate clear steps to reproduce bugs</li>
</ul>
<p><strong>Example prompt:</strong><br>
Analyze this issue and suggest potential solutions with implementation approaches.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-issue-analysis.png" alt="Issue analysis"></p>
<hr>
<h2 id="code-review-and-collaboration">Code Review and Collaboration</h2>
<p>GitHub Copilot enhances collaboration by assisting reviewers with intelligent insights.</p>
<h3 id="review-capabilities">Review Capabilities</h3>
<ul>
<li><strong>Review comments</strong> – Generate actionable feedback</li>
<li><strong>Security analysis</strong> – Identify vulnerabilities and risky patterns</li>
<li><strong>Performance optimization</strong> – Suggest efficiency improvements</li>
</ul>
<p><strong>Example prompt:</strong><br>
Review this code change and provide feedback on security and performance considerations.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-code-review-comments.png" alt="Code review comments"></p>
<blockquote>
<p>⚠️ <strong>Note</strong><br>
Code review features consume <strong>1–3 PRUs</strong>, depending on analysis depth.</p>
</blockquote>
<hr>
<h2 id="github-copilot-explaining-errors-in-github-actions">GitHub Copilot: Explaining Errors in GitHub Actions</h2>
<p>GitHub Copilot can analyze failed <strong>GitHub Actions workflows</strong> and explain what went wrong.</p>
<h3 id="how-copilot-helps">How Copilot Helps</h3>
<ul>
<li><strong>Error analysis</strong> – Identifies root causes from logs</li>
<li><strong>Solution suggestions</strong> – Recommends fixes</li>
<li><strong>Best practices</strong> – Improves workflow reliability</li>
<li><strong>Context awareness</strong> – Understands step dependencies</li>
</ul>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-actions-error-explanation.png" alt="GitHub Actions error explanation"></p>
<p>This feature helps reduce time spent diagnosing CI/CD failures and improves pipeline stability.</p>
<hr>
<h2 id="key-takeaway-2">Key Takeaway</h2>
<p>GitHub Copilot on <a href="http://GitHub.com">GitHub.com</a> brings AI-powered assistance directly into <strong>repositories, pull requests, issues, code reviews, and workflows</strong>. By leveraging agent tasks, PR summaries, issue analysis, and workflow error explanations, teams can collaborate more effectively, reduce manual overhead, and maintain development velocity.</p>
<h1 id="github-copilot-for-the-command-line">GitHub Copilot for the Command Line</h1>
<p>GitHub Copilot is not limited to IDE-based code assistance—it also enhances productivity directly from the <strong>command line</strong>. By integrating with the <strong>GitHub CLI</strong>, Copilot can explain unfamiliar commands, suggest commands based on intent, and even execute them on your behalf. This makes it useful for both beginners and experienced terminal users by simplifying complex workflows and reducing manual effort.</p>
<hr>
<h2 id="what-this-unit-covers-3">What This Unit Covers</h2>
<ul>
<li>Common GitHub Copilot CLI commands</li>
<li>Executing and revising suggested commands</li>
<li>Configuration options for Copilot CLI</li>
<li>Feedback and organizational controls</li>
<li>Data handling and privacy settings</li>
</ul>
<hr>
<h1 id="github-copilot-cli-—-installation--usage-guide">GitHub Copilot CLI — Installation &amp; Usage Guide</h1>
<h2 id="overview">Overview</h2>
<p>GitHub Copilot CLI allows you to interact with Copilot directly from your terminal. You can:</p>
<ul>
<li>Explain shell commands</li>
<li>Suggest commands for tasks</li>
<li>Revise previous suggestions</li>
<li>Manage configuration and AI models</li>
<li>Work interactively with files and directories</li>
</ul>
<hr>
<h2 id="installation">Installation</h2>
<h3 id="macos--linux-homebrew">macOS &amp; Linux (Homebrew)</h3>
<pre class=" language-bash"><code class="prism  language-bash">brew <span class="token function">install</span> copilot-cli
</code></pre>
<p>Official Install Script (All Platforms)</p>
<pre><code>curl -fsSL https://gh.io/copilot-install | bash
</code></pre>
<p>Launch Copilot CLI in  <strong>interactive mode</strong>:</p>
<pre><code>copilot
</code></pre>
<p>It displays see a welcome banner and a prompt:<br>
<img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-cli-banner.png" alt="Copilot explain in CLI"><br>
On first launch, Copilot asks whether you trust the files in the current folder. Copilot may read, modify, or execute files in this directory during the session, so only proceed in locations you trust.<br>
<img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-cli-trust-files.png" alt="Copilot explain in CLI"><br>
You can use the  <code>@</code>  to select a specific file you want to work with as context.<br>
<img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-cli-select-file.png" alt="Copilot explain in CLI"></p>
<h2 id="launch-copilot-cli">Launch Copilot CLI</h2>
<h3 id="interactive-mode">Interactive Mode</h3>
<p><code>copilot</code></p>
<p>You will see a welcome banner and prompt.</p>
<h3 id="directory-trust-prompt">Directory Trust Prompt</h3>
<p>On first launch, Copilot asks if you trust the current directory.</p>
<blockquote>
<p>Copilot may read, modify, or execute files in this directory.<br>
Only allow access in trusted locations.</p>
</blockquote>
<hr>
<h2 id="using-file-context">Using File Context</h2>
<p>You can use <code>@</code> to reference a specific file in your current directory:</p>
<p><code>@README.md</code></p>
<p>This allows Copilot to use that file as context for your questions or commands.</p>
<hr>
<h2 id="one-shot-mode-non-interactive">One-Shot Mode (Non-Interactive)</h2>
<p>Run a single prompt without entering full interactive mode:</p>
<p><code>copilot -i "explain brew install git"</code></p>
<p><code>copilot -i "suggest find large files and delete them"</code></p>
<h2 id="slash-commands-1">Slash Commands</h2>
<p>Slash commands control the session and cannot be replaced by natural language.</p>
<p>Command</p>
<p>Description</p>
<p><code>/help</code></p>
<p>Show all available commands</p>
<p><code>/explain &lt;command&gt;</code></p>
<p>Explain a shell command</p>
<p><code>/suggest &lt;task&gt;</code></p>
<p>Suggest a command for a task</p>
<p><code>/revise</code></p>
<p>Revise the last suggestion</p>
<p><code>/feedback</code></p>
<p>Send feedback</p>
<p><code>/exit</code></p>
<p>Exit interactive mode</p>
<p><code>/model &lt;model&gt;</code></p>
<p>Select AI model</p>
<p><code>/theme [auto|dark|light]</code></p>
<p>Change terminal theme</p>
<p><code>/skills</code></p>
<p>Manage skills</p>
<p><code>/mcp</code></p>
<p>Manage MCP server</p>
<p><code>/list-dirs</code></p>
<p>Show allowed directories</p>
<p><code>/reset-allowed-tools</code></p>
<p>Reset tool permissions</p>
<hr>
<h2 id="example-workflows">Example Workflows</h2>
<h3 id="explain-a-command">1. Explain a Command</h3>
<p><code>&gt; Explain what `git reset --hard HEAD` does</code></p>
<p>Copilot will return a full explanation of what the command does and its risks.<br>
<img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-explain-in-cli.png" alt="Copilot explain in CLI"></p>
<hr>
<h3 id="suggest-a-command">2. Suggest a Command</h3>
<p><code>&gt; Find and delete all .log files in my home folder</code></p>
<p>Copilot will suggest a shell command and ask for confirmation before execution.</p>
<p><img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-cli-suggest-command.png" alt="Copilot suggest in CLI"></p>
<hr>
<h3 id="revise-a-suggestion">3. Revise a Suggestion</h3>
<p>After Copilot suggests a command:</p>
<p><code>&gt; Include only files modified in the last 7 days</code></p>
<p>Copilot updates the command accordingly.<br>
<img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-cli-revise-suggestion.png" alt="Copilot suggest in CLI"></p>
<hr>
<h3 id="provide-feedback">4. Provide Feedback</h3>
<p><code>&gt; /feedback</code></p>
<p>You will be prompted to choose feedback type and redirected to GitHub’s feedback form.<br>
<img src="https://learn.microsoft.com/en-us/training/github/github-copilot-across-environments/media/copilot-cli-provide-feedback.png" alt="Copilot suggest in CLI"></p>
<hr>
<h3 id="exit-interactive-mode">5. Exit Interactive Mode</h3>
<p><code>&gt; /exit</code></p>
<hr>
<h2 id="configuration-options">Configuration Options</h2>
<h3 id="interactive-configuration">Interactive Configuration</h3>
<p>Use slash commands inside Copilot:</p>
<pre><code>/model
/theme
/skills
/mcp
/list-dirs
/reset-allowed-tools
</code></pre>
<hr>
<h3 id="global-configuration-non-interactive">Global Configuration (Non-Interactive)</h3>
<p><code>copilot configure</code></p>
<p>This allows you to:</p>
<ul>
<li>
<p>Set default AI model</p>
</li>
<li>
<p>Change theme</p>
</li>
<li>
<p>Enable or disable analytics</p>
</li>
<li>
<p>Manage organizational access</p>
</li>
</ul>
<hr>
<h2 id="best-practices">Best Practices</h2>
<ul>
<li>
<p>Use <strong>interactive mode</strong> for exploration</p>
</li>
<li>
<p>Use <strong>one-shot mode</strong> for quick tasks</p>
</li>
<li>
<p>Always <strong>review commands before running</strong></p>
</li>
<li>
<p>Combine with GitHub CLI (<code>gh</code>) for repo and issue management</p>
</li>
<li>
<p>Use <code>/skills</code> to enhance capabilities</p>
</li>
<li>
<p>Only allow trusted directories for file access</p>
</li>
</ul>
<hr>
<h2 id="security-notes">Security Notes</h2>
<p>Copilot CLI can:</p>
<ul>
<li>
<p>Read files</p>
</li>
<li>
<p>Modify files</p>
</li>
<li>
<p>Execute commands</p>
</li>
</ul>
<p>Always verify:</p>
<ul>
<li>
<p>Directory trust</p>
</li>
<li>
<p>Suggested commands</p>
</li>
<li>
<p>File context usage</p>
</li>
</ul>
<hr>
<h2 id="recommended-workflow">Recommended Workflow</h2>
<pre><code>1. Start copilot
2. Trust directory
3. Use /suggest or natural language
4. Revise if needed
5. Review command
6. Execute
7. Exit session
</code></pre>

