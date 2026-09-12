# 🧠 Content AI Partner

Your AI content creation assistant. Upload videos, get detailed feedback, spin an idea wheel, and plan your content calendar.

## Features

### 1. 📹 Video Analysis
Upload raw clips, finished Reels/TikToks, or batch uploads. The AI analyzes:
- Hook effectiveness (first 1–3 seconds)
- Pacing and dead sections
- Exercises/activities shown
- Camera angles and composition
- Your delivery and personality
- Funny moments for gags
- Ending engagement (does it make people comment/follow?)
- Repetitive elements

**Example feedback:**
```
Hook: 6/10
You take ~3 seconds before anything interesting happens. 
Start with the failed rep, then cut to the setup.

Best moment: 0:17–0:21
That's the bit I'd build the Reel around.

Fix: Cut 4 seconds from the middle and add a reaction shot after the set.
```

### 2. 🎡 Idea Wheel
Spin the wheel and get a complete video concept:
- **Categories:** Weekly Challenge, Day-in-the-life, Gym experiment, Comedy/gag, Strength challenge, Rugby × Gym, Progress series, Educational, With a mate, Viewer challenge, Gym interviews
- **Smart tracking:** Remembers everything you've posted to avoid recycling ideas
- **Complete packages:** Hook, gags, structure, ending, and CTA

**Example spin output:**
```
🎡 THIS WEEK'S VIDEO
Category: Gym Challenge
Challenge: Let the wheel decide your entire workout

Hook: "Today I'm letting this wheel decide everything I do in the gym."

Gags:
- Wheel lands on an absolutely horrible exercise
- Dramatic reaction
- Fake confidence before attempting it
- Running joke throughout the video

Ending: "If this gets 100 comments, I'm letting the wheel choose next week's workout."
```

### 3. 📅 Content Calendar
Plan your week with smart recommendations:
- **Default schedule:** Monday (Day-in-the-life), Wednesday (Gym gag), Friday (Challenge), Sunday (Wheel decides)
- **Smart detection:** Alerts you if you're posting too many similar videos
- **Contextual suggestions:** "You've posted 3 training videos recently. Let's NOT make another standard workout montage. Next video: 'I let strangers design my gym workout.'"

### 4. 🎯 Personalized Content Brain
Tell the AI "I want this to feel like me" and it learns:
- Your humor style
- Editing preferences
- Music choices
- Video length
- Hook style
- Recurring jokes
- Filming style
- Gym/rugby crossover elements
- Things you don't want to do

**End goal:** Ask "I've got gym at 6. Give me something to film." and get a complete video concept with shot list, script, jokes, hook, thumbnail idea, and ending.

## Tech Stack (Planned)

- **Backend:** Python (FastAPI)
- **Video Analysis:** OpenAI Vision API / FFmpeg
- **Database:** PostgreSQL
- **Frontend:** React + TypeScript
- **Deployment:** Docker + GitHub Actions

## Roadmap

### Phase 1: MVP (Video Analysis)
- [ ] Video upload infrastructure
- [ ] Frame extraction and analysis
- [ ] Hook detection (first 3 seconds)
- [ ] Pacing analysis
- [ ] Basic feedback generation
- [ ] CLI tool for testing

### Phase 2: Idea Wheel & Calendar
- [ ] Idea Wheel spinner logic
- [ ] Content history tracking
- [ ] Calendar scheduling
- [ ] Smart deduplication
- [ ] Web dashboard

### Phase 3: Personalization
- [ ] User preference learning
- [ ] Content brain customization
- [ ] Personalized recommendations
- [ ] Complete shot list generation

### Phase 4: Polish & Scale
- [ ] Video editing integration
- [ ] Thumbnail generation
- [ ] Analytics tracking
- [ ] Mobile app
- [ ] Community features

## Getting Started

(Coming soon)

## Contributing

Contributions welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License - see [LICENSE](LICENSE) for details.
