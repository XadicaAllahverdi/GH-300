<h2 id="github-copilot-spaces-—-summary">GitHub Copilot Spaces — Summary</h2>

<h3 id="overview-1">Overview</h3>
<p><strong>GitHub Copilot Spaces</strong> provide a focused way to work with AI by grounding responses in a <strong>curated, tightly scoped context</strong>. Unlike general Copilot Chat, Spaces are designed for <strong>depth, consistency, and reproducibility</strong> rather than broad exploration.</p>
<hr>
<h3 id="what-is-a-copilot-space-1">What is a Copilot Space?</h3>
<ul>
<li>A <strong>dedicated Copilot chat</strong> centered on a specific topic or workflow</li>
<li>Context is explicitly defined by you</li>
<li>Can include:
<ul>
<li>GitHub files (code, configs, docs)</li>
<li>Issues and pull requests</li>
<li>Free-text instructions</li>
</ul>
</li>
<li>Acts like a specialized, domain-focused AI assistant<br>
<img src="https://learn.microsoft.com/en-us/training/github/introduction-copilot-spaces/media/adding-instructions.png" alt="Inbound Flow Diagram"></li>
</ul>
<hr>
<h3 id="why-spaces-improve-answer-quality-1">Why Spaces Improve Answer Quality</h3>
<ul>
<li>Narrowed context reduces noise</li>
<li>Leads to <strong>more accurate, consistent, and predictable responses</strong></li>
<li>Ideal for repeatable or domain-specific tasks</li>
<li>Context ordering matters: most important inputs should come first</li>
</ul>
<hr>
<h3 id="setting-context-effectively-1">Setting Context Effectively</h3>
<h4 id="attaching-files-1">Attaching Files</h4>
<ul>
<li>Use <strong>Attach files / Add context</strong> during Space setup</li>
<li>Supported context:
<ul>
<li>Source code</li>
<li>Markdown documentation</li>
<li>Configuration files</li>
</ul>
</li>
<li>Files are pulled from the <strong>default branch</strong>, staying up to date</li>
<li>Optional local uploads (if workspace allows), such as images or datasets<br>
<img src="https://learn.microsoft.com/en-us/training/github/introduction-copilot-spaces/media/copilot-chat.png" alt="Inbound Flow Diagram"></li>
</ul>
<h4 id="adding-instructions-1">Adding Instructions</h4>
<ul>
<li>Use the <strong>Instructions</strong> section to guide Copilot</li>
<li>Can include:
<ul>
<li>Goals (e.g., “Summarize onboarding”)</li>
<li>Style preferences (formal, concise, etc.)</li>
<li>Examples of expected output</li>
</ul>
</li>
<li>Best practices:
<ul>
<li>Keep instructions brief and actionable</li>
<li>Include step-by-step workflows if relevant</li>
<li>Update instructions anytime to refine focus<br>
<img src="https://learn.microsoft.com/en-us/training/github/introduction-copilot-spaces/media/adding-instructions.png" alt="Inbound Flow Diagram"></li>
</ul>
</li>
</ul>
<hr>
<h3 id="when-to-use-copilot-spaces-1">When to Use Copilot Spaces</h3>
<p>Use a Space when you need:</p>
<ul>
<li>Consistent answers on a <strong>specific topic</strong></li>
<li>Support for:
<ul>
<li>A particular service</li>
<li>Runbooks or playbooks</li>
<li>Known datasets or workflows</li>
</ul>
</li>
<li>Predictable, grounded outputs rather than broad discovery</li>
</ul>
<hr>
<h3 id="best-practices-1">Best Practices</h3>
<ul>
<li>Keep Spaces <strong>small and focused</strong> (model context limits apply)</li>
<li>Lead with the <strong>most important files or instructions</strong></li>
<li>Use <strong>clear, concise instructions</strong></li>
<li>Add <strong>canonical examples</strong> to anchor style and expectations</li>
<li>Remember: context selection and order directly affect responses</li>
</ul>
<hr>
<h3 id="key-trade-off-1">Key Trade-off</h3>
<ul>
<li><strong>Spaces:</strong> depth, precision, consistency</li>
<li><strong>General Chat:</strong> breadth, exploration, discovery<br>
breadth, exploration, discovery</li>
</ul>
<h2 id="creating-your-first-github-copilot-space">Creating Your First GitHub Copilot Space</h2>
<p>Creating a <strong>Copilot Space</strong> is simple but powerful. Once created, it becomes a <strong>reusable workspace</strong> where Copilot operates within a clearly defined scope, enabling precise and grounded AI interactions.</p>
<hr>
<h2 id="what-you’ll-learn">What You’ll Learn</h2>
<ul>
<li>How to create a Space and name it for discoverability</li>
<li>The difference between <strong>personal</strong> and <strong>organization-owned</strong> Spaces</li>
<li>How to add and structure context using instructions and attachments</li>
<li>Why organization and clarity improve Copilot’s responses</li>
</ul>
<hr>
<h2 id="creating-a-space">Creating a Space</h2>
<p>To create a Space:</p>
<ol>
<li>Go to <strong><a href="https://github.com/copilot/spaces">https://github.com/copilot/spaces</a></strong></li>
<li>Click <strong>Create space</strong></li>
<li>Enter a <strong>clear and descriptive name</strong></li>
<li>Choose ownership:
<ul>
<li><strong>Personal</strong> (only you manage it)</li>
<li><strong>Organization-owned</strong> (shareable via GitHub permissions)</li>
</ul>
</li>
<li>(Optional) Add a <strong>description</strong> to explain the Space’s purpose</li>
<li>Click <strong>Save</strong></li>
</ol>
<blockquote>
<p>💡 You can edit the name and description anytime using <strong>Edit</strong> in the top-right corner.</p>
</blockquote>
<hr>
<h2 id="adding-context-to-a-space">Adding Context to a Space</h2>
<p>Spaces support <strong>two types of context</strong>, which directly influence response quality.</p>
<hr>
<h3 id="instructions-free-text">Instructions (Free Text)</h3>
<p>Instructions tell Copilot <strong>how to behave</strong> in this Space.</p>
<p>Use them to define:</p>
<ul>
<li>Areas of expertise</li>
<li>Tasks Copilot should help with</li>
<li>Things Copilot should avoid</li>
</ul>
<p>Well-written instructions help Copilot align with your <strong>intent and workflow</strong>.</p>
<hr>
<h3 id="attachments">Attachments</h3>
<p>Attachments provide <strong>grounded context</strong> for better answers.<br>
Spaces always reference the <strong>latest version from the main branch</strong>.</p>
<p>You can add:</p>
<ul>
<li><strong>Files and folders</strong> from GitHub repositories (code, docs, configs)</li>
<li><strong>Linked issues and pull requests</strong> (via URLs)</li>
<li><strong>Uploaded files</strong> (images, documents, spreadsheets)</li>
<li><strong>Text content</strong> (notes, transcripts, pasted references)</li>
</ul>
<hr>
<h2 id="why-organization-matters">Why Organization Matters</h2>
<ul>
<li>Clear structure improves relevance</li>
<li>Focused context leads to more accurate responses</li>
<li>Organized Spaces are easier to reuse and share</li>
<li>Less ambiguity = better Copilot output</li>
</ul>
<h1 id="sharing-discoverability-and-governance-—-summary">Sharing, Discoverability, and Governance — Summary</h1>
<h2 id="goal">Goal</h2>
<p>Make Copilot Spaces <strong>easy to find</strong>, <strong>safe to share</strong>, and <strong>accurate over time</strong> with lightweight governance.</p>
<hr>
<h2 id="visibility--sharing">Visibility &amp; Sharing</h2>
<ul>
<li>Set visibility based on intended use (personal vs organization).</li>
<li>Share via link; rely on org browsing/catalogs if available.</li>
<li>Use a <strong>clear, purpose-driven title</strong> and short description.</li>
<li>Follow <strong>“one job per Space”</strong> principle.</li>
</ul>
<hr>
<h2 id="security--access">Security &amp; Access</h2>
<ul>
<li>Spaces <strong>inherit GitHub permissions</strong> (no new access granted).</li>
<li>Users only see repos/issues/PRs they already have access to.</li>
<li>Avoid pasting sensitive data in free text.</li>
<li>Prefer <strong>linking version-controlled files</strong>.</li>
</ul>
<hr>
<h2 id="discoverability">Discoverability</h2>
<ul>
<li>Use consistent <strong>naming conventions</strong> (e.g., <code>ServiceName—Onboarding Helper</code>).</li>
<li>Add 1–2 sentence descriptions with <strong>scope, audience, outputs</strong>.</li>
<li>Include tags/keywords and announce in org channels if applicable.</li>
</ul>
<hr>
<h2 id="versioning--freshness">Versioning &amp; Freshness</h2>
<ul>
<li>Spaces reference <strong>live GitHub sources</strong> (default branch).</li>
<li>Linked issues/PRs update automatically.</li>
<li>Keep scope small to reduce drift.</li>
<li>For snapshots or branch-specific guidance:
<ul>
<li>Narrow file references</li>
<li>Add brief examples</li>
<li>Attach text files if supported</li>
</ul>
</li>
</ul>
<hr>
<h2 id="governance-lightweight">Governance (Lightweight)</h2>
<ul>
<li>Assign a clear <strong>owner/maintainer</strong>.</li>
<li>Add a short <strong>“How to use this Space”</strong> note.</li>
<li>Include <strong>1–3 canonical examples</strong> of good output.</li>
<li>Split Spaces if they grow beyond a single job.</li>
</ul>
<hr>
<h2 id="review-cadence">Review Cadence</h2>
<ul>
<li>Review <strong>monthly or per release</strong>.</li>
<li>During review:
<ul>
<li>Validate links</li>
<li>Test 2–3 prompts</li>
<li>Update examples</li>
<li>Remove stale/noisy sources</li>
<li>Reconfirm visibility &amp; access</li>
</ul>
</li>
<li>Track feedback (issues, discussions, or checklist).</li>
</ul>
<hr>
<h2 id="checklist-exam-friendly">Checklist (Exam-Friendly)</h2>
<ul>
<li>✅ Clear title &amp; description</li>
<li>✅ Correct owner &amp; visibility</li>
<li>✅ Permissions verified (inherit GitHub access)</li>
<li>✅ No sensitive data in free text</li>
<li>✅ Consistent naming &amp; keywords</li>
<li>✅ Assigned maintainer</li>
<li>✅ Regular review cadence</li>
</ul>
<h1 id="do’s-and-don’ts-of-working-in-a-space-—-summary">Do’s and Don’ts of Working in a Space — Summary</h1>
<h2 id="do’s">Do’s</h2>
<ul>
<li><strong>Keep questions tightly scoped</strong> to attached sources (files, issues, PRs, notes).</li>
<li><strong>Use the Space for a single task/domain</strong> and reuse its terminology for consistency.</li>
<li><strong>Prompt for verifiable outputs</strong>: confirm intent, then add concrete constraints (format, paths, time ranges).</li>
<li><strong>Ask for runnable artifacts</strong> (code, queries, commands) and references to included sources when useful.</li>
<li><strong>Iterate to improve quality</strong>: tighten instructions, add 1–3 strong examples, prune noisy sources.</li>
<li><strong>Keep context fresh and ordered</strong>: link version-controlled files (default branch) and lead with key sources.</li>
</ul>
<h2 id="don’ts">Don’ts</h2>
<ul>
<li><strong>Don’t @-mention people or extensions</strong>—mentions don’t notify users and extensions won’t run.</li>
<li><strong>Don’t expect external discovery</strong> beyond what’s attached (unless repo search is explicitly supported).</li>
<li><strong>Don’t let the Space sprawl</strong> beyond one job or exceed context limits; split if answers degrade.</li>
<li><strong>Don’t paste sensitive data</strong> into free text; link to repos or use uploads with proper permissions.</li>
</ul>

