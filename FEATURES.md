# Resonance: A Plague Tale Legacy: Feature Scope

Status: Module concept - not implemented. Checked 2026-09-05.

The items below are proposed capabilities. They are not release notes or a list of working features.

## Chapter profiles

Investigate named local progress snapshots organised by chapter and game version.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Damage assistance

Research adjustable incoming damage so practice can use a small amount of help instead of an all-or-nothing setting.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Combat timing

Explore a bounded practice-speed option while checking animation, audio and scripted events.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Encounter retries

Design a repeatable encounter workflow where the available save structure permits reliable restoration.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Exploration notes

Keep optional puzzle and collection notes beside each chapter without asserting automatic completion.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Assistance presets

Plan separate exploration and combat profiles with a clear list of proposed changes.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Shared application architecture

This theme is one adapter for a common application. The shared interface can manage profiles and show change previews; each game adapter must implement and validate its own behaviour. No universal memory addresses, item identifiers, save paths or hotkeys are supplied.

## Session scope

The proposed game-state assistance is scoped to the single-player game. Profile restoration must account for the complete relevant state, including any separate world and character data.

## First implementation target

A player wants to practise one encounter without repeating the preceding chapter. The planned profile would record the starting point and a modest assistance level, then allow another attempt with less help.
