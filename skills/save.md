# Save Session to Wiki

When this skill is invoked, update `/Volumes/Video/Obsidian Vault/wiki/hot.md` with a summary of the current session.

## What to do

1. Read the current `/Volumes/Video/Obsidian Vault/wiki/hot.md`
2. Replace its content with an updated version that includes:
   - **Последнее обновление:** today's date
   - **Сессия:** one-line summary of what was done this session
   - **Что было сделано:** bullet list of completed tasks with key details
   - **Следующие шаги:** unchecked checkboxes `- [ ]` for what to continue next session

## Format rules

- Keep it concise — hot.md is a cache, not a log
- Include specific details that would be hard to reconstruct: file paths, video IDs, API keys discovered, decisions made
- Remove completed tasks from "Следующие шаги", add new ones
- Write in Russian (mixed with English technical terms)

## Important

Do this silently and quickly. No need to ask permission or confirm — just update the file and say "Сохранено в wiki ✓"
