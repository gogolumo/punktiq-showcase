# Punktiq Product Overview

## Summary

Punktiq is an interactive, mobile-first study-companion prototype. It connects concise study material, active checks, practical exercises, goals, rewards, peer context, and a companion character in one deliberate learning loop.

Its initial design context is students in KdG Applied Computer Science, but the broader product question is portable: can a study tool make the next useful action obvious, verify that action, and turn the result into motivating progress without becoming another distracting feed?

## The problem

Students often manage course content, notes, exercises, deadlines, and motivation in separate places. Three weaknesses follow:

1. **Passive progress:** opening or reading content can feel like completion even when understanding was never checked.
2. **Fragmented context:** the next useful action is hidden across documents, platforms, and personal notes.
3. **Shallow gamification:** streaks and points can reward activity volume instead of meaningful learning.

Punktiq treats those as one product-design problem rather than three unrelated features.

## Target experience

A student should be able to open Punktiq and immediately understand:

- what to study next;
- how long it is likely to take;
- what action proves completion;
- how that completion changes today's goal;
- how their progress relates to a relevant academic cohort.

The product avoids an infinite social feed. Peer context is purposeful and scoped to academic relationships such as cohort, course, programme, and friends.

## Core loop

1. Simon recommends one focused study action.
2. The student opens a concise study item.
3. A practical exercise or short question set checks understanding.
4. A passed attempt becomes a completion.
5. The completion grants XP and separate cosmetic credits.
6. Daily-goal, streak, and leaderboard state update.
7. Simon reacts and guides the next action.

An unsuccessful attempt produces feedback and another chance; it does not produce XP.

## Main product areas

### Home

The dashboard is organised around a single Simon recommendation, supported by daily progress, missions, deadlines, and private notes.

### Study library

Study items can be explored by course and status. The intended information hierarchy includes difficulty, estimated duration, reward, and completion state without exposing an overwhelming catalogue at once.

### Active checks and SQL practice

Reading leads to an explicit check. For database topics, the prototype also contains an in-browser SQL practice environment that compares query output in a contained local dataset before the learner proceeds.

### Progress and rewards

XP represents verified learning progress. Credits are intentionally separate and can support Simon cosmetics without changing academic rank. This separation avoids turning purchasable or cosmetic activity into learning status.

### Academic cohort leaderboard

The leaderboard is scoped to meaningful academic contexts. Screen names are the default public identity. The prototype currently uses sample entries and does not claim live institutional data.

### Simon Buddy

Simon provides prompts, reactions, mood, and cosmetic expression. The companion supports the learning loop rather than becoming a general-purpose assistant.

### Administration and integrity

The product model includes seasons, integrity alerts, review, and auditable administrative actions. The current prototype demonstrates an overview and selected actions; several deeper admin sections remain explicit placeholders.

## Fairness and privacy decisions

- screen names are used by default in rankings;
- real-name visibility should require an explicit choice;
- duplicate rewards for the same completed item are blocked in the prototype logic;
- failed attempts do not award XP;
- rankings are derived from accumulated XP rather than invented rank jumps;
- suspicious behaviour should be reviewed rather than automatically punished;
- season-closing and integrity decisions need an audit trail;
- users should be able to opt out of competitive visibility in a production version.

## Product boundaries

Punktiq is currently an interactive prototype. It does not claim:

- production authentication or security;
- a deployed multi-user backend;
- official KdG integration or endorsement;
- real cohort participation or validated engagement metrics;
- production-ready anti-fraud;
- permission to redistribute KdG course content.

Those boundaries are part of the product story: the prototype validates interaction and domain decisions before institutional or backend complexity is introduced.
