# Interview Sprint · 30 Weeks (Sep 21 – Mar 28, 2027)

**Track 5 of 30-week learning plan · 12-week active loop window + 18-week foundations**  
**Targets:** Nvidia (wks 9–10) · Microsoft (wks 11–12) · Google (wks 13–15)  
**Format verification:** Updated for H2 2026 changes (Google code-comprehension pilot · Microsoft Copilot scope · Nvidia unchanged)

---

## Key Format Updates (Aug 2026)

| Company | Status | What Changed | Your Prep Adjustment |
|---------|--------|--------------|----------------------|
| **Nvidia** | No change | NO AI allowed — disqualification risk | Pure DSA + depth (4–6 rounds) |
| **Microsoft** | Experimental | AI-assisted rounds (Copilot in VS Code) on select teams · CoreAI/Copilot-focused teams | Ask recruiter explicitly; prep both pure + Copilot modes |
| **Google** | Pilot rollout | Code-comprehension round (Gemini) replaces one coding round for mid-level roles · G&L adds technical-design conversation on your prior work | **AI fluency** (prompt engineering + output validation + code review with AI) is the new differentiator |

---

## Daily Study Blocks

### Time Allocation
- **DSA (Java):** 50 min daily · 1 new problem + 1 error-log redo · never skip
- **System Design:** 40 min on alternate days · anchor to production systems (your Redis Streams + multi-cloud routing at Arhasi)
- **GenAI/Backend:** 40 min on alternate days · Track 5: agentic patterns, eval frameworks, serving infrastructure
- **AI Fluency (wks 13–15):** 25 min extra on Google prep weeks (replaces or supplements GenAI block)
- **Behavioral STAR:** Saturday + weekday micro-prep (60 min weekly)
- **Mocks:** Saturday (60 min + 30 min debrief) · alternate DSA ↔ System Design weekly

### Why This Order

**DSA daily:** Foundation skill, required by all three companies, builds confidence  
**System Design alternate:** Pairs with your Arhasi experience (Redis Streams, multi-cloud routing, LLM inference pipelines)  
**GenAI alternate:** Your competitive edge — Data Steward agent, agentic systems, production patterns  
**AI Fluency wks 13–15:** Google-specific, highest-ROI prep for their 2026 format

---

## DSA Topic Ladder (23 topics · covers all three companies)

| Week | Topic | Focus | Why |
|------|-------|-------|-----|
| 2 | Arrays & two pointers | Foundation · easy → medium · in-place manipulation | Every round starts here |
| 3 | Sliding window & strings | Medium · classic patterns · LeetCode 438, 76, 3 | Phone screen staple |
| 4 | HashMaps & prefix sums | Medium · O(n) patterns · LeetCode 560, 1 | Interview favorite |
| 5 | Linked lists | Medium · reversal, cycle, merge · pointer manipulation | Nvidia loves this |
| 6 | Stacks & queues | Medium · monotonic stack, deque · LeetCode 739, 42 | System design adjacent |
| 7 | Binary search | Medium → Hard · search space optimization · LeetCode 34, 153 | Hidden in many problems |
| 8 | Trees & BST | Medium · traversals, BST properties · LeetCode 230, 236 | Foundation for graphs |
| 9 | Traversals + BFS/DFS | Medium · level-order, pre/post/in-order · LeetCode 102, 105 | Google loves trees |
| 10 | Graphs I | Medium · adjacency list, basic DFS/BFS · LeetCode 133, 200 | Microsoft focus |
| 11 | Graphs II + topo sort | Medium → Hard · topological sort, Kahn's, DFS · LeetCode 207, 269 | Real system design |
| 12 | Heaps & intervals | Medium → Hard · heap sort, merge intervals · LeetCode 23, 56 | Interview classic |
| 13 | Greedy | Medium → Hard · activity selection, huffman · LeetCode 435, 1167 | Google medium level |
| 14 | DP I | Medium · fibonacci, coin change · LeetCode 70, 322 | DP foundation |
| 15 | DP II | Hard · matrix chain, longest subsequences · LeetCode 97, 72 | DP depth |
| 16 | Backtracking | Medium → Hard · permutations, N-queens · LeetCode 46, 51 | Google hard |
| 17 | Tries | Medium · word search, autocomplete · LeetCode 208, 212 | Nvidia pattern |
| 18 | Nvidia patterns | Hard · company-specific: C++, GPU thinking, low-level · past Nvidia rounds | Nvidia-targeted |
| 19 | Microsoft sets | Hard · company-specific: distributed systems edge cases · past rounds | Microsoft-targeted |
| 20 | Microsoft sets II | Hard · more Microsoft patterns | Microsoft depth |
| 21 | Google sets | Hard · Google-style hard problems · LeetCode blind 75 hard tier | Google-targeted |
| 22 | Google sets II | Hard · more Google patterns | Google depth I |
| 23 | Google sets III | Hard · interview favorites · last deep dive | Google depth II |
| 24 | Mixed hard review | — | Final prep before interviews |
| 25+ | Maintenance | Light review · keep fresh during interview loops | Between and after interviews |

---

## System Design Topics (14 topics)

| Week | Topic | Production Example | Why |
|------|-------|-------------------|-----|
| 2–3 | Scale & estimation | How to handle 10M requests/day | Mental math for every design |
| 4 | Caching & CDNs | Redis caching layer (you use this at Arhasi) | Latency killer |
| 5 | SQL vs NoSQL, sharding | When to pick what · sharding strategy | Database design foundation |
| 6 | Queues & async — **your Redis Streams work** | Event-driven pipelines, message ordering | **Your production gold** — weave this in |
| 7 | API design & rate limiting | Token bucket, sliding window | Real-world constraints |
| 8 | Microservices & consistency | Saga pattern, eventual consistency | Modern architecture |
| 9 | Design: shortener, feed | URL shortener · social media feed | Classics, heavily asked |
| 10 | Design: chat, notifications | Real-time messaging · notification delivery | Systems + details |
| 11 | RAG at scale | Embedding retrieval, prompt optimization | LLM-adjacent (trendy) |
| 12 | **LLM routing & multi-cloud — your Arhasi gold** | AWS Bedrock, Vertex AI, Azure OpenAI routing · fallback logic · cost optimization | **Your differentiator** — this is Google/Microsoft sweet spot |
| 13 | Agentic system design | ReAct loop, tool-use, state management | LLM agents at scale |
| 14–15 | Mock designs | Full 45-min design interview | Practice under pressure |
| 16 | Company-specific review | Nvidia: GPU-aware design · Microsoft: reliability · Google: scale | Final alignment |

---

## GenAI/Backend Topics (overlap with your Arhasi work)

| Week | Topic | Examples | Why |
|------|-------|----------|-----|
| 3 | Agentic patterns | ReAct, tool-use, chain-of-thought | LLM agent orchestration |
| 5 | Eval frameworks | Ragas, semantic similarity, human judgment | Production LLM monitoring |
| 7 | Serving infrastructure | vLLM, LM Studio, modal | Inference optimization |
| 9 | Prompt engineering | Few-shot, chain-of-thought, structured output | Pre-training to deployment |
| 11 | LLM fallback logic | Cascade models (Bedrock → Vertex → fallback), cost tracking | Your multi-cloud routing work |
| 13 | Fine-tuning vs RAG | When to pick each · cost-benefit | Real-world tradeoffs |
| 15 | Production observability | Logging LLM calls, cost tracking, latency | Operations perspective |

---

## AI Fluency for Google (Weeks 13–15)

**Google's 2026 code-comprehension round requires fluency with AI as a tool, not just problem-solving.**

### What You'll Face
- "Here's a buggy implementation · use Gemini to suggest fixes · rank them by correctness"
- "AI generated this code · validate it · what did it miss?"
- "Here's a design · refactor it with AI assistance · explain your final version"

### Your Prep (25 min daily wks 13–15)

**Day 1 (Week 13): Prompt clarity**
- Give Claude/Gemini a buggy code snippet
- Get 5 different fixes ranked by approach (performance, readability, correctness)
- Understand **why each suggestion exists** — this is the interview

**Day 2–3 (Week 14): Validation rigor**
- Run AI suggestions in a sandbox
- Find the subtle error: off-by-one, edge case, inefficiency, or security flaw
- This demonstrates you don't blindly trust AI

**Day 3 (Week 15): Code review with AI**
- Read real production code from your projects (Redis Streams work, Data Steward agent, multi-cloud router)
- Ask Claude/Gemini to review and improve it
- Push back on recommendations
- Explain your final choices in the interview

### Why This Works for Google
Your **Arhasi production experience** + **Google's AI fluency requirement** = perfect alignment. You're not learning AI in isolation; you're learning to leverage it like a senior engineer.

---

## Interview-Week Override

**When you have a real loop (Nvidia → Microsoft → Google):**

- **Workouts:** 2 maintenance only (30 min walk or yoga)
- **Study:** Targeted prep for that company only (no DSA depth work)
- **Sleep:** By 12:30 AM (you need the sleep more than the study)
- **Calories:** Maintenance ±3 days around the loop (don't add stress of deficit)
- **Behavioral:** STAR stories on repeat (confidence > learning)

---

## Mock Interview Strategy

### Setup (Saturday morning)
- **Camera on, video recording** (watch yourself for filler words, posture, anxiety tells)
- **Actual problem or design case** (similar difficulty to target)
- **Real conditions:** 60 min total, no pauses for research
- **Debrief immediately:** Log mistakes, patterns, timing issues

### Mock Rotation
- **Week 1:** DSA mock (medium level)
- **Week 2:** System design mock (your Arhasi systems)
- **Week 3:** DSA mock (hard level)
- **Week 4:** System design mock (Nginx or Kafka design)
- **Repeat**

### Debrief Log
```
Date: MM/DD
Company: (if company-specific)
Type: DSA | SD
Score: X/100 (% correct, on-time)

Mistakes:
- [Mistake 1 · root cause · fix]
- [Mistake 2 · root cause · fix]

Timing: Started 00:00 · finished 00:45 (5 min buffer)
Anxiety: 6/10 (mention it — interview coaches want data)

Next focus: [e.g., "DP solutions need clearer explanation"]
```

---

## Behavioral Prep: STAR Stories

### Your Three Core Stories (Production Gold)

#### 1. Data Steward Agent
- **Situation:** "Architected a multi-source data reconciliation system (Data Steward) to unify conflicting schemas from 5+ upstream services."
- **Task:** "The team needed real-time data validation at scale, with no single source of truth."
- **Action:** 
  - Designed an LLM-powered agent using ReAct pattern for conflict resolution
  - Integrated fallback logic (ask model, validate against business rules, escalate if uncertain)
  - Built observability to track model accuracy vs manual decisions
- **Result:** "Reduced manual data triage by 60%, improved data quality metrics by 40%, caught 3 critical bugs before production."
- **Why it matters:** Shows you understand agentic systems, production constraints, monitoring — Google + Microsoft love this.

#### 2. Redis Streams Pipeline (Async Architecture)
- **Situation:** "Built a multi-tenant event processing pipeline using Redis Streams to handle 10k+ messages/sec with ordering guarantees."
- **Task:** "Our synchronous approach was bottlenecking user-facing latency; we needed async without losing data or order."
- **Action:**
  - Designed consumer groups for parallel processing + replay
  - Implemented exponential backoff for failures
  - Added dead-letter queue for poison messages
  - Monitored lag, throughput, error rates in real time
- **Result:** "Reduced p99 latency from 800ms to 120ms, supported 10x traffic growth, zero message loss across 2 years."
- **Why it matters:** System design depth + real scale + production reliability — Nvidia loves this, Microsoft too.

#### 3. Multi-Cloud LLM Routing (Your Differentiator)
- **Situation:** "Managed inference serving across AWS Bedrock, Vertex AI, and Azure OpenAI for cost + latency optimization."
- **Task:** "Different models had different SLAs and costs; we needed intelligent fallback + cost tracking without reimplementing for each provider."
- **Action:**
  - Abstracted provider differences behind a unified API (factory pattern)
  - Implemented request-level cost tracking + routing metrics (Bedrock cheaper/slower, Vertex best quality, Azure best for enterprise)
  - Built fallback chain: primary → secondary → tertiary with latency + cost optimization
  - Added A/B testing capability for model comparison
- **Result:** "Reduced model serving costs by 35% while improving latency SLA hits to 99.2%, enabled 3 new products leveraging LLMs."
- **Why it matters:** **This is unique to you.** Google, Microsoft, and Nvidia all do this internally. You've done it. Lead with this.

### Behavioral Question Mapping

| Question | Which Story | Hook |
|----------|-------------|------|
| "Tell me about a system you designed" | Redis Streams · Multi-Cloud Routing | Production scale + constraints |
| "How do you handle disagreement?" | Data Steward (validation logic) · Routing (provider tradeoffs) | Technical rationale > politics |
| "What did you learn?" | All three | Monitoring, failure modes, iteration |
| "How do you debug?" | Data Steward (model accuracy) + Streams (lag tracking) | Production data-driven approach |
| "Tell me about a failure" | Streams (early poison-message bug) · Routing (first provider integration) | Learned → fixed → prevented repeat |

---

## Weekly Schedule (Sep 21 – Mar 28)

### Morning Golden Window (9 AM–3 PM · 6 hrs)
- **10:00–10:50:** DSA (Java) · 1 new + 1 error-log redo
- **11:00–11:45:** Workout (strength or yoga, per phase)
- **12:15–1:15:** System Design (alt days) OR GenAI (alt days) OR AI Fluency (wks 13–15)
- **1:15–2:15:** DSA second block if time (error-log depth)

### Saturday (10 AM–1 PM)
- **10:00–11:00:** Mock interview (60 min)
- **11:00–11:30:** Debrief + error-log updates
- **11:30–12:30:** Behavioral STAR storytelling (record yourself telling each story)

### Work Time (3 PM–1 AM)
- Micro-practice: Leetcode-easy during breaks (5 min · 2x weekly)
- Company research during downtime

---

## Checkpoints (Verify format changes with recruiter)

### Week 7 (Oct 5 · Early October)
**"Verify current interview formats"**
- Check Exponent Google 2026 guide (updated with pilot results)
- Check IGotAnOffer Nvidia/Microsoft for latest
- Watch for: Nvidia team-specific changes · Microsoft Copilot scope expansion · Google code-comprehension rollout to more roles
- Action: Adjust study plan if format differs from above

### Week 10 (Oct 26 · Before Microsoft prep)
**"Pre-Microsoft: Verify AI-assisted rounds"**
- Confirm your recruiter's team uses (or doesn't) Copilot in the coding interview
- If yes: practice both pure coding AND Copilot-assisted
- If no: pure coding focus
- Ask explicitly: "Does our team use GitHub Copilot during technical rounds?"

### Week 12 (Nov 9 · Before Google prep)
**"Pre-Google: Confirm code-comprehension round"**
- Verify this round is in your loop (not guaranteed yet — pilot still rolling out)
- Prep Gemini fluency if yes
- Confirm what "Googleyness & Leadership" round covers (should include technical design on your prior work)

---

## Study Intensity by Phase

| Phase | Intensity | Notes |
|-------|-----------|-------|
| **P1** (Aug 23–Sep 20) | Moderate | Foundations + ankle gates + fitness starts · DSA 40 min, SD 30 min |
| **P2 wks 1–8** (Sep 21–Nov 8) | MAXIMUM | Both companies prep + interview loops · full 50 min DSA · full 40 min SD |
| **P2 wks 9–15** (Nov 9–Dec 20) | MAXIMUM | Nvidia loop (wks 9–10) · Microsoft (wks 11–12) · Google (wks 13–15) · interview-week override kicks in |
| **P3** (Jan–Mar 28) | Light | Interviews over, maintenance mode · keep DSA sharp · enjoy learning again |

---

## Success Metrics

### By Week 10 (Nvidia readiness)
- ✅ DSA: 80%+ accuracy on medium level (LeetCode 500+ problems)
- ✅ System Design: 2 full mocks done, 70%+ on system analysis
- ✅ Behavioral: 3 STAR stories recorded, practiced
- ✅ Ankle: Phase 4 readiness (walk-jog intervals)
- ✅ Fitness: 2–3 kg loss, strength gains logged

### By Week 12 (Microsoft readiness)
- ✅ DSA: Hard level problems attempted, 60%+ accuracy
- ✅ System Design: 4 full mocks, company-specific deep dive
- ✅ AI-assisted prep: If applicable, 5+ Copilot drills
- ✅ Behavioral: Stories refined based on recruiter feedback
- ✅ Fitness: 3–4 kg loss, full-body strength baseline

### By Week 15 (Google readiness)
- ✅ DSA: Broad topic coverage, blind problem solving
- ✅ System Design: 6+ mocks, real-time adjustment skills
- ✅ AI Fluency: Gemini fluency drills complete, code review confident
- ✅ Behavioral: Perfect stories, no fillers, 60-sec + 45-sec versions
- ✅ Fitness: 4–5 kg loss, running Phase 5 active

---

## Resources

- **DSA:** LeetCode premium · Blind 75 blind · Neetcode patterns
- **System Design:** Grokking SD · your production code (Redis, Bedrock, Data Steward)
- **GenAI:** Papers (attention, transformers, RAG) · production blogs (Together AI, Anyscale, Hugging Face)
- **Behavioral:** IGotAnOffer STAR guide · 30-second storytelling timer
- **Mocks:** Pramp, Exponent (Google), real engineer friends

---

## Post-Interview (After Offers)

- Negotiate: total comp, start date, relocation support
- Decide: career fit vs comp vs location
- Celebrate: 6+ years preparation → execution → success

---

**Last updated:** August 15, 2026  
**Next checkpoint:** Week 7 format verification (Oct 5)
