# DECISION TREES

## DT01: How Should I Enter This Audience's World?

```
START
│
├─ Am I part of this community?
│  ├─ YES → Use Fit-In Strategy (their language, their world)
│  │  ├─ Do I want to modify their beliefs?
│  │  │  ├─ YES → Use Frame Shift Framework (F02)
│  │  │  └─ NO → Communicate within their world directly
│  │  └─ DONE
│  └─ NO → STOP. Do Audience Deconstruction (F03) first
│     ├─ Can I map enough to enter?
│     │  ├─ YES → Proceed with Fit-In Strategy
│     │  └─ NO → Do not attempt communication yet
│     └─ DONE
```

## DT02: Which Direction Should I Zoom?

```
START
│
├─ Is my audience broad/general?
│  ├─ YES → ZOOM IN (universe → continent → city → location)
│  │  → Start with big picture agreements, narrow to specifics
│  └─ NO (expert/specialized)
│     → ZOOM OUT (location → city → continent → universe)
│     → Start with a specific detail they recognize, expand
```

## DT03: How Do I Root This Claim?

```
START
│
├─ Do concrete examples of success exist?
│  ├─ YES → Use real case studies. Stack as many as possible.
│  └─ NO
│     ├─ Can I build a prototype?
│     │  ├─ YES → Use prototype as existence proof
│     │  └─ NO
│     │     ├─ Does an analogous example from another domain exist?
│     │     │  ├─ YES → Use it as approximate rooting
│     │     │  └─ NO → STOP. Claim is unrootable right now.
│     │     │     → Wait, build proof, or run experiments
│     │     └─ DONE
│     └─ DONE
```

## DT04: Which Persuasion Method Should I Use?

```
START
│
├─ Does target hold a belief I want to change?
│  ├─ Can I identify two conflicting beliefs they hold?
│  │  ├─ YES → Dissonance Resolution Framework (F05)
│  │  └─ NO
│  │     ├─ Can I enter their world and modify incrementally?
│  │     │  ├─ YES → Frame Shift Framework (F02)
│  │     │  └─ NO
│  │     │     ├─ Is there a single root assumption to challenge?
│  │     │     │  ├─ YES → Leverage Point Framework (F04)
│  │     │     │  └─ NO → Start from atomic units, build very slowly
│  │     │     └─ DONE
│  │     └─ DONE
│  └─ DONE
│
├─ Is target resistant/hostile?
│  ├─ YES → Validate their position first
│  │  → "You are right to be skeptical..."
│  │  → Lower defenses before ANY new information
│  │  → NEVER brute-force with contradicting facts
│  └─ NO → Proceed with standard frameworks
```

## DT05: How Complex Should My Language Be?

```
START
│
├─ Is audience scale broad (thousands+)?
│  ├─ YES → Maximize simplicity
│  │  → Simplest possible language
│  │  → Relatable scale (small numbers, not large)
│  │  → Stories, not statistics
│  └─ NO (specialized/insider)
│     → Use in-group language
│     → Tribal signals increase trust
│     → Technical depth is acceptable
│     → Jargon signals membership
```

## DT06: How Many Arguments Should I Present?

```
START
│
├─ Do I have ONE devastating argument?
│  ├─ YES → Use ONLY that argument
│  │  → Concentrate all force on the root assumption
│  │  → Do NOT dilute with supporting points
│  └─ NO
│     ├─ Do I have multiple arguments of equal strength?
│     │  ├─ YES → Lead with the one closest to audience's worldview
│     │  │  → Use frame shift to bridge gap
│     │  └─ NO → Find the leverage point. You don't have it yet.
│     └─ DONE
│
│ NEVER present arguments as equal-weight laundry list
```

## DT07: How Should I Design This AI Prompt?

```
START
│
├─ Is desired output generic/exploratory?
│  ├─ YES → Broad prompt acceptable (but still set SOME laws)
│  └─ NO (specific/constrained output needed)
│     → Construct detailed universe:
│        1. Set physical laws (constraints, boundaries)
│        2. Define entities and relationships
│        3. Provide few-shot examples
│        4. Specify anti-patterns explicitly
│        5. Add micro-details for richness
│     │
│     ├─ Does output have AI defaults I want to avoid?
│     │  ├─ YES → Explicitly declare as anti-patterns
│     │  │  → e.g., "Do not use 'not just X, it's Y'"
│     │  └─ NO → Proceed
│     └─ DONE
```

## DT08: Stories or Data?

```
START
│
├─ Is audience decision driven by emotion/identity?
│  ├─ YES → Concrete stories
│  │  → Single compelling narrative > aggregate data
│  └─ NO (analysis/logic driven)
│     → Data BUT wrapped in a story frame
│     → "Person X used to... now they... result is..."
│
│ NEVER present raw statistics without narrative anchoring
```

## TRIGGERS (Signals to change approach)

| Signal | Meaning | Action |
|--------|---------|--------|
| Audience uses jargon you don't recognize | You're in the wrong world | STOP → Map their world first |
| Your argument has >3 supporting points | You haven't found the leverage point | STOP → Find the root assumption |
| Audience resists harder with more evidence | You're brute-forcing | Switch to validation-first |
| AI output feels generic | Prompt universe is unconstrained | Add laws, examples, specifics |
| Reader disengages | Cognitive load too high | Simplify language and structure |
| You can't name their world | You haven't done audience work | Run Audience Deconstruction (F03) |

## STOPPING CONDITIONS

| Condition | Action |
|-----------|--------|
| No examples to root with | Stop building that world. Wait or build proof. |
| Audience cognitive immune system activates | Stop adding complexity. Validate. Simplify. |
| Wrong leverage point identified | Stop arguing. Redo root-cause analysis. |
| AI output matches desired universe | Stop adding prompt detail. Ship. |
