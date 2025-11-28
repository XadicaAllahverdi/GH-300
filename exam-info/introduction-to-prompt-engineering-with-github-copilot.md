---


---

<h1 id="🚀-github-copilot--prompt-engineering-—-summary">🚀 GitHub Copilot &amp; Prompt Engineering — Summary</h1>
<p>GitHub Copilot, powered by OpenAI, accelerates software development by assisting with everything from initial code creation to production-ready implementations. It understands project context through training on natural language and billions of lines of publicly available code, enabling context-aware suggestions and automating repetitive tasks.</p>
<p>To get the most out of Copilot, prompt engineering is essential. The clarity and strategy of your prompts determine how accurate, fast, and effective Copilot’s responses will be.</p>
<hr>
<h2 id="🧠-what-you’ll-learn-in-this-module">🧠 What You’ll Learn in This Module</h2>
<h3 id="prompt-engineering-fundamentals">1. Prompt Engineering Fundamentals</h3>
<ul>
<li>Core principles and best practices</li>
<li>How Copilot interprets prompts</li>
<li>How prompts influence the quality of code suggestions</li>
</ul>
<h3 id="advanced-prompting-techniques">2. Advanced Prompting Techniques</h3>
<ul>
<li>Role prompting</li>
<li>Managing chat history for better accuracy</li>
<li>Reducing iterations with better prompt structure</li>
</ul>
<h3 id="how-copilot-processes-prompts">3. How Copilot Processes Prompts</h3>
<ul>
<li>Internal flow of prompt → model → response</li>
<li>How Copilot prioritizes and uses context</li>
<li>Efficient generation of suggestions</li>
</ul>
<h3 id="data-flow-in-copilot">4. Data Flow in Copilot</h3>
<ul>
<li>Data flow for code suggestions and chat</li>
<li>Secure handling and transmission of prompt data</li>
<li>Built-in content filtering and safeguards</li>
</ul>
<h3 id="the-role-of-llms">5. The Role of LLMs</h3>
<ul>
<li>How Large Language Models power Copilot</li>
<li>Why LLMs enable context understanding and reasoning</li>
<li>Their importance in code generation</li>
</ul>
<h3 id="crafting-effective-prompts">6. Crafting Effective Prompts</h3>
<ul>
<li>Structuring prompts for precision</li>
<li>Optimizing relevance and reducing revision cycles</li>
<li>Aligning Copilot with coding style and architecture</li>
</ul>
<h3 id="streamlining-development-workflows">7. Streamlining Development Workflows</h3>
<ul>
<li>How better prompts improve velocity</li>
<li>Reducing repetitive tasks</li>
<li>Getting consistent, production-ready outputs faster</li>
</ul>
<hr>
<h1 id="prompt-engineering-foundations-and-best-practices">Prompt Engineering Foundations and Best Practices</h1>
<h2 id="what-is-prompt-engineering">What is prompt engineering?</h2>
<p>Prompt engineering is the process of crafting clear instructions to guide AI systems like GitHub Copilot to generate context-appropriate, syntactically correct, and functional code.</p>
<hr>
<h2 id="principles-of-prompt-engineering-—-the-4-ss">Principles of Prompt Engineering — The 4 Ss</h2>
<h3 id="single"><strong>Single</strong></h3>
<p>Focus your prompt on one well-defined task.</p>
<h3 id="specific"><strong>Specific</strong></h3>
<p>Make your instructions explicit and detailed.</p>
<h3 id="short"><strong>Short</strong></h3>
<p>Keep prompts concise while retaining clarity.</p>
<h3 id="surround"><strong>Surround</strong></h3>
<p>Use descriptive filenames, comments, and open related files to give Copilot more context.</p>
<hr>
<h2 id="best-practices-in-prompt-engineering">Best Practices in Prompt Engineering</h2>
<h3 id="provide-enough-clarity"><strong>Provide enough clarity</strong></h3>
<p>Write clear, explicit prompts.<br>
Example: <em>“Write a Python function to filter and return even numbers from a list.”</em></p>
<h3 id="provide-enough-context"><strong>Provide enough context</strong></h3>
<p>Use comments, filenames, and open tabs to help Copilot understand your project.</p>
<h3 id="provide-examples"><strong>Provide examples</strong></h3>
<p>Add one or more examples to show patterns or expected output.<br>
Useful for boilerplate, tests, and repetitive implementations.</p>
<h3 id="assert-and-iterate"><strong>Assert and iterate</strong></h3>
<p>If the first output is not correct:</p>
<ul>
<li>Delete the suggestion</li>
<li>Add more details to your prompt</li>
<li>Try again<br>
Iteration improves output quality.</li>
</ul>
<hr>
<h2 id="how-copilot-learns-from-your-prompts">How Copilot Learns from Your Prompts</h2>
<h3 id="zero-shot-learning"><strong>Zero-shot learning</strong></h3>
<p>Copilot generates code only from your description, with no examples.</p>
<h3 id="one-shot-learning"><strong>One-shot learning</strong></h3>
<p>You provide one example, and Copilot follows its pattern.</p>
<h3 id="few-shot-learning"><strong>Few-shot learning</strong></h3>
<p>You provide multiple examples to guide consistent, complex output.</p>
<hr>
<h2 id="chain-prompting--chat-history-management">Chain Prompting &amp; Chat History Management</h2>
<ul>
<li>Long conversations increase cost (2–3 PRUs per turn).</li>
<li>Summarize context when the chat gets long.</li>
<li>Reset the chat for new features.</li>
<li>Refer briefly to previous outputs instead of pasting full code.</li>
</ul>
<hr>
<h2 id="role-prompting">Role Prompting</h2>
<h3 id="security-expert"><strong>Security Expert</strong></h3>
<p>“Act as a cybersecurity expert and create a password validator following OWASP.”</p>
<h3 id="performance-expert"><strong>Performance Expert</strong></h3>
<p>“Act as a performance optimization expert and refactor this for large datasets.”</p>
<h3 id="testing-specialist"><strong>Testing Specialist</strong></h3>
<p>“Act as a testing specialist and create full unit tests with edge cases.”</p>
<p>Role prompting gives more targeted, production-ready results.</p>
<hr>
<h1 id="github-copilot-user-prompt-process-flow">GitHub Copilot User Prompt Process Flow</h1>
<p>This unit explains how GitHub Copilot transforms your prompts into accurate, useful code suggestions.<br>
The process follows both <strong>inbound</strong> and <strong>outbound</strong> flows.</p>
<hr>
<h1 id="🟦-inbound-flow">🟦 Inbound Flow</h1>
<p><img src="https://learn.microsoft.com/en-us/training/github/introduction-prompt-engineering-with-github-copilot/media/3-github-copilot-inbound-flow.png" alt="Inbound Flow Diagram"></p>
<h2 id="secure-prompt-transmission--context-gathering">1. Secure Prompt Transmission &amp; Context Gathering</h2>
<ul>
<li>User prompt is securely transmitted over <strong>HTTPS</strong>.</li>
<li>Copilot receives:
<ul>
<li>Natural language comments</li>
<li>Chat prompts</li>
</ul>
</li>
<li>Simultaneously gathers context:
<ul>
<li>Code before &amp; after cursor (FIM: Fill-in-the-Middle)</li>
<li>Filename &amp; file type</li>
<li>Open tabs and nearby files</li>
<li>Project structure &amp; file paths</li>
<li>Programming languages &amp; frameworks used</li>
</ul>
</li>
<li>FIM preprocessing expands contextual understanding.</li>
</ul>
<p>This step converts your natural instruction into a concrete code-generation task.</p>
<hr>
<h2 id="proxy-filter">2. Proxy Filter</h2>
<ul>
<li>The prompt flows through a <strong>proxy server</strong> in a GitHub-owned Azure tenant.</li>
<li>Filters out:
<ul>
<li>Prompt injection attempts</li>
<li>Unauthorized system queries</li>
<li>Attempts to extract model internals</li>
</ul>
</li>
</ul>
<hr>
<h2 id="toxicity-filtering">3. Toxicity Filtering</h2>
<p>Copilot removes or blocks:</p>
<ul>
<li>Hate speech &amp; inappropriate language</li>
<li>Harmful or offensive content</li>
<li>Personal data (names, addresses, IDs)</li>
</ul>
<p>This ensures safe and responsible code generation.</p>
<hr>
<h2 id="code-generation-with-llm">4. Code Generation with LLM</h2>
<ul>
<li>The cleaned, structured prompt is passed to the <strong>Large Language Model</strong>.</li>
<li>LLM generates:
<ul>
<li>Code suggestions</li>
<li>Patterns aligned with project &amp; file context</li>
<li>Framework-specific structures</li>
</ul>
</li>
</ul>
<hr>
<h1 id="🟩-outbound-flow">🟩 Outbound Flow</h1>
<p><img src="https://learn.microsoft.com/en-us/training/github/introduction-prompt-engineering-with-github-copilot/media/3-github-copilot-outbound-flow.png" alt="Outbound Flow Diagram"></p>
<h2 id="post-processing--response-validation">5. Post-Processing &amp; Response Validation</h2>
<p><strong>Responses are checked for:</strong></p>
<ul>
<li><strong>Toxicity:</strong> removing harmful output</li>
<li><strong>Code quality:</strong> detection of:
<ul>
<li>Bugs</li>
<li>Security vulnerabilities (XSS, SQL injection)</li>
<li>Unsafe patterns</li>
</ul>
</li>
<li><strong>Public-code filtering (optional):</strong>
<ul>
<li>Blocks &gt;150-character suggestions similar to public GitHub code</li>
</ul>
</li>
</ul>
<p>Invalid or risky outputs are truncated or removed entirely.</p>
<hr>
<h2 id="suggestion-delivery--feedback-loop">6. Suggestion Delivery &amp; Feedback Loop</h2>
<p>Once validated:</p>
<ul>
<li>The suggestion is returned to the user.</li>
<li>Copilot analyzes user actions:
<ul>
<li>Acceptance → strengthens similar patterns</li>
<li>Modification → improves understanding</li>
<li>Rejection → reduces similar outputs</li>
</ul>
</li>
</ul>
<p>This creates a continuous improvement loop.</p>
<hr>
<h2 id="repeat-for-subsequent-prompts">7. Repeat for Subsequent Prompts</h2>
<p>For every new prompt:</p>
<ul>
<li>Copilot gathers updated context</li>
<li>Uses your interactions as learning signals</li>
<li>Generates progressively better and more aligned code</li>
</ul>
<p>Over time, Copilot becomes more accurate and intuitive for your specific workflows.</p>
<hr>
<h1 id="github-copilot-data-handling">GitHub Copilot Data Handling</h1>
<h2 id="🔐-data-handling-for-copilot-code-suggestions">🔐 Data Handling for Copilot Code Suggestions</h2>
<ul>
<li>Copilot <strong>does not retain prompts</strong> (code or context) used for generating code suggestions.</li>
<li>After returning a suggestion, all prompt data is <strong>discarded</strong>.</li>
<li><strong>Copilot Individual</strong> subscribers can <strong>opt out</strong> of sharing prompts for model fine-tuning.</li>
<li>If not opted out, prompts may be used to improve foundational models.</li>
</ul>
<hr>
<h1 id="💬-data-handling-for-github-copilot-chat">💬 Data Handling for GitHub Copilot Chat</h1>
<h2 id="formatting">1. Formatting</h2>
<ul>
<li>Copilot formats responses for readability.</li>
<li>Code blocks are highlighted.</li>
<li>Some responses include direct insertion options.</li>
</ul>
<h2 id="user-engagement">2. User Engagement</h2>
<ul>
<li>Chat maintains <strong>conversation history</strong> so Copilot can understand follow-ups.</li>
<li>Users can ask clarifying questions, refine results, or provide more details.</li>
</ul>
<h2 id="data-retention">3. Data Retention</h2>
<ul>
<li>Copilot Chat <strong>outside the editor</strong> retains:
<ul>
<li>Prompts</li>
<li>Suggestions</li>
<li>Supporting context<br>
for <strong>28 days</strong>.</li>
</ul>
</li>
<li>Retention for in-editor Copilot Chat may vary.</li>
<li>Applies similarly to:
<ul>
<li>CLI</li>
<li>Mobile</li>
<li><a href="http://GitHub.com">GitHub.com</a> Copilot Chat</li>
</ul>
</li>
</ul>
<hr>
<h1 id="🧠-prompt-types-supported-by-copilot-chat">🧠 Prompt Types Supported by Copilot Chat</h1>
<h3 id="direct-questions"><strong>Direct Questions</strong></h3>
<p>Examples:</p>
<ul>
<li>“How do I implement quicksort in Python?”</li>
<li>“Why isn’t my React component rendering?”</li>
</ul>
<h3 id="code-related-requests"><strong>Code-Related Requests</strong></h3>
<ul>
<li>Code generation</li>
<li>Bug fixing</li>
<li>Explanation / refactoring<br>
Example: “Write a factorial function.”</li>
</ul>
<h3 id="open-ended-queries"><strong>Open-Ended Queries</strong></h3>
<ul>
<li>“Best practices for clean code?”</li>
<li>“How to improve Python performance?”</li>
</ul>
<h3 id="contextual-prompts"><strong>Contextual Prompts</strong></h3>
<ul>
<li>“Here’s my code—suggest improvements.”</li>
<li>“Help me design authentication flow.”</li>
</ul>
<p>Copilot processes diverse inputs, making it a highly flexible coding assistant.</p>
<hr>
<h1 id="📏-limited-context-windows">📏 Limited Context Windows</h1>
<p><img src="https://learn.microsoft.com/en-us/training/github/introduction-prompt-engineering-with-github-copilot/media/4-copilot-data-limited-context-window.png" alt="Context Window Diagram"></p>
<ul>
<li>Copilot can process <strong>200–500 lines</strong> of code or <strong>a few thousand tokens</strong> in standard mode.</li>
<li><strong>Copilot Chat</strong> operates with a <strong>4k token context window</strong>, allowing broader understanding.</li>
<li>You should:
<ul>
<li>Break complex tasks into smaller prompts</li>
<li>Provide relevant snippets</li>
<li>Avoid overwhelming the context window</li>
</ul>
</li>
</ul>
<p>These steps help Copilot respond more accurately and efficiently.</p>
<hr>

