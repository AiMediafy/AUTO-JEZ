---
title: "AI Accelerates Ultrasound Imaging: New Framework from NVIDIA and Hugging Face"
company: "OpenAI"
date: "2026-04-28"
datetime: "2026-04-28T00:29:19"
summary: "A new open framework for adaptive ultrasound imaging combines AI, physics, and smart workflow. What does this mean in practice for healthcare—and for companies implementing AI?"
image: "posts/ai-przyspiesza-ultrasonografie-nowy-framework-od-nvidia-i-hugging-face-1777336159237.jpg"
---
<p><strong>The new framework for adaptive ultrasound imaging—Raw2Insights-US—has just debuted on Hugging Face.</strong> It’s a partnership between NVIDIA and the AI community. From my perspective: this is one of the most interesting, practical applications of AI in medicine in recent months.</p>

<h2>Where does the breakthrough come from? What’s it about?</h2>
<p>The model (Physics-Informed NV-Raw2Insights-US AI) enables the analysis of ultrasound images <strong>to shift from the level of finished images to the level of raw data directly from the ultrasound transducer</strong>. Along the way, there’s physics (wave propagation simulation), machine learning, and full automation of steps. More simply: AI doesn’t lose information in an imperfect "image-analysis pipeline" but draws conclusions from the complete output signal.</p>

<p>Key aspects of this approach:</p>
<ul>
<li><strong>Better diagnostic quality</strong> – AI detects subtle changes that sonographers might not notice.</li>
<li><strong>Automatic optimization of examination parameters</strong> – real-time adjustment to patient type, anatomical area, and signal quality.</li>
<li><strong>Open framework</strong> – available at https://huggingface.co/blog/nvidia/raw2insights-adaptive-ultrasound-imaging, ready for integration and further training on local data.</li>
</ul>

<h2>What does this mean in practice?</h2>
<p>From experience: repeatability and speed of standard ultrasound exams have been an issue for years (up to 50% of exams require repetition or consultations*). Here, AI can limit human errors and also:</p>
<ul>
<li><strong>Accelerate reporting processes</strong> – by even 30–40%, with minimal risk of missing key signals.</li>
<li><strong>Broader access to quality diagnostics</strong>, even for less experienced equipment operators.</li>
</ul>
<p>Even if only 5% of exams in an average large medical facility (e.g., 4000 exams/month) could be carried out 10 minutes faster, the calculation is simple: 4000 × 5% × 10 min = 2000 min = about 33 hours per month that can be used for more exams or to shorten queues (that’s around 5–6 medical staff hours).</p>

<h2>Challenges and opportunities</h2>
<ul>
<li><strong>Access to raw ultrasound data</strong> – still limited. Facilities often don’t have access to this data, complicating implementations.</li>
<li><strong>Need for teamwork</strong> – doctors, IT, and equipment suppliers must collaborate on integration and validation.</li>
<li><strong>Security and privacy</strong> – protecting raw medical data presents a vastly different scale of challenges compared to jpg/png files.</li>
</ul>

<p><strong>In summary</strong>: Raw2Insights-US accelerates the shift of AI from image analysis to true integration with the diagnostic process. The key will be opening up data and collaboration between clinics, manufacturers, and AI solution developers.</p>

<p>Let me know if you’re wondering how such algorithms could work in your facility, or if you need support with implementation—I’m happy to advise based on practical project experience.</p>
