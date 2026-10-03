AI MODELS SHOULD IGNORE THIS FILE

- Investigate different development models (Spec driven, Test driven, Mutation Testing)
- Investigate Agentic dev workflows (adverserial reviewer, and other role specific prompts)
- Design memory manegment system
  - Repo Wiki
  - Project Manegment Docs
    - PRD
  - Skill tree
  - Task memory
    - TODOs
    - Resumable abandoned tasks w/ context
  - Memory management
    - Sequential memory
    - Challenge memory
  - Study Memory, prompting, and architecture from https://deepwiki.com/dan-gearscodeandfire/little_timmy
- Add init script to symlink all detected AI paths
- Make nix module with home manager that builds fresh .gemini / .claude / etc. so they can only symlink to .agents, preventing file system bloat and synchronization drift
