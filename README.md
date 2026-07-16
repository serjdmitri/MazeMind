🐭 Maze Mind

Teach your own AI!

Maze Mind is an interactive, single-file web app that teaches reinforcement learning through hands-on maze solving. Build a maze, choose how the agent gets rewarded, then watch a mouse learn — through trial, error, and reward — to find its way to the cheese on its own. No backend, no dependencies: it's plain HTML, CSS, and JavaScript running entirely in the browser.

What it does

Reinforcement learning is how an AI agent learns by trial and error — earning rewards for good moves and penalties for bad ones — until it discovers the best strategy for reaching its goal. Maze Mind makes that process visible and interactive instead of abstract.

Modes

🤖 Train an AI

Design a maze (or have one generated for you), pick its size and shape, and train a real Q-learning agent to solve it. Three reward schemes are available:


Guided – draw the path you want the mouse to learn. It's rewarded for staying on it and penalized for straying, though it never actually sees the path — only the reward signal.
Discover it yourself – no path at all. The agent pays a flat cost per step and gets a big reward at the exit, so it has to find an efficient route entirely on its own.
Multiple Paths – more than one correct route exists; the agent is rewarded most for finding the shortest, with progressively smaller rewards for longer (but still valid) paths.


Switch into Discovery Mode to run episodes one at a time or train in bulk, and watch the agent improve. A results dashboard tracks episodes run, success rate, points earned, a learning curve, and a full run log, plus advanced controls for tuning the learning rate and exploration rate. A Speed slider (Normal → Instant) lets you fast-forward long training runs, adjustable even mid-run. Save and reload multiple trained agents at any time.

🧑 Become the AI

Flip the experience: now you're the agent. The maze is hidden until you step into it — walls only reveal themselves when you bump into them, exactly like the mouse discovers them one collision at a time. Earn and lose points the same way the AI does, restart on a mistake, and once you complete a maze with zero errors, it counts as a clean solve. Save your fastest clean times to a leaderboard and compete with friends.

Maze options


Shapes: Square, Double Square, and L-Shape mazes, each with independent size controls
Build your own maze by hand, or have one auto-generated
Live charts tracking time-to-finish across runs, per shape, so you can watch the agent (or yourself) get faster over time


Tech stack


Pure HTML, CSS, and vanilla JavaScript — no frameworks, no build step, no external libraries
Q-learning implemented from scratch in-browser
Progress (saved agents, leaderboard times) persisted via localStorage


Getting started

Just open maze-mind-v2_9.html in any modern browser — that's it.

Team

Built by Ally Rogin, Sergey Dmitriev, Lizzy Chu, and Bernardo Dias Martins.
