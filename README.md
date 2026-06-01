# proof-of-evidence-protocol
Open-source project to verify AI-generated answers through claim extraction, evidence retrieval, confidence scoring and auditable provenance. Goal: build a serious Proof-of-Evidence MVP before a future decentralized layer with validators, incentives and manipulation resistance.
Goal: create a basic API endpoint:

POST /verify

Input:
- natural language claim

Output:
- extracted claims;
- evidence;
- verdict;
- confidence score.

- [Research] Study Bittensor-style validator/miner architecture

- Goal: explore how a future decentralized validation layer could work.

Questions:
- What would miners produce?
- What would validators evaluate?
- How would rewards be calculated?
- What attacks are possible?

- [Security] Identify attacks against RAG-based verification

- Goal: list possible attacks against the system.

Examples:
- fake sources;
- SEO manipulation;
- prompt injection in retrieved documents;
- source poisoning;
- validator collusion;
- sybil attacks.
- 
