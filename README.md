# Sakhi (सखी · தோழி · సఖి) — a voice-first guide to government services

**Problem:** 48% of rural girls in India have never used the internet. Women are locked out of digital systems by design, not by capability.

**Solution:** Sakhi is a talking guide that needs no English, no typing, no account and no prior digital skill. She speaks, listens, and walks a woman through one real-world step at a time.

## How a first-time user experiences it
1. The first screen shows only big buttons with language names in their own script. Tap one and Sakhi greets her by voice.
2. Sakhi asks aloud: "What do you need?" She presses the big red mic and **speaks** ("bank", "इलाज", "வங்கி", "ఆరోగ్యం"), or taps a big picture card.
3. Sakhi reads **one short step at a time** (what to carry, where to go, exactly what to say, what she will get). "Listen again" and "Back" are always one tap away.
4. The last step reminds her to ask her Anganwadi / ASHA didi, so help comes from a trusted woman nearby.

## Services included
- **Bank account** (Pradhan Mantri Jan Dhan Yojana): zero-balance account, Aadhaar is enough.
- **Health card** (Ayushman Bharat PM-JAY): free treatment up to Rs 5 lakh per family per year. Helpline 14555.

## Languages
Hindi, Tamil, Telugu, English. Voice matching works across languages, so a word in any of them is understood.

## Design choices for zero digital knowledge
- Voice in, voice out. Text is only a backup.
- Huge touch targets, one decision per screen, no menus, no login, no typing.
- Phone numbers are spoken digit by digit so they are easy to follow.
- No server, no API key, no data collected. Runs fully in the browser, so her questions stay private.

## Run it
Open `index.html` in Chrome on Android or desktop. Voice features use the browser's built-in speech tools (Chrome recommended). If voice is unavailable, the screen still shows everything in text.

## Add a language or service
All content is in the `L` object at the top of the script in `index.html`. Copy one language block, translate it, and add its speech code (for example `kn-IN`).

## Honest limits and next steps
- Scheme rules and availability vary by state (for example, some states run their own health schemes). Verify with a local helper before relying on a step.
- Next: more services (ration card, Ladli/maternity benefits, skill courses), WhatsApp and missed-call versions for feature phones, and an AI layer for open-ended questions.
