# Construct Registry — Compilatorum → Semantic VM

> Status: experimental architecture / v0.1
> Principle: repositories are source corpora; glyphic atoms are the minimal semantic IR; constructs are reusable semantic capabilities; MicroDomains are addressable executable compositions.

## 1. Three levels

REPOSITORY → mining/extraction → GLYPHIC ATOM → clustering/typing → CONSTRUCT → compilation/binding → MICRODOMAIN → OPCODE → KERNEL → ENGINE → STATE → FEEDBACK

### Repository
A repository is evidence and raw material: code, specifications, experiments, schemas, prompts, diagrams, tests, README text and history. It is not automatically a construct.

### Glyphic atom
The smallest reusable semantic unit extracted from that corpus. Examples: → ROUTE, ⊕ COMPOSE, ? QUERY, Δ TRANSFORM, Σ AGGREGATE, Ω ORACLE, ◎ STATE, ↻ FEEDBACK, ◇ VALUE.

### Construct
A typed composition of atoms plus meaning, context, inputs, outputs, operators, constraints and provenance.

### MicroDomain
A deployable/addressable construct bundle: address + semantics + state + opcode + router + permissions + runtime + history. NFT is one possible representation/addressing mechanism; the semantic architecture does not depend on a specific NFT standard.

## 2. Complete ingestion pipeline

GitHub repos + chatlogs + prompts + artifacts
→ Semantic Miner
→ Glyph atoms + Evidence
→ Construct Registry
→ Semantic Compiler
→ PromptIR / GlyphIR
→ Semantic Router
→ MicroDomain Graph
→ Opcode Dispatch
→ Kernel + Engine Runtime
→ State′
→ Feedback / Provenance
→ Registry refinement

This makes Compilatorum a self-describing corpus: projects are simultaneously source code, experiments, evidence and candidate machine components.

## 3. Repository corpus

The current Compilatorum corpus includes 42 principal repositories. The following are provisional semantic roles inferred from repository names and the broader architecture; implementation evidence should be checked before a role becomes authoritative.

### Semantic / language / compilation
- glyphtionary — glyphic vocabulary, semantic atoms, Semantic IR
- compilatum — compilation / semantic transformation
- SLM — language-model / inference substrate
- NaturalLanguageCognitiveArchitecture — natural-language cognitive architecture
- promptcraft — prompt construction / prompt engineering
- Corpora — corpus / evidence substrate
- knowledge-weaver — knowledge integration / relation weaving
- cognitive-search-orchestrator — semantic retrieval / orchestration

### Oracle / cognition / simulation
- oracle — oracle runtime / uncertainty / inference
- cognitiv — cognitive constructs
- neurocoder-pwa — cognitive coding interface
- holographic-synthesis — synthesis / multi-perspective composition
- hypervision — observation / visualization
- neurosimbolic-trader — neuro-symbolic decision / simulation
- prompt-audiofeedback — prompt ↔ signal ↔ feedback loop

### Planning / agents / orchestration
- planner — planning / lifecycle / state transitions
- context-planner-pwa — contextual planning
- monorepo — composition / shared infrastructure
- omni-laboratory — experimental integration surface
- harness-engineering — evaluation / execution harness
- uml-navigator — architecture / graph navigation
- lottie-flow — process / flow representation
- storybook-genui — component / UI grammar
- lovable-command-center — command-center / orchestration UI
- canvas — visual workspace / artifact surface

### Web3 / DAO / economic substrate
- DAO — governance / proposal lifecycle / machine specification
- value-curator — value curation / semantic valuation
- vc — venture / capital allocation
- web3-launchpad-pro — Web3 launch / project lifecycle
- farcaster-nexus — social / agent / network routing
- defi-kingdom — DeFi/game economic experiments
- dfk-pecdoa-postman-cockpit — DAO / protocol operations
- invest-os — investment operating system
- sovereign-budget — budget / resource allocation
- regenerativo — regenerative systems / resource flows

### Data / infrastructure / resources
- lakehouse — data lakehouse / semantic data substrate
- InternaResources — resource ontology / internal knowledge
- links-vault — link / reference graph
- gdrive-reorg — information architecture / organization
- cult — cultural / semantic corpus
- uap-synthesis-project — heterogeneous evidence synthesis

### Domain experiments / transformation
- molora — compositional / molecular semantics
- kaelvive-reversa — transformation / reversal
- cadcad-explorer — computational modeling / mechanism simulation
- sovereign-html-mockups — interface / sovereign UI experiments

## 4. Construct families

### Semantic
SEMANTIC-ATOM, GLYPH, GLYPHTIONARY, ONTOLOGY, SEMANTIC-IR, SEMANTIC-ROUTER, HERMENEUTIC-FUNCTOR, SEMIURGY, CONTEXT, MEANING, PROVENANCE

### Cybernetic
SYSTEM, MACHINE, MECHANISM, ENGINE, KERNEL, STATE, TRANSITION, FEEDBACK, CONTROL, OBSERVATION, ADAPTATION, SCADA

### Computational
PROGRAM, PROMPT, PARSER, COMPILER, INTERPRETER, VM, RUNTIME, OPCODE, DISPATCH, MEMORY, AGENT

### Cognitive
INTENT, ATTENTION, COGNITION, DIGITAL-TWIN, HYPERCOMMUNICATION, REASONING, INFERENCE, REFLECTION

### Economic / Web3
VALUE, CURATION, TOKEN, NFT, MICRODOMAIN, WALLET, ADDRESS, DAO, GOVERNANCE, MECHANISM-DESIGN, YIELD, X-POLLINATION, RESOURCE-FLOW

### Lifecycle / maturity
CONCEPT, HYPOTHESIS, MOCK, PROTOTYPE, POC, MVP, PILOT, PROJECT, SCALE, ARCHIVE

These families are not silos: a construct can be polymorphic across families.

## 5. Glyphic layer

Flow: → ROUTE, ↔ CONNECT, ↻ FEEDBACK, ⇢ EMIT
Composition: ⊕ COMPOSE, ⊗ INTERSECT, ∪ MERGE, ÷ DECOMPOSE
Transformation: Δ TRANSFORM, ↺ REVERSE, ⇄ MAP, Σ AGGREGATE
Cognition / inference: ? QUERY, Ω ORACLE, ∴ INFER, ≈ SIMULATE, ! VALIDATE
State / value: ◎ STATE, ◇ VALUE, $ ALLOCATE, ⚑ GOVERN

A glyph is useful only when it has a typed operational interpretation. Decorative symbolism is not enough.

## 6. Canonical construct record

Suggested fields: id, version, type, ontology, atoms, operators, inputs, outputs, constraints, relations, provenance and maturity.

Example: maturity
- type: lifecycle.construct
- ontology: project-lifecycle
- atoms: ◎ STATE; Δ TRANSFORM; ! VALIDATE
- operators: CLASSIFY; ASSESS; TRANSITION
- inputs: artifact; evidence
- outputs: maturity_state
- constraints: evidence_required=true
- provenance: planner; DAO; value-curator; chatlogs; specifications
- maturity: experimental / provisional confidence

## 7. Semantic addresses

construct://maturity
construct://value-curation
construct://semantic-router
construct://hermeneutic-functor
construct://nft-microdomain
construct://x-pollination
construct://oracle
construct://mechanism-design
construct://dao-lifecycle
construct://prompt-vm

A prompt can import semantics instead of reproducing context: USE construct://maturity; USE construct://value-curation; ANALYZE target://compilatorum/*.

## 8. Repository → Construct → MicroDomain

value-curator → value + curation + ranking + Web3 + resource allocation → VALUE-CURATION → construct://value-curation → md://compilatorum/value-curator → VALUE / FILTER / ROUTE / SIMULATE

glyphtionary → glyph + semantic relation + opcode → SEMANTIC-IR → construct://glyphtionary → PromptVM instruction substrate

DAO → proposal + lifecycle + governance → DAO-LIFECYCLE → construct://dao-lifecycle → GOVERN / ROUTE / VOTE / EXECUTE / FEEDBACK

## 9. Construct graph

Repository —produces→ Atom
Atom —composes→ Construct
Construct —instantiates→ MicroDomain
MicroDomain —implements→ Opcode
Opcode —requires→ Kernel
Kernel —executes-on→ Engine
Execution —changes→ State
State —emits→ Feedback
Feedback —updates→ Construct

This graph is the data model for the Cytoscape.js SCADA semiótico.

## 10. Compilatorum as self-compiling system

Compilatorum corpus → semantic mining → construct registry → PromptVM → new analysis/synthesis → new constructs → updated Compilatorum.

The machine consumes its own artifacts as source material. This is the bootstrap loop.

## 11. Critical distinctions

1. Repository ≠ construct. A repo is evidence/corpus; extraction must establish the semantic unit.
2. Glyph ≠ construct. A glyph is an atom/instruction/symbol; a construct has ontology, behavior, relations and provenance.
3. NFT ≠ semantics by itself. Tokenization does not automatically create a computational MicroDomain; executable semantics must be explicit.

The operational criterion is: addressable + interpretable + routable + executable + stateful + composable.

## 12. Next registry structure

construct-registry/
├── atoms/
├── constructs/
├── opcodes/
├── kernels/
├── microdomains/
├── repositories/
├── schemas/
└── graph/

The registry becomes the semantic backbone shared by PromptVM, Cytoscape SCADA, GitHub corpus and future Web4/NFT representations.