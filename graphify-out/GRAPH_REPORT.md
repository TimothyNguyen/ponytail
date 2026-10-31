# Graph Report - ponytail  (2026-10-27)

## Corpus Check
- 204 files · ~465,918 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 11 file(s) not represented in the graph (top: .toml 6, (none) 3, .mdc 1)

## Summary
- 896 nodes · 1644 edges · 54 communities (46 shown, 8 thin omitted)
- Extraction: 95% EXTRACTED · 5% INFERRED · 0% AMBIGUOUS · INFERRED: 86 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Community 0
- Community 1
- Community 2
- Community 3
- Community 4
- Community 5
- Community 6
- Community 7
- Community 8
- Community 9
- Community 10
- Community 11
- Community 12
- Community 13
- Community 14
- Community 15
- Community 16
- Community 17
- Community 18
- Community 19
- Community 20
- Community 21
- Community 22
- Community 23
- Community 24
- Community 25
- Community 26
- Community 27
- Community 28
- Community 29
- Community 30
- Community 31
- Community 32
- Community 33
- Community 34
- Community 35
- Community 36
- Community 37
- Community 38
- Community 39
- Community 40
- Community 41
- Community 42
- Community 43
- Community 44
- Community 45
- Community 46
- Community 47
- Community 48
- Community 49
- Community 50
- Community 53

## God Nodes (most connected - your core abstractions)
1. `register()` - 29 edges
2. `getPonytailInstructions()` - 17 edges
3. `_fail()` - 14 edges
4. `_ok()` - 14 edges
5. `ponytailExtension()` - 14 edges
6. `judge_call()` - 13 edges
7. `run_cell()` - 13 edges
8. `main()` - 13 edges
9. `getDefaultMode()` - 13 edges
10. `_import()` - 12 edges

## Surprising Connections (you probably didn't know these)
- `AGENTS.md compact always-on rules` --semantically_similar_to--> `Ponytail skill: lazy senior dev ruleset`  [INFERRED] [semantically similar]
  AGENTS.md → skills/ponytail/SKILL.md
- `Band task board + CSV ledger (optional)` --optional_part_of--> `Adapter: Claude Code plugin + hooks`  [INFERRED]
  .claude-plugin/plugin.json → docs/agent-portability.md
- `copilot-instructions.md (static rule copy)` --semantically_similar_to--> `AGENTS.md compact always-on rules`  [INFERRED] [semantically similar]
  .github/copilot-instructions.md → AGENTS.md
- `Adapter: Claude Code plugin + hooks` --uses--> `Lifecycle: SubagentStart injects into subagents (Claude only)`  [EXTRACTED]
  docs/agent-portability.md → hooks/ponytail-subagent.js
- `Adapter: Claude Code plugin + hooks` --uses--> `Lifecycle: UserPromptSubmit tracks /ponytail level`  [EXTRACTED]
  docs/agent-portability.md → hooks/claude-codex-hooks.json

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Ruleset injection path (single source -> per-agent delivery)** — sem_skill_ponytail, hooks_ponytail_instructions, sem_additional_context, sem_pi_system_prompt [EXTRACTED 1.00]

## Communities (54 total, 8 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.06
Nodes (77): RFC-4180, boardHtml(), day(), duration(), elapsed(), esc(), fmtTokens(), json() (+69 more)

### Community 1 - "Community 1"
Cohesion: 0.03
Nodes (62): assert, bandFlag, claudeEnv, codebuddyConfigDir, codebuddyEnv, codebuddyHome, codebuddyState, codexData (+54 more)

### Community 2 - "Community 2"
Cohesion: 0.05
Nodes (53): csvRow(), field(), fs, { getClaudeDir }, HAIKU_55_LONG, human(), ledgerDir(), mergeRows() (+45 more)

### Community 3 - "Community 3"
Cohesion: 0.09
Nodes (22): _contained(), _fail(), _find(), _find_class(), _import(), _import_pkg(), _ok(), score_auth() (+14 more)

### Community 4 - "Community 4"
Cohesion: 0.11
Nodes (18): _cli_call(), aggregate(), _base_cmd(), _claude_version(), _git(), _git_snapshot(), main(), _one() (+10 more)

### Community 5 - "Community 5"
Cohesion: 0.15
Nodes (16): main(), parse_complete(), _rank_ok(), run(), one(), selftest(), selftest_offline(), submission() (+8 more)

### Community 6 - "Community 6"
Cohesion: 0.06
Nodes (29): assert, claudeDir, configDir, configPath, cursorDir, cursorFlagPath, cursorHooksPath, env (+21 more)

### Community 7 - "Community 7"
Cohesion: 0.12
Nodes (23): activate(), claudeDir, {
  clearMode,
  cursorRuleNotice,
  cursorRulePath,
  isCodeBuddy,
  isCodex,
  isCopilot,
  isCursor,
  readMode,
  setMode,
  writeHookOutput,
}, { execFileSync }, finish(), fs, { getDefaultMode, getClaudeDir, isShellSafe }, { getPonytailInstructions } (+15 more)

### Community 8 - "Community 8"
Cohesion: 0.11
Nodes (16): isDeactivationCommand(), normalizeConfigMode(), normalizePersistedMode(), completePonytailArgs(), {
  DEFAULT_MODE,
  RUNTIME_MODES,
  getDefaultMode,
  getQuietStartup,
  getHideStatus,
  normalizeMode,
  normalizePersistedMode,
  isDeactivationCommand,
  writeDefaultMode,
}, { getPonytailInstructions, filterSkillBodyForMode }, parsePonytailCommand(), ponytailExtension() (+8 more)

### Community 9 - "Community 9"
Cohesion: 0.08
Nodes (25): author, name, url, bugs, url, description, exports, ./plugin (+17 more)

### Community 10 - "Community 10"
Cohesion: 0.16
Nodes (20): getDefaultMode(), normalizeMode(), writeDefaultMode(), __dirname, frontmatterField(), parseCommandFile(), parseSkillFile(), { getDefaultMode, normalizeMode, writeDefaultMode } (+12 more)

### Community 11 - "Community 11"
Cohesion: 0.18
Nodes (15): build_injected_context(), _config_dir(), _default_mode(), _fallback_instructions(), _filter_skill_body_for_mode(), _handle_mode_command(), _make_skill_command_handler(), handler() (+7 more)

### Community 12 - "Community 12"
Cohesion: 0.17
Nodes (14): _cells(), _fixed_diff(), _gate_ok(), judge_reply(), main(), _pair_call(), pairwise(), one() (+6 more)

### Community 13 - "Community 13"
Cohesion: 0.13
Nodes (16): fs, getConfigDir(), getConfigPath(), getHideStatus(), getQoderDir(), getQuietStartup(), os, path (+8 more)

### Community 14 - "Community 14"
Cohesion: 0.13
Nodes (16): { DEFAULT_MODE, normalizeMode, normalizePersistedMode }, filterSkillBodyForMode(), fs, getFallbackInstructions(), getPonytailInstructions(), INDEPENDENT_MODES, path, SKILL_PATH (+8 more)

### Community 15 - "Community 15"
Cohesion: 0.18
Nodes (8): chat_code_loc(), code_stats(), _count(), git_diff_stats(), gz(), _is_test(), score_workspace(), _selfcheck_split()

### Community 16 - "Community 16"
Cohesion: 0.14
Nodes (11): fs, path, system, fs, path, system, assert, fs (+3 more)

### Community 17 - "Community 17"
Cohesion: 0.22
Nodes (15): isShellSafe(), fs, hooksPath(), install(), isPonytailHook(), { isShellSafe }, os, path (+7 more)

### Community 18 - "Community 18"
Cohesion: 0.12
Nodes (10): assert, fs, { isPonytailHook }, os, path, root, rootFwd, { spawnSync } (+2 more)

### Community 19 - "Community 19"
Cohesion: 0.21
Nodes (12): DESCRIPTIONS, fs, NAMES, outPath(), path, render(), ROOT, sourceBody() (+4 more)

### Community 20 - "Community 20"
Cohesion: 0.19
Nodes (14): Adapter: Claude Code plugin + hooks, Adapter: Codex plugin + hooks, Adapter: GitHub Copilot / Copilot CLI plugin, Adapter: pi extension, Adapter rule: keep host adapters thin, AGENTS.md compact always-on rules, Band task board + CSV ledger (optional), copilot-instructions.md (static rule copy) (+6 more)

### Community 21 - "Community 21"
Cohesion: 0.17
Nodes (12): assert, commands, { filterSkillBodyForMode }, fs, os, path, python(), pythonExe() (+4 more)

### Community 22 - "Community 22"
Cohesion: 0.20
Nodes (8): CHECKS, correctnessTimeoutMs(), exec(), { execSync }, fs, os, path, python()

### Community 23 - "Community 23"
Cohesion: 0.20
Nodes (10): writeHookOutput(), writeOut(), finish(), { getPonytailInstructions }, inject(), mode, { readMode, writeHookOutput }, vm (+2 more)

### Community 24 - "Community 24"
Cohesion: 0.18
Nodes (9): assert, check(), correctness, test, assert, fs, path, root (+1 more)

### Community 25 - "Community 25"
Cohesion: 0.17
Nodes (8): assert, fs, os, path, { pathToFileURL }, statePath, test, tmp

### Community 26 - "Community 26"
Cohesion: 0.17
Nodes (9): agents, canonical, copies, fs, INVARIANTS, path, root, skill (+1 more)

### Community 27 - "Community 27"
Cohesion: 0.18
Nodes (11): assert, fs, loadManifest(), path, read(), REUSED_COMMANDS, REUSED_SKILLS, root (+3 more)

### Community 28 - "Community 28"
Cohesion: 0.22
Nodes (9): BUDGET, buildMap(), { execFileSync }, fs, LANG, listFiles(), namesIn(), path (+1 more)

### Community 29 - "Community 29"
Cohesion: 0.18
Nodes (8): { createHash }, fs, { getClaudeDir, getQoderDir }, os, path, projectDir, stateDir, statePath

### Community 30 - "Community 30"
Cohesion: 0.18
Nodes (10): assert, commands, debtCopies, debtSamples, fs, path, piSource, root (+2 more)

### Community 31 - "Community 31"
Cohesion: 0.18
Nodes (8): assert, fs, HOST_PLUGIN_MANIFESTS, os, path, root, { spawn, execFileSync }, test

### Community 32 - "Community 32"
Cohesion: 0.27
Nodes (3): load(), main(), sign_p()

### Community 33 - "Community 33"
Cohesion: 0.20
Nodes (7): assert, { buildMap }, dir, fs, map, os, path

### Community 34 - "Community 34"
Cohesion: 0.20
Nodes (7): assert, fs, os, path, root, { spawnSync }, test

### Community 35 - "Community 35"
Cohesion: 0.20
Nodes (7): fs, passthrough, path, root, skillsDir, slugs, { spawnSync }

### Community 36 - "Community 36"
Cohesion: 0.22
Nodes (6): assert, fs, path, root, SKILL_DIRS, test

### Community 37 - "Community 37"
Cohesion: 0.29
Nodes (5): CHECKS, assert, behavior, check(), test

### Community 38 - "Community 38"
Cohesion: 0.29
Nodes (5): assert, cases, loc, score(), test

### Community 39 - "Community 39"
Cohesion: 0.25
Nodes (7): description, name, owner, name, url, plugins, $schema

### Community 40 - "Community 40"
Cohesion: 0.29
Nodes (7): distinct, fs, path, readVersion(), root, VERSION_FILES, versions

### Community 41 - "Community 41"
Cohesion: 0.25
Nodes (6): assert, fs, path, REQUIRED_COMMAND_FILES, root, test

### Community 42 - "Community 42"
Cohesion: 0.33
Nodes (5): Band, claude-code, PluginState, Tests, Tokens

### Community 43 - "Community 43"
Cohesion: 0.33
Nodes (5): name, private, scripts, test, type

### Community 44 - "Community 44"
Cohesion: 0.33
Nodes (5): assert, fs, path, root, test

### Community 45 - "Community 45"
Cohesion: 0.33
Nodes (5): assert, fs, path, root, test

## Knowledge Gaps
- **16 isolated node(s):** `RFC-4180`, `Smallest-complete-change ladder (6 steps)`, `Never-cut list (validation, security, data loss)`, `Skill: ponytail-review (diff review)`, `Skill: ponytail-audit (repo audit)` (+11 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 509 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **8 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Ponytail skill: lazy senior dev ruleset` connect `Community 14` to `Community 20`?**
  _High betweenness centrality (0.010) - this node is a cross-community bridge._
- **What connects `RFC-4180`, `Smallest-complete-change ladder (6 steps)`, `Never-cut list (validation, security, data loss)` to the rest of the system?**
  _16 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.06077630234933606 - nodes in this community are weakly interconnected._
- **Why does `getPonytailInstructions()` connect `Community 14` to `Community 1`, `Community 7`, `Community 8`, `Community 10`, `Community 23`?**
  _High betweenness centrality (0.009) - this node is a cross-community bridge._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.03125 - nodes in this community are weakly interconnected._
- **Why does `getDefaultMode()` connect `Community 10` to `Community 8`, `Community 1`, `Community 13`, `Community 7`?**
  _High betweenness centrality (0.005) - this node is a cross-community bridge._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.05084745762711865 - nodes in this community are weakly interconnected._