# Lattice Forge changelog

One short line per change. Newest first.

## 0.9.17 (2026-11-12)
- New: the Assistant, a chat that remembers you between conversations (Sessions ▸ New assistant chat).
- The Assistant keeps its memories and conversations in its own folder in your user folder.
- The Assistant can only use files in its own folder unless you allow more.
- When a conversation ends, the Assistant saves anything it missed remembering.
- Turning Private off asks whether to purge or keep what you wrote.
- Private mode: nothing from the conversation is saved, here or on the server.
- Choose the Assistant's context mode on its tab.
- The Assistant looks like a chat app.
- Turn the Internet on or off for each conversation.
- Re-roll a reply, or edit a message and send it again; earlier versions are kept.
- Conversations are saved automatically.
- Open an earlier conversation, or delete the ones you no longer need.
- Editing the context of a conversation keeps the earlier version.
- New: Help ▸ What's new.
- Change the text size and the app size (UI menu).
- Save the current session as a project (Projects menu).
- New session lets you pick the server.
- Send becomes Stop while a reply is being written.
- Ctrl+Enter queues a message.
- Big tasks continue in parts automatically.
- Big text attachments are read in parts instead of pasted.
- The model can read a whole file into notes.
- The context meter is more accurate.
- New: API Relay lets programs on this computer use your server (Server ▸ API Relay…).
- New: Minimize to tray.
- Start with --relay and --minimize.
- lattice run is replaced by the API Relay.
- Each computer gets its own security certificate for its server.
- Model settings say what each setting does.
- Model settings show the model's own default values.
- No reasoning setting on models that don't offer one.
- The online setup shows which version it will install.
- Update problems are reported automatically.
- Lattice-Lite shows the connection squares.
- Lattice-Lite says when the model is starting.
- Fixed: line breaks in messages.
- Fixed: reading some text files showed twice as many lines.
- Fixed: Send feedback promised attachments it could not add.
- The Lite downloader and the online setup identify themselves as installers, not as the app.
- An out-of-date downloader or online setup says so and tells you what to do.

## 0.9.16 (2026-11-01)
- See and remove the accounts saved on this computer (Account ▸ Saved sign-ins…).
- Fixed: Account ▸ Enroll this computer… closed the app.
- Fixed: Account ▸ Devices… wrongly said "ID does not match".

## 0.9.15 (2026-10-21)
- Long replies no longer lose the connection.
- If a reply is lost, the app says so plainly and offers Retry.
- Roles can work in the background while you keep chatting.
- Check on or cancel a role's background work.
- Roles can read files in your project.
- The app stops a model that keeps repeating the same actions.
- Claude Code and Codex can be used as roles.

## 0.9.14 (2026-10-15)
- The terminal chat and lattice run use tools only with models that support them.
- Pause and Resume are more reliable.
- A paused chat resumes only on the server, account and chat it came from.
- Send waits while a chat is being saved.

## 0.9.13 (2026-10-10)
- Use Claude or OpenAI with your own API key (Server ▸ API keys and spending…).
- Set a spending limit for each API key.
- Hand tasks to Claude Code or Codex on this computer (Agents menu).
- Claude Code and Codex only read your files unless you allow changes.
- Pause a long chat and resume it later, on servers that offer it.
- Roles: the chat model can hand work to other models, on any of your servers (Server ▸ Roles…).
- A model on another server can write the summaries of long chats.
- The setup program passes your enrollment straight to the app.
- Feedback the server can't accept now tells you why.
- Clearer Help, including the getting-started guide.

## 0.9.12 (2026-10-08)
- Shorter, plainer text throughout the app.
- Press F1 on any control or menu to open its Help page.
- A one-time tip about F1 for new accounts.

## 0.9.11 (2026-10-07)
- Write your own system prompt for every session.
- Give a project its own system prompt.
- An online installer that sets up the newest version with your enrollment code.

## 0.9.10 (2026-10-06)
- The app can shorten long conversations by itself.
- Choose which model writes conversation summaries (Server ▸ Summarizer model).
- Leaving Raw mode asks whether to keep its messages.
- Updates are more reliable.
- American spelling throughout.

## 0.9.9 (2026-10-04)
- A sharper connection indicator on each session's top row.

## 0.9.8 (2026-10-04)
- The app keeps the connection alive during long replies.
- A dropped connection is explained, with Retry.
- A status indicator shows each step of a reply.

## 0.9.7 (2026-10-02)
- Renamed to Lattice Forge, with a new icon.
- A setup program comes with every release.
- Settings moved to their own Lattice Forge folder.

## 0.9.6 (2026-10-01)
- Built-in Help with topics, search and links.
- A Getting started PDF.
- Plainer menu names and wording.
- The app offers setup when it starts with no server.
- Set up a second computer with a code from your first one.

## 0.9.5 (2026-10-01)
- The model can read part of a file, and search files.
- A turn too large for the server is explained instead of retried.
- The app tries the server's other addresses when one fails.
- Settings show one row per setting.
- Reasoning can be set to None or Auto.

## 0.9.4 (2026-09-24)
- Each computer gets its own sign-in.
- Automatic error reports.
- Send feedback from the app.
- Stop also cancels the work on the server.
- Procedure documents for Rehydrate, End session and standing rules.
- Sign in from the terminal.

## 0.9.3 (2026-09-21)
- Security fixes for updates, saved sign-ins and file tools.
- Setting up a computer is done in the desktop app only.

## 0.9.2 (2026-09-20)
- A banner offers new versions without blocking the app.
- Help ▸ About shows the version, build and server.
- Each tab names its server.
- Install an update from a file, without a network connection.

## 0.9.1 (2026-09-20)
- The app can update itself.

## 0.9.0 (2026-09-14)
- First release.
- The desktop app and the terminal chat.
- Set up a computer with an enrollment code.
- Raw context mode.
- The shared-priority bar.
