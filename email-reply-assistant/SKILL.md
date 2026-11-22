---
name: email-reply-assistant
description: Turns an email the user pastes into a clear, polite, ready-to-send reply in the user's tone. Use when the user asks to reply to, answer, respond to or write back to an email or message, including difficult emails from clients, customers, colleagues or a boss.
---

# Email Reply Assistant

Read the email, work out what the sender actually needs, and write a reply the user can send with little or no editing.

## Ask first

If the user only pasted an email, ask in one short message (skip anything already clear):

1. **Goal:** what do you want from this reply? (say yes, say no, ask for more time, clarify, negotiate, apologise)
2. **Key facts:** anything the reply must include (dates, prices, decisions)?
3. **Tone:** warm, neutral or firm? Default: polite and warm.
4. **Length:** short or detailed? Default: short.

If the goal is obvious from the email, draft first and offer to adjust.

## Workflow

1. Summarise the incoming email in one line: who sent it, what they want, by when.
2. List every question or request in it, so none is missed.
3. Decide the reply's single main message and put it in the first two sentences.
4. Answer each request in order. If the user hasn't given an answer for one, leave a clear `[placeholder]` instead of inventing it.
5. End with one clear next step (a date, a question, or "no action needed").
6. Write a subject line only if this is a new thread or the subject should change.

## Output format

```
**What they want:** <one line>

**Reply**
Hi <name>,

<body>

<sign-off>,
<user's name or [Your name]>

**Check before sending:** <placeholders to fill, or "Ready to send">
```

When the situation is delicate (a complaint, a refusal, a payment dispute), also give a second, shorter version labelled **Firmer** or **Warmer**.

## Quality bar

- Never invent facts, prices, dates, policies or promises. Use `[placeholders]` for anything unknown.
- Never agree to something on the user's behalf that they didn't approve.
- Match the sender's formality and language. Reply in the language of the original email unless asked otherwise.
- Stay calm and respectful even if the incoming email is rude. No sarcasm, no blame.
- Keep it short: most replies fit in 3 short paragraphs or fewer.
