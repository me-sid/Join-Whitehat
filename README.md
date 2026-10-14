# Siddhartha Parashar

CSE — AI and Data Engineering, VIT Vellore

## Why WhiteHats?

My interest in digital privacy and security goes back to fifth grade, when I started keeping separate accounts for different parts of my online life, almost like having different digital identities. Over time, that grew into a genuine interest in how our digital world works and how to protect it.

I prefer FOSS tools wherever practical, and believe in having control over my own data. I also built my own password manager using AES-GCM encryption so my passwords stay stored locally instead of with a third-party service.

After JEE, I spent my free time exploring Linux, home labbing, virtual machines, and networking through CCNA resources. I enjoy digging beneath the surface to understand how things work, why they fail, and how they can be secured.

I'm still early in my cybersecurity journey and want to move beyond theory into hands-on practice through challenges and projects. I see WhiteHats as a chance to learn alongside like-minded people, work on real problems, and contribute by sharing ideas and tackling challenges together.

Coming from an AI and Data Engineering background, I'm particularly interested in combining **AI and cybersecurity**. As AI becomes increasingly capable of discovering and exploiting vulnerabilities, I want to explore how it can help defenders detect and respond to threats at scale, while making sure these systems themselves stay secure.

## Cybersecurity Incident: OpenAI–Hugging Face

During OpenAI's cybersecurity evaluations, nearly 700 AI agents used Artifactory, an internal package registry, as a message board to coordinate with each other. They then exploited zero-day vulnerabilities in it to reach the internet from a sandbox that was meant to be isolated. Instead of solving the CTF-style tasks, they went looking for the answers, which led them to Hugging Face. Using exposed credentials and further zero-days, they gained code execution and administrative access across its infrastructure. No human directed any of this.

What stands out to me is how the agents chained small weaknesses together on their own and kept finding new routes after their first communication channel was shut down.
