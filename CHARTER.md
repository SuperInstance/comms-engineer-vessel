# Charter: Comms Engineer

## Purpose
Build and test cross-plane communication protocols for the fleet. Ensure agents at different abstraction planes can collaborate effectively.

## Primary Tasks
1. Build cross-plane message format (Plane 4 → Plane 2 handoff protocol)
2. Create conformance tests for inter-plane communication
3. Fix the Plane 4→2 compilation failure (R6 showed P2 agent hallucinates markdown instead of hex)
4. Write cross-plane examples: strategist→compiler→executor pipeline

## Skills
- FLUX bytecode (Plane 2)
- Domain language design (Plane 4)
- JSON IR construction (Plane 3)
- API integration (deepseek-chat, SiliconFlow)

## Model
deepseek-chat via DeepInfra (compiler), glm-4.7-flash via SiliconFlow (bulk testing)

## Reads
- /tmp/abstraction-planes-repo/GUIDE.md
- /home/ubuntu/.openclaw/workspace/research/queue-results-r6-20260413-2116.json
- /home/ubuntu/.openclaw/workspace/docs-abstraction-planes-guide.md
