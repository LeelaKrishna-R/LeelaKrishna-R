<h1 align="center">Leelakrishna Ravuri</h1>

<p align="center">Systems integration, moving into infrastructure and networking.</p>

---

👋 I run a homelab and spend most of my time keeping real systems alive. When something breaks enough times, I end up building a small tool to deal with it, and that's most of what you'll find here.

I've got a Master's in AI from the University of North Texas and an Electronics and Communication background, and right now I'm going deeper into infrastructure and networking while studying for the CCNA. I lean on the AI side where it genuinely helps, not just to use it. On the side I also do some dev work at [dexterai.org](https://dexterai.org).

I'd rather show real, tested work than a wall of logos, and I try to be honest about what I'm still figuring out.

## 🛠️ Stuff I've built

**🤖 Friday** · [heyfriday.dev](https://heyfriday.dev)

- Personal AI assistant built as a bunch of small agents that hand work off to each other.
- Has a self-healing layer that notices when something falls over and brings it back.
- Runs on my own hardware at home. The code goes public in the next few days.

**🌐 [net-triage](https://github.com/LeelaKrishna-R/net-triage)**

- Reads a network log or a device config and tells you what's probably wrong, then points at the exact lines that give it away.
- Calling an LLM is the easy part. The part I care about is the eval harness that measures how often it's actually right, so it's a real number (6 out of 6 on the cases it ships with) instead of "trust me."
- TypeScript, 18 tests.

**♻️ [lazarus](https://github.com/LeelaKrishna-R/lazarus)**

- Self-healing monitor for a homelab. Watches your hosts, shrugs off the random one-off blips, and restarts a downed service over SSH on its own.
- Built to stay safe: it only runs commands you've whitelisted, backs off after a couple of tries, and has a dry-run mode so you can see exactly what it would do first.
- Python, one dependency, 42 tests.

**💸 [agent-budget](https://github.com/LeelaKrishna-R/agent-budget)**

- A small npm package I published. Tracks token usage and cost for LLM agents with zero dependencies, so you can set a budget on an agent and actually see what it's spending.

**🎮 Discord bots** built with discord.js, which is where a lot of my hands-on JavaScript comes from.

## 🧰 What I actually work with

- Hands-on with JavaScript, Node, and discord.js.
- The Linux and Git basics you pick up from running your own boxes.
- Building projects in Python and TypeScript, still sharpening both.
- Head-down on networking right now, working toward the CCNA.

## 📊 My GitHub at a glance

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=LeelaKrishna-R&theme=tokyo-night&hide_border=true" />
</p>

## 📫 Reach out

- [LinkedIn](https://www.linkedin.com/in/leelakrishnaravuri/)
- [Email](mailto:leelakrishnaravuri999@gmail.com)
- [krishnar.xyz](https://krishnar.xyz)
