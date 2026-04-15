---
title: "VAKRA from IBM: A New Benchmark for AI Agents – Analysis of Opportunities and Limitations"
company: "OpenAI"
date: "2026-04-15"
datetime: "2026-04-15T12:21:26"
summary: "IBM’s VAKRA benchmark assesses how AI handles reasoning and tool use in real-world tasks. What does this mean for AI adoption in companies? Here are the specifics."
image: "posts/vakra-od-ibm-nowy-benchmark-dla-agentow-ai-analiza-szans-i-ograniczen-1776255686529.jpg"
---
<p><strong>The new VAKRA benchmark from IBM Research provides a real testing ground for AI agents who not only need to understand tasks, but also utilize tools – like search engines, APIs, or external calculators.</strong> This immediately raises questions: how do current models (OpenAI, Google, Anthropic, xAI, etc.) perform, and what does this mean for business?</p>

<h2>What does VAKRA actually test?</h2>
<p><strong>VAKRA focuses on several classic challenges:</strong></p>
<ul>
  <li>Multi-step reasoning (e.g., analyzing data, connecting facts)</li>
  <li>Effective collaboration with third-party tools (e.g., fetching data from APIs, generating PDFs, online search)</li>
  <li>Context tracking – does the model remember what it has done and what it needs?</li>
</ul>
<p>From my experience, the key point is that VAKRA isn’t just based on typical prompts. These are tasks very close to real business projects, where the agent must do something specific and repeat it in different contexts.</p>

<h2>Findings from the tests – where do models fall short?</h2>
<ul>
  <li><strong>Workflow issues:</strong> Models often forget earlier steps or fail to integrate data from multiple sources (which, in real deployments, can halt the entire process).</li>
  <li><strong>Insufficient tool usage:</strong> Even when a model has access to an API or search engine, it doesn’t always know when and how to use these functions effectively.</li>
  <li><strong>Errors in understanding complex instructions:</strong> For more complex tasks, output accuracy drops by a dozen or so percentage points (in practice: if you deploy such an agent on a process 5h × 20 tasks × 60 PLN/h = roughly 6,000 PLN monthly, the losses from errors become significant).</li>
</ul>

<h2>Potential – why should you be watching this?</h2>
<p>The benchmark shows that progress in AI isn’t just about larger models, but above all <strong>better orchestration and tool integration</strong>. If your company is planning to implement AI agents to automate tasks—it’s definitely worth testing live how they handle typical VAKRA challenges. <strong>Benchmark data lets you assess the ROI of deployment without illusions.</strong></p>

<h2>What do you need to do to make an agent work in your company?</h2>
<ul>
  <li>Ensure clearly defined tasks and triggers—without this, the model will get "lost."</li>
  <li>Detailed integration with tools (APIs, databases, CRM) and strong control over permissions.</li>
  <li>Testing on real data with your team—preferably in several iterations.</li>
</ul>

<p>In summary: <strong>VAKRA doesn’t provide “magical” solutions, but a realistic view of what AI can already do, and where human corrections are still essential.</strong> It’s worth following, as future benchmark versions will get ever closer to actual business processes.</p>

<p>If you want to talk about this, or test an agent on your own data—reach out. Subscribe to the newsletter so you don’t miss the next set of specifics.</p>
