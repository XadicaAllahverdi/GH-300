---


---

<h1 id="responsible-ai">Responsible AI</h1>
<p>Responsible AI - Responsible AI is an approach to developing, assessing, and deploying artificial intelligent systems in a safe, trustworthy, and ethical way.</p>
<h2 id="principles-of-responsible-ai">6 Principles of responsible AI</h2>
<ul>
<li>Fairness: AI systems should treat all people fairly.</li>
<li>Reliability and safety: AI systems should perform reliably and safely.</li>
<li>Privacy and security: AI systems should be secure and respect privacy.</li>
<li>Inclusiveness: AI systems should empower everyone and engage people.</li>
<li>Transparency: AI systems should be understandable.</li>
<li>Accountability: People should be accountable for AI systems.</li>
</ul>
<h2 id="fairness">Fairness</h2>
<p>Detect bias and mitigate unfair impacts such as:</p>
<ul>
<li>Reviewing training data.</li>
<li>Testing models with balanced demographic samples.</li>
<li>Using adversarial debiasing.</li>
<li>Monitoring model performance across user segments.</li>
<li>Implementing controls to override unfair model scores.</li>
</ul>
<h2 id="privacy-and-security">Privacy and security</h2>
<h3 id="user-consent">User Consent:</h3>
<ul>
<li>Always ask for permission before collecting data. Clearly tell users what data is used and why. Avoid hidden data collection.</li>
</ul>
<h3 id="minimal-data-use">Minimal Data Use:</h3>
<ul>
<li>Collect only the data necessary for the AI to function. Remove or avoid sensitive information and regularly review data inputs.</li>
</ul>
<h3 id="data-protection">Data Protection:</h3>
<ul>
<li>Anonymize data (pseudonymization, aggregation).</li>
<li>Encrypt everything — both in transit and at rest.</li>
<li>Use secure key management (HSMs, Azure Key Vault, envelope encryption).</li>
</ul>
<h3 id="access-control--security">Access Control &amp; Security:</h3>
<ul>
<li>Limit employee access to sensitive models/data.</li>
<li>Classify data by sensitivity, rotate keys often, back them up securely, and run regular security audits.</li>
</ul>
<h2 id="inclusiveness">Inclusiveness</h2>
<ul>
<li>AI must work fairly for all people, across different backgrounds, abilities, and regions.</li>
<li>Systems must be accessible (screen readers, captions, voice control) and easy for everyone to use.</li>
<li>AI should be globally inclusive, supporting different languages, cultures, and places with low connectivity.</li>
<li>Diverse communities should be involved in the design process to avoid bias.</li>
<li>AI should let everyone benefit equally, without excluding any group.</li>
</ul>
<h3 id="examples">Examples:</h3>
<ul>
<li>Facial recognition is accurate for all skin tones, ages, genders.</li>
<li>Interfaces usable by people with disabilities.</li>
<li>Translation tools supporting regional dialects.</li>
<li>Working offline and with limited connectivity and computing resources.</li>
</ul>
<h2 id="transparency">Transparency</h2>
<ul>
<li>AI systems must be understandable and interpretable.</li>
<li>Creators should clearly explain how the system works, justify design choices, and be honest about strengths and limitations.</li>
<li>Systems must support auditability with proper logging, reporting, and auditing tools.</li>
<li>Transparency builds trust, accountability, fairness, safety, and inclusiveness.</li>
</ul>
<h3 id="to-implement-transparency">To implement transparency:</h3>
<ul>
<li>Document data and models.</li>
<li>Use explanatory interfaces.</li>
<li>Apply debugging tools.</li>
<li>Build testing dashboards.</li>
<li>Maintain strong logging and auditing practices.</li>
</ul>
<h2 id="accountability">Accountability</h2>
<ul>
<li>People, not AI, are responsible for the behavior and impact of AI systems.</li>
<li>AI creators and organizations must monitor systems continuously, identify issues, and reduce risks.</li>
<li>Accountability is critical because AI can cause harm (bias, unfair decisions, misinformation) if not properly overseen.</li>
<li>Microsoft’s Responsible AI Standard requires companies to own responsibility for how their AI systems are designed, developed, deployed, and used.</li>
<li>AI systems must remain answerable to humans, not operate without oversight.</li>
</ul>
<h2 id="additional-information">Additional Information</h2>
<p>OpenAI created the generative pretrained language model in GitHub Copilot, powered by OpenAI Codex. An extension is available for Visual Studio Code (VS Code), Visual Studio, Neovim, and the JetBrains suite of integrated development environments (IDEs).</p>
<h1 id="interact-with-copilot">Interact with Copilot</h1>
<h2 id="inline-suggestions">Inline suggestions</h2>
<ul>
<li>Copilot shows real-time code completions as gray text ahead of your cursor.</li>
<li>Accept with <strong>Tab</strong> or the <strong>right arrow</strong>.</li>
<li>Reject by typing or pressing <strong>Esc</strong>.</li>
<li>Great for repetitive code and boilerplate.</li>
</ul>
<h2 id="command-palette">Command palette</h2>
<ul>
<li>Open with <strong>Ctrl+Shift+P</strong> (Windows/Linux) or <strong>Cmd+Shift+P</strong> (Mac).</li>
<li>Type <strong>“Copilot”</strong> to see all actions.</li>
<li>Common commands: <strong>Explain This</strong>, <strong>Generate Unit Tests</strong>, etc.</li>
<li>Useful for quick feature access.</li>
</ul>
<h2 id="copilot-chat">Copilot chat</h2>
<ul>
<li>Full chat panel for natural-language questions.</li>
<li>Ask for syntax help, examples, or algorithms.</li>
<li>Example question: “Implement binary search in Python.”</li>
<li>Ideal for learning and exploration.</li>
</ul>
<h2 id="inline-chat">Inline chat</h2>
<ul>
<li>Context-aware chat inside the editor.</li>
<li>Open with <strong>Ctrl+I</strong> / <strong>Cmd+I</strong>.</li>
<li>Great for localized edits, explanations, or improvements.</li>
</ul>
<h3 id="slash-commands">Slash commands</h3>
<ul>
<li><strong>/explain</strong> – explains selected code</li>
<li><strong>/suggest</strong> – suggests improvements</li>
<li><strong>/tests</strong> – generates unit tests</li>
<li><strong>/comment</strong> – converts comments to code</li>
</ul>
<h2 id="comments-to-code">Comments to code</h2>
<ul>
<li>Write a comment describing desired functionality.</li>
<li>Press Enter and Copilot generates the code automatically.</li>
<li>Very fast for simple features.</li>
</ul>
<h2 id="multiple-suggestions">Multiple suggestions</h2>
<ul>
<li>Copilot may offer multiple alternatives.</li>
<li>Cycle with <strong>Alt+]</strong> (Windows/Linux) or <strong>Option+]</strong> (Mac).</li>
</ul>
<h2 id="explanations">Explanations</h2>
<ul>
<li>Select code → right-click → <strong>Copilot: Explain This</strong>.</li>
<li>Helps understand unfamiliar or inherited code.</li>
</ul>
<h2 id="automated-test-generation">Automated test generation</h2>
<ul>
<li>Select a function or class.</li>
<li>Use command palette → <strong>Generate Unit Tests</strong>.</li>
<li>Copilot creates test cases to improve reliability.</li>
</ul>
<h1 id="summary-set-up-configure-and-troubleshoot-github-copilot">Summary: Set up, configure, and troubleshoot GitHub Copilot</h1>
<h2 id="sign-up-for-github-copilot">Sign up for GitHub Copilot</h2>
<ul>
<li>Go to <strong>GitHub → Settings → Copilot</strong> (under <em>Code, planning, and automation</em>).</li>
<li>Start a <strong>free trial</strong> or <strong>subscription</strong>.</li>
<li>Install the GitHub Copilot extension for your preferred environment:
<ul>
<li><a href="http://GitHub.com">GitHub.com</a> (no extension needed)</li>
<li>VS Code</li>
<li>Visual Studio</li>
<li>JetBrains IDEs</li>
<li>Neovim</li>
</ul>
</li>
</ul>
<blockquote>
<p>This module focuses on <strong>VS Code setup</strong>.</p>
</blockquote>
<h2 id="configure-github-copilot-in-vs-code">Configure GitHub Copilot in VS Code</h2>
<h3 id="add-the-github-copilot-extension">Add the GitHub Copilot extension</h3>
<ol>
<li>Open the <strong>GitHub Copilot</strong> page in Visual Studio Marketplace.</li>
<li>Select <strong>Install</strong> → open in <strong>VS Code</strong>.</li>
<li>In VS Code, select <strong>Install</strong> on the extension tab.</li>
<li>If needed, sign in to GitHub through VS Code.</li>
</ol>
<h3 id="enable-or-disable-github-copilot">Enable or disable GitHub Copilot</h3>
<ul>
<li>In the bottom status bar, use the <strong>Copilot status icon</strong>.</li>
<li>Choose:
<ul>
<li><strong>Enable completions</strong></li>
<li><strong>Disable completions globally</strong></li>
<li><strong>Disable completions for the current language</strong></li>
</ul>
</li>
</ul>
<h3 id="manage-inline-suggestions">Manage inline suggestions</h3>
<ul>
<li>Go to <strong>File → Preferences → Settings</strong>.</li>
<li>Select <strong>Extensions → GitHub Copilot</strong>.</li>
<li>Under <strong>Editor: Enable Auto Completions</strong>, check or uncheck to enable/disable inline suggestions.</li>
<li>You can also configure language-specific settings.</li>
</ul>
<h2 id="troubleshoot-github-copilot-in-vs-code">Troubleshoot GitHub Copilot in VS Code</h2>
<h3 id="view-logs">View logs</h3>
<ul>
<li>Open the command palette:
<ul>
<li><strong>Shift+Cmd+P</strong> (Mac)</li>
<li><strong>Ctrl+Shift+P</strong> (Windows/Linux)</li>
</ul>
</li>
<li>Run:
<ul>
<li><strong>Developer: Open Log File</strong>, or</li>
<li><strong>Developer: Open Extensions Logs Folder</strong></li>
</ul>
</li>
</ul>
<h3 id="view-electron-logs">View Electron logs</h3>
<ul>
<li>If regular logs don’t show errors:
<ul>
<li>Select <strong>Help → Toggle Developer Tools</strong>.</li>
</ul>
</li>
</ul>
<h3 id="diagnose-network-issues-firewalls-proxies">Diagnose network issues (firewalls, proxies)</h3>
<ul>
<li>Open the command palette again.</li>
<li>Search for <strong>Diagnostics</strong>.</li>
<li>Select <strong>GitHub Copilot: Collect Diagnostics</strong>.</li>
<li>This opens a new editor with troubleshooting information.</li>
</ul>

