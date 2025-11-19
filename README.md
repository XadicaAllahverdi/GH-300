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
<hr>
<h2 id="fairness">Fairness</h2>
<p>Detect bias and mitigate unfair impacts such as:</p>
<ul>
<li>Reviewing training data.</li>
<li>Testing models with balanced demographic samples.</li>
<li>Using adversarial debiasing.</li>
<li>Monitoring model performance across user segments.</li>
<li>Implementing controls to override unfair model scores.</li>
</ul>
<hr>
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
<hr>
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
<hr>
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
<hr>
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

