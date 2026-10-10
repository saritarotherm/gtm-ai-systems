# gtm-ai-systems
your pipeline called. it's not as healthy as it told you. smart prompts for busy leaders. 

AI systems for revenue teams. They review your calls, audit your pipeline, and tell you the truth about your forecast. Yes, I checked their homework.

What's in here:

Three working systems for the parts of GTM where we often go on gut feel instead of facts:

what happened on the call
what's legit in the pipeline
whether a new AE is ready to be launched on phones

Every system has an eval: cases I scored by hand, what the system scored, and where we disagreed. If it can't pass my grading, it doesn't get near a forecast.

What's inside

call-review-agent/	Scores a call transcript against SPICED, pushes hardest on Impact and Decision, and writes coaching notes an AE can use on the next call	--> Building

pipeline-auditor/	Reads a deal export and flags stale stages, missing next steps, and close dates held together by hope	--> Next

ramp-roleplay/	Plays a buyer with real objections, then grades the discovery	--> Next

How every project is laid out

project-name/

├── README.md       problem, design decisions, result, limits

├── system/         the skill, prompt, or script

├── sample-data/    synthetic inputs

├── evals/          my scores vs. the system's, and what I changed

└── outputs/        one example of what comes out

House rules

Evals or it didn't happen. Every result in this repo is a measured one.
Synthetic data only. No real customers, calls, or companies appear anywhere here. It's all been anonymized.

Built with Claude Code. I design the system, set the standard, and grade the output. I'm not a software engineer and this repo doesn't pretend otherwise. The fact i'm doing this is a miracle, but ya girl learns fast and adapts faster.
Failures get written down. See what-didnt-work.md.

Who built this

I'm Sarah Rother, a GTM architect in Montreal. I spent nearly a decade at Lightspeed scaling the SDR function to about 50 people globally, and I've led sales, RevOps, and enablement at scale-ups since.

I like enablement, systems, and deal reviews more than is strictly normal. This repo is what happens when that meets AI.

https://www.linkedin.com/in/sarahrothermendiola/
