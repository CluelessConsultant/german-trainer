# German Trainer

A German course for adult learners, from A1 to C1. I built it because I need German for work in Germany, and I use it every day. It has 3 learners so far.

**Try it:** [deutschlehrer777.streamlit.app](https://deutschlehrer777.streamlit.app/)

## What is in it

- **Grammatik:** 78 grammar rules from A1 to C1, each with a short quiz, and a verb conjugator. I checked the rules against a telc B2/C1 sample exam and the Klett textbooks B1 to C1.
- **Lesen:** articles from Zeit, Spiegel, Handelsblatt and WirtschaftsWoche instead of textbook sentences.
- **Hören:** native-speed podcasts such as Deutschlandfunk "Der Tag" and Easy German.
- **Schreiben:** writing tasks by level, with feedback.
- **Sprechen:** topics and questions for practice with a partner.
- **Vokabeln:** your own word list, with pronunciation.
- **Korrektur:** paste any German text and get it corrected, with a short reason for each mistake.

A translation box sits in the sidebar on every tab.

## How it is built

- Python and Streamlit
- The Anthropic Claude API for quizzes, corrections and feedback
- Supabase (Postgres) for learners' vocabulary and progress
- Amazon Polly for pronunciation

I built it with AI-assisted development (Claude Code).
