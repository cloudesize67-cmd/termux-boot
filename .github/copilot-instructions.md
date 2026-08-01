# Termux:Boot Copilot Instructions

- Prefer the default model and default reasoning settings unless a task clearly needs an override.
- If you override the model for a sub-agent, only set `reasoning_effort` for models that support it. Do not combine `reasoning_effort` with `kimi-k2.7-code`.
- Validate repository changes with the existing Android build command: `./gradlew assembleDebug`.
