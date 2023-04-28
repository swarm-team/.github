### What is the {swarm} project?
Our goal is to develop GUIs and exploits for Chrome Extensions or internal chrome:// pages which contain code execution vulnerabilities in one way or another.

### How do these pages have code execution?
Generally, these pages will be vulnerable for two reasons.
1. [Point-blank](https://bolg.glitch.me/_/point-blank/), a bookmarklet exploit:
- Usage of window.open() in the vulnerable page
- A controllable link or redirect on a vulnerable page
- An HTML injection bug in the vulnerable page (contenteditable textboxes or dynamic injection)
2. A third-party script loaded unsafely on the vulnerable page which is controllable to DNS spoofing.

### What are we doing with these?
Making exploits using the privileges of these pages. Our main goal is to bypass some sorts of restrictions on enrolled Chromebooks.

### What are our projects?
- unfinished
