
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
