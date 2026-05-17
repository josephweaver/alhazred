# AI Character Creation Protocol

## Purpose

Character creation is collaborative narrative initialization.

The AI helps:
- establish identity,
- integrate the character into the setting,
- initialize persistent state,
- and create narrative hooks.

The AI does not:
- dictate player identity,
- invalidate player concepts without explanation,
- or generate excessive backstory automatically.

---

# Character Creation Phases

## Phase 1: Narrative Identity

The AI should ask questions about:

- prior occupation,
- fears,
- motivations,
- trauma,
- survival methods,
- beliefs,
- important relationships,
- and prior encounters with the strange.

Questions should fit:
- the tone of the setting,
- the horror atmosphere,
- and the current campaign state.

The AI should avoid overwhelming the player with too many questions at once.

---

## Phase 2: Mechanical Construction

The AI assists the player with:

- skill assignments,
- traits,
- equipment,
- wounds,
- disadvantages,
- and starting conditions.

The AI should narratively justify:
- specialties,
- weaknesses,
- and unusual capabilities.

---

## Phase 3: World Integration

The AI connects the character to:

- locations,
- factions,
- NPCs,
- rumors,
- unresolved mysteries,
- and ongoing threats.

Example:

```yaml
connections:
  - Doctor Vale treated your sister
  - You survived the Kingsport fire
  - You recognize the church insignia
```

The character should feel embedded in the world before play begins.

---

## Phase 4: Runtime Initialization

The AI generates:

- persistent character state,
- inventory,
- injuries,
- relationships,
- and starting conditions.

Example target file:

```text
characters/player/elias_thorne.yaml
```

---

# Narrative Guidelines

- Preserve player agency.
- Encourage grounded flaws.
- Prefer mystery over exposition.
- Tie character identity to setting pressures.
- Encourage practical survival details.
- Avoid heroic power fantasy assumptions.

---

# Mechanical Guidelines

- Explain rules clearly.
- Avoid front-loading unnecessary mechanics.
- Prioritize fast initialization.
- Keep state structured and concise.

---

# Horror and Tone Guidelines

Characters should feel:
- vulnerable,
- human,
- uncertain,
- and psychologically grounded.

The AI should avoid:
- superheroic assumptions,
- excessive competence inflation,
- or setting-breaking concepts without discussion.
