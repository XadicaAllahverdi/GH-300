<h2 id="introduction-github-copilot-features-—-summary">Introduction: GitHub Copilot Features — Summary</h2>
<p><strong>GitHub Copilot</strong> is an AI-powered coding partner that helps developers write code faster and more efficiently by providing intelligent autocomplete suggestions and interactive, natural-language assistance directly in the editor.</p>
<p>Copilot analyzes the current file along with related project files and comments to generate context-aware suggestions, ranging from single lines of code to complete functions.</p>
<p><strong>GitHub Codespaces</strong> provides a cloud-based development environment integrated with Visual Studio Code. It enables developers to work with preconfigured repositories, including installed dependencies, libraries, extensions, and editor settings—allowing rapid onboarding and consistent development environments.</p>
<h3 id="scenario-working-with-an-existing-project">Scenario: Working with an Existing Project</h3>
<p>In real-world development, productivity is critical when working on both new and existing projects. This module focuses on using <strong>advanced GitHub Copilot features</strong> to improve workflows related to:</p>
<ul>
<li>Writing and modifying code</li>
<li>Understanding unfamiliar codebases</li>
<li>Creating documentation</li>
<li>Writing and improving unit tests</li>
</ul>
<h3 id="learning-outcomes">Learning Outcomes</h3>
<p>By the end of this module, you will be able to:</p>
<ul>
<li>Work in a <strong>preconfigured GitHub repository</strong> using Codespaces and the Copilot extension</li>
<li>Use <strong>interactive Copilot features</strong> to generate meaningful suggestions for existing projects</li>
<li>Apply advanced Copilot capabilities to <strong>explore codebases</strong>, <strong>add HTTP API endpoints</strong>, <strong>write tests</strong>, and <strong>document code</strong></li>
</ul>
<h3 id="main-objective">Main Objective</h3>
<p>The main goal is to enable effective use of <strong>interactive prompts and advanced GitHub Copilot features</strong> to enhance and extend a software project.</p>
<h3 id="prerequisites">Prerequisites</h3>
<ul>
<li>Basic understanding of <strong>Python</strong> and text editors</li>
<li>Familiarity with <strong>Git and GitHub fundamentals</strong> (<code>git add</code>, <code>git push</code>)</li>
<li>A <strong>GitHub account with GitHub Copilot enabled</strong><br>
<em>(Copilot Free with usage limits is sufficient for learning)</em></li>
</ul>
<h2 id="advanced-github-copilot-features-—-summary">Advanced GitHub Copilot Features — Summary</h2>
<p>When working on real-world projects, developers often need to understand existing codebases, review documentation, fix bugs, and write tests. These tasks can be time-consuming, but <strong>GitHub Copilot’s advanced features</strong> help streamline and accelerate them.</p>
<h3 id="the-basics-ghost-text">The Basics: Ghost Text</h3>
<ul>
<li>When Copilot is enabled, it shows <strong>ghost text</strong> (inline code suggestions).</li>
<li>You can:
<ul>
<li><strong>Accept</strong> suggestions by pressing <strong>Tab</strong></li>
<li><strong>Ignore</strong> them and keep typing</li>
</ul>
</li>
<li>By default, Copilot uses open files as context.</li>
<li>You can guide suggestions using:
<ul>
<li>Comments in code</li>
<li>The chat window</li>
<li>Inline chat</li>
</ul>
</li>
</ul>
<h3 id="chatting-with-github-copilot">Chatting with GitHub Copilot</h3>
<ul>
<li>Accessible via the <strong>chat icon</strong> in the Visual Studio Code sidebar</li>
<li>Opens a dedicated pane for interactive conversations</li>
<li>Useful for:
<ul>
<li>Asking questions about current code</li>
<li>Understanding libraries or frameworks</li>
<li>Getting help with software-related problems</li>
</ul>
</li>
</ul>
<h3 id="using-inline-chat">Using Inline Chat</h3>
<ul>
<li>Open with:
<ul>
<li><strong>Ctrl + I</strong> (Windows)</li>
<li><strong>Cmd + I</strong> (Mac)</li>
</ul>
</li>
<li>Allows interaction <strong>directly within the code editor</strong></li>
<li>Keeps context close to the code without switching panes</li>
<li>Ideal for refactoring, explanations, and quick fixes</li>
</ul>
<h3 id="slash-commands">Slash Commands</h3>
<ul>
<li>Available in both chat and inline chat</li>
<li>Triggered by typing <code>/</code></li>
<li>Provide <strong>intent-based shortcuts</strong> for common tasks</li>
<li>Examples:
<ul>
<li><code>/tests</code> – generate or improve unit tests</li>
<li><code>/docs</code> – write or enhance documentation</li>
</ul>
</li>
<li>Slash commands help produce better results with shorter prompts</li>
</ul>
<h3 id="agents">Agents</h3>
<ul>
<li>Agents give Copilot <strong>specialized context</strong></li>
<li>Common agents include:
<ul>
<li><code>@terminal</code> – interact with terminal commands</li>
<li><code>@workspace</code> – understands the entire project workspace</li>
</ul>
</li>
<li>Example usage:<pre class=" language-text"><code class="prism  language-text">@workspace how can I package this project?

</code></pre>
</li>
</ul>
<h2 id="github-codespaces--copilot-free-usage-—-notes">GitHub Codespaces &amp; Copilot Free Usage — Notes</h2>
<h3 id="github-codespaces-free-tier">GitHub Codespaces (Free Tier)</h3>
<ul>
<li>All GitHub accounts include <strong>up to 60 free hours per month</strong></li>
<li>Applies to <strong>two-core instances</strong></li>
<li>Includes limited storage and compute usage</li>
<li>Suitable for learning, small projects, and experimentation</li>
<li>For details, see <strong>GitHub Codespaces monthly included storage and core hours</strong></li>
</ul>
<h3 id="github-copilot-free-tier">GitHub Copilot (Free Tier)</h3>
<ul>
<li>Includes:
<ul>
<li><strong>2,000 code autocompletions per month</strong></li>
<li><strong>50 chat messages per month</strong></li>
</ul>
</li>
<li>How to get started:
<ol>
<li>Open <strong>Visual Studio Code</strong></li>
<li>Click the <strong>GitHub Copilot icon</strong></li>
<li>Select <strong>“Sign in to Use GitHub Copilot for Free”</strong></li>
</ol>
</li>
</ul>
<h3 id="free-copilot-pro-eligibility">Free Copilot Pro Eligibility</h3>
<ul>
<li><strong>Educators</strong></li>
<li><strong>Students</strong></li>
<li><strong>Selected open-source maintainers</strong></li>
</ul>
<p>Eligible users can receive <strong>Copilot Pro for free</strong>.<br>
Learn more: <a href="https://aka.ms/Copilot4Students">https://aka.ms/Copilot4Students</a></p>
<h3 id="key-takeaway">Key Takeaway</h3>
<p>GitHub provides generous free access to <strong>Codespaces</strong> and <strong>Copilot</strong>, making it easy to explore cloud-based development and AI-assisted coding with minimal setup.</p>
<h2 id="applied-github-copilot-techniques-—-summary">Applied GitHub Copilot Techniques — Summary</h2>
<p>This unit focuses on using <strong>GitHub Copilot</strong> effectively in <strong>existing projects</strong> and for <strong>more complex development tasks</strong> beyond basic code generation.</p>
<h3 id="advanced-tasks-with-copilot">Advanced Tasks with Copilot</h3>
<p>When working on established codebases, developers often need to:</p>
<ul>
<li>Fix bugs</li>
<li>Implement new features</li>
<li>Write documentation</li>
<li>Create unit tests</li>
<li>Work with terminal commands</li>
</ul>
<p>GitHub Copilot supports all these workflows through advanced, context-aware features.</p>
<h3 id="implicit-prompts">Implicit Prompts</h3>
<ul>
<li>Copilot can use <strong>precrafted prompts implicitly</strong> through selections and slash commands.</li>
<li>You don’t always need to write detailed prompts.</li>
<li>Example workflow:
<ol>
<li>Select buggy code</li>
<li>Open inline chat (<code>Ctrl + I</code> / <code>Cmd + I</code>)</li>
<li>Use <code>/fix</code> to receive a suggested correction</li>
</ol>
</li>
</ul>
<p>This approach is fast and effective for common coding issues.</p>
<h3 id="useful-slash-commands">Useful Slash Commands</h3>
<p>Slash commands can be used in both <strong>chat</strong> and <strong>inline chat</strong> to guide Copilot’s intent:</p>
<ul>
<li><code>/fix</code> – Fix bugs in selected code</li>
<li><code>/doc</code> – Add documentation or comments</li>
<li><code>/explain</code> – Explain how the code works</li>
<li><code>/generate</code> – Generate new code</li>
<li><code>/optimize</code> – Improve performance and runtime</li>
<li><code>/tests</code> – Generate unit tests</li>
<li><code>/help</code> – Learn how to use Copilot chat</li>
</ul>
<p>Using slash commands improves response quality without requiring long prompts.</p>
<h3 id="combining-inline-chat-and-slash-commands">Combining Inline Chat and Slash Commands</h3>
<ul>
<li>Inline chat keeps suggestions close to the code</li>
<li>Slash commands add clear intent</li>
<li>Together, they offer a flexible and efficient workflow</li>
</ul>
<h3 id="selective-context-with-agents">Selective Context with Agents</h3>
<p>Copilot can tailor suggestions using <strong>specific context scopes</strong>:</p>
<ul>
<li><code>@workspace</code> – Uses the entire project
<ul>
<li>Example: Generate a Dockerfile for the project</li>
</ul>
</li>
<li><code>@terminal</code> – Uses terminal output
<ul>
<li>Example: Debug an error message</li>
</ul>
</li>
<li><code>@file</code> – Focuses on a specific file
<ul>
<li>Example: Refactor a function in <code>main.py</code></li>
</ul>
</li>
<li><code>@directory</code> – Considers a specific directory
<ul>
<li>Example: Optimize scripts in a utilities folder</li>
</ul>
</li>
</ul>
<p>These agents help Copilot provide accurate, project-aware responses without manually opening multiple files.</p>
<h3 id="key-note">Key Note</h3>
<p>Even without explicit agents, GitHub Copilot automatically uses <strong>open files</strong> in your editor as context.</p>
<h3 id="key-takeaway-1">Key Takeaway</h3>
<p>By combining <strong>implicit prompts</strong>, <strong>slash commands</strong>, <strong>inline chat</strong>, and <strong>context-aware agents</strong>, GitHub Copilot becomes a powerful assistant for maintaining, improving, and extending existing software projects.</p>

