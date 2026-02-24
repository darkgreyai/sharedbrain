# sharedbrain
Permanent memory architecture for OpenClaw agents — survives context compression, resets, and updates

SharedBrain is a battle-tested memory architecture for OpenClaw agents, running in production on a 16-agent setup. It stores agent memory outside ~/.openclaw/ so OpenClaw can never wipe it, and connects all agents to a shared knowledge base via memorySearch.extraPaths.
