# VS Code + Claude Live Demo
## Pittsburgh Boot Camp — Day 1 Implementation Block

---

## INTRO VIDEO — PLAY BEFORE THE DEMO

**File:** `build-something-real.mp4`

Play it as the transition into the Implementation Block — right after lunch ends, before you say a word. Let the video do the mood-setting. When it ends, you walk on screen and say:

*"That's what the next 90 minutes looks like. Let's go."*

Then open VS Code.

---

## THE SETUP

You're on screen. VS Code open. Claude Code running in the terminal.
The audience picks the business. You build it live.

That's the whole demo.

---

## WHAT THE AUDIENCE SEES

1. A blank VS Code window
2. You open the terminal
3. You type one sentence
4. Claude builds a complete working website
5. You open it in the browser
6. The room loses their mind

Total time: 8–12 minutes from blank screen to live webpage.

---

## THE SCRIPT

### Opening (30 seconds, before touching the keyboard)

"I want to show you something. No prep. No pre-built files.
I'm going to ask someone in the room for their business.
And by the time we're done, they're going to have a working website.

Who's got a business?"

[pick someone — get: business name, what they do, one thing they want visitors to do]

---

### The Build (live, on screen)

**Step 1 — Open VS Code terminal**
```
cd ~/Desktop
mkdir [business-name] && cd [business-name]
```

**Step 2 — Launch Claude Code**
```
claude
```

**Step 3 — The prompt (type this live, out loud, slowly so the room hears every word)**

```
Build me a single-page business website for [Business Name].

They are a [what they do] based in Pittsburgh.
The main thing they want visitors to do is [their goal — call, book, buy, contact].

Make it:
- Clean, modern, dark background
- Mobile friendly
- One clear headline that explains what they do
- A short paragraph about the business
- A big call-to-action button
- A contact section with a phone number placeholder

Save it as index.html. Make it look professional — not like a template.
```

**Step 4 — Let Claude work. Don't touch anything. Let the room watch.**

Narrate while it builds:
- "Watch what it's doing — it's writing the HTML..."
- "Now the CSS — see how it's styling the layout..."
- "It knows to make it mobile-friendly without being asked..."

**Step 5 — Open the file**
```
open index.html
```

**Step 6 — Show the result full screen**

---

### The Moment (after the browser opens)

Turn to the person whose business it is.

"Is that your business?"

[they say yes]

"How long would that have taken you to build?"

[let them answer]

"Claude did it in [X] minutes. And you own it. You can deploy it today."

---

### The Follow-Up Prompt (optional — if the room wants more)

"Let's say they want to change the color scheme. Watch this."

```
Change the color scheme to navy blue and gold.
Add a testimonials section with three placeholder reviews.
```

Show the update in real time.

---

### The Close

"Everything you just watched — that's Claude Code running inside VS Code.
Free to use. Works on your Mac mini.
You're going to do exactly this in the next 60 minutes.
And you're going to leave today with something that works."

---

## TECHNICAL REQUIREMENTS

- VS Code installed and open before the demo
- Claude Code authenticated (`claude` command works in terminal)
- Terminal font size: 18pt minimum (readable from back of room)
- VS Code font size: 18pt minimum
- Browser ready to open (Chrome or Safari, full screen)
- Internet connection confirmed working
- **Backup plan:** Screenshot sequence of a pre-run demo if internet fails

---

## WHAT TO HAVE READY BEFORE THE DEMO

- VS Code open, blank window, terminal panel visible
- Claude Code logged in and ready
- Font sizes bumped up
- All notifications off (Do Not Disturb on)
- Desktop clean — no distracting icons or files

---

## WHY THIS DEMO WORKS

The audience isn't watching someone code.
They're watching someone talk to a computer — in plain English — and get a real result.

That's the insight they came for.

Not "how do I learn to code."
"Oh. I don't have to."
