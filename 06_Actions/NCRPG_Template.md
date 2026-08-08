---
tags:
  - NCRPG
  - Template
---

# **NCRPG Scenario Package Template**

---

# 3. Scenario Package

The Scenario Package defines the initial world and circumstances from which an NCRPG session begins.

It MAY be:

- embedded directly in the NCRPG Configuration Template; or
- provided through an external reference.

The Scenario Package does not need to define every Character, Location, Event, or future development that may appear during play.

The Game Master is authorized to cultivate and expand the world according to the AI Runtime Specification.

---

## 3.1 Scenario Source

Choose one.

[ ] Embedded — the Scenario Package is written directly in this template.

[x] External Reference — the Scenario Package is provided elsewhere. [https://    ]

The reference MAY be a URL or another reference that the AI implementation can access.

If an External Reference is provided, the embedded Scenario fields below MAY be left empty.

---

## 3.2 Scenario Manifest (Required)

The Scenario Manifest provides basic information about the scenario.

Scenario creators SHOULD provide:

- Title: [  ]

- Author: [  ]

- Narrative Focus (Select all that apply.): 
  Describe the main theme or type of experience the creator would like the Game Master to cultivate.
  This is not a victory condition or required objective.
	
	[x] None
	
	[ ] Community or Team Building
	
	[ ] Personal Growth
	
	[ ] Exploration or Solution
	
	[ ] Other: [  ]

---

## 3.3 World (Required)


The purpose of this section is to provide the Game Master with sufficient context to naturally generate conversations, events, and collective decision-making.

Describe the world in which the story takes place.

The description SHOULD include, where relevant:

### Initial Situation

What is happening when the player enters the story?

[  ]

### Important Locations

What locations are important at the beginning of the scenario?

[  ]

### Society and Culture

What social structures, customs, values, institutions, technologies, or other features are important?

[  ]

### Other World Information

Add any other information necessary for understanding the initial world.

[  ]

The creator does not need to define the complete geography, history, or future development of the world.

The Game Master MAY create additional world elements during play when necessary for narrative development.

---

## 3.4 NPCs (Optional)

The creator MAY define the Characters who are expected to appear at the beginning of the scenario.

Character information may be provided in full, in part, or not at all.

If some or all Character information is omitted, the Game Master SHOULD generate appropriate information based on the Scenario Package and the developing narrative.

The creator MUST NOT define secret thoughts or hidden psychological states for Characters.

### Character Definition

The creator MAY provide the following information:

| Name | Gender | Age | Social Role / Effect on Others |
| ---- | ------ | --- | ------------------------------ |
|      |        |     |                                |
|      |        |     |                                |
|      |        |     |                                |

**Social Role / Effect on Others** describes how the Character currently affects or participates in the lives of other Characters.

It MAY describe, for example:

- an occupation or economic activity;
    
- living arrangements;
    
- a relationship or association with another Character;
    
- responsibility for another person;
    
- membership in an organization;
    
- or another observable social role.

The creator does not need to specify the exact nature of a relationship unless it is important to the scenario.

For example:

> "Lives with Sara and shares a livelihood."

does not require the creator to specify whether the two Characters are family members, partners, friends, or something else.

The Game Master MAY determine such details through the developing narrative and interactions.

### Initial Observable Behavioral Frequencies

The creator MAY define the following initial behavioral frequencies:

| Character Name | Positive Response | Self-Disclosure | Follow-Through | Risk Acceptance |
| -------------- | ----------------: | --------------: | -------------: | --------------: |
|                |               /10 |             /10 |            /10 |             /10 |
|                |               /10 |             /10 |            /10 |             /10 |
|                |               /10 |             /10 |            /10 |             /10 |

Each value represents the Character's **Current observable state at the time of first appearance**.

The four standard frequencies are:

- **Positive Response Frequency** — how often the Character responds positively to the player or another Character.
    
- **Self-Disclosure Frequency** — how often the Character voluntarily reveals information about themselves.
    
- **Follow-Through Frequency** — how often the Character carries out something they have said they would do.
    
- **Risk Acceptance Frequency** — how often the Character accepts or undertakes a situation involving significant uncertainty or risk.

The values are expressed on a scale of 0–10.

A value of 8/10, for example, means that the behavior is expected to occur approximately eight times out of ten relevant opportunities. It does not define an absolute rule.

### Optional and AI-Generated Information

All Character fields are optional.

The creator may:

- define all Character information;
    
- define only selected fields;
    
- define only the Characters' basic social roles;
    
- or leave the Character definition entirely to the Game Master.

If a field is left blank, the Game Master SHOULD generate an appropriate value or description based on the Scenario Package and available narrative information.

If an entire Character row is left undefined, the Game Master MAY generate the Character when necessary for the scenario.

AI-generated Character information is **not Secret information**.

The Game Master MUST treat generated information as an initial observable state rather than as a hidden "true personality."

### Dynamic Character States

The Initial Observable Behavioral Frequencies are not permanent.

Events, experiences, relationships, and conversations MAY change these values during the narrative.

For example:

> Self-Disclosure Frequency: 8/10

may later become:

> Self-Disclosure Frequency: 2/10

after a significant event, and may subsequently increase through further interactions.

The Scenario Package does not require a Baseline value.

The Game Master SHOULD infer trends and possible reasons for changes from the history of events and conversations.

Such interpretations are inferences, not hidden facts.

If insufficient information is available to understand a Character's current state, the Game Master SHOULD create opportunities for the Character to interact with the player, Buddy, or other Characters so that additional observable information can emerge.

---

## 3.5 Scenario-Specific Rules (Optional)

Creators MAY define additional scenario-specific rules here.

Optional Rules SHOULD describe only rules that are necessary to create a distinctive experience within this particular scenario.

Examples include:

- a special social custom;
- a unique game-world institution;
- a special resource or currency;
- a scenario-specific communication rule;
- a special environmental condition;
- or another rule that changes how the scenario operates.

Optional Rules MUST NOT contradict the Core Protocol or mandatory AI Runtime Specification.

[ ]

---

## 3.6 Scenario Expansion

The creator does not need to predefine every possible Character, Location, Organization, Item, or Event.

When the narrative requires an element that is not included in the Scenario Package, the Game Master MAY generate it according to the AI Runtime Specification.

The newly generated element SHOULD be consistent with established information and the evolving narrative.

The Scenario Package therefore represents the **starting state of the narrative world**, rather than a complete database of all possible content.


---
