# 😤 Ughh AI

> AI hype, meet reality - Satirical AI memes for the tech community

[![Instagram Follow](https://img.shields.io/badge/Instagram-@ughh__ai-E4405F?style=flat&logo=instagram)](https://instagram.com/ughh_ai)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Vibes](https://img.shields.io/badge/vibes-chaotic_neutral-purple.svg)]()

---

## 🎭 About

**Ughh AI** is a satirical content brand that cuts through AI hype with dry humor, brutal honesty, and relatable tech culture commentary. We create Instagram memes that tech workers actually send to their co-workers.

No fluff. No motivational BS. Just the reality of working in tech during the AI gold rush.

**Target Audience:** Developers, tech workers, startup employees who are tired of AI hype

---

## 🎯 What We Do

### Content Pillars

| Theme | Description | Example |
|-------|-------------|---------|
| **AI Hype vs Reality** | The gap between marketing and reality | "GPT-5 will replace developers" vs reality: Copy-pasted StackOverflow |
| **Coding Culture** | Developer life, debugging hell, legacy code | "Refactoring" = commenting out old code |
| **Tech Layoffs** | Silicon Valley's hiring/firing cycle | Hired 100 engineers. Fired 100 engineers. "Efficiency gains" |
| **Startup Culture** | VC funding, pivots, "disruption" | Raised $10M Series A. Spent $9M on office snacks |
| **CEO Contradictions** | Leadership hypocrisy | Monday: "We're family" Friday: Layoffs via Zoom |
| **AI Ethics** | Environmental impact, data privacy | Training one model = carbon footprint of 5 cars for a year |
| **Work-Life Balance** | Hustle culture, burnout, crunch | "Optional weekend hackathon" (manager will judge you) |

### Format

- **Square images** (1080×1080px) optimized for Instagram
- **Bold text** on solid backgrounds (usually black)
- **Minimal design** - text is the star
- **Punchline delivery** - setup → punchline structure
- **No hashtags** - organic reach only

---

## 🎨 Visual Style

### Design Principles

```
┌─────────────────────────┐
│                         │
│    BOLD STATEMENT       │
│    IN ALL CAPS          │
│                         │
│    Dry punchline below  │
│    in smaller text      │
│                         │
└─────────────────────────┘
```

**Colors:**
- Primary: Black background (#000000)
- Text: White (#FFFFFF)
- Accents: Minimal (red for emphasis)

**Typography:**
- Font: Inter, Helvetica, SF Display (system fonts)
- Size: 64-68pt for main text
- Weight: Regular to Bold depending on tone
- Line spacing: 40px for readability

**Tone Mapping:**
| Tone | Font | Use Case |
|------|------|----------|
| Dry irony | Inter Regular | Multi-line jokes, observations |
| Authority | Helvetica Bold | Statements, declarations |
| Sarcastic | Courier | Code references, tech parody |

---

## 📱 Example Posts

### 1. AI Hype vs Reality
```
CEO: "Our AI will revolutionize healthcare"

The AI:
if temperature > 100:
    print("You might be sick")
```

### 2. Tech Layoffs
```
MONDAY:
"We're a family here"

FRIDAY:
Mass layoff email at 8 AM
```

### 3. Startup Culture
```
Raised $50M Series B

$45M went to:
- Ping pong tables
- Kombucha on tap
- "Chief Vibes Officer"

Product: Still in beta
```

### 4. CEO Contradictions
```
Company value: Transparency

Also company:
"We can't discuss compensation"
"Layoffs? What layoffs?"
"Trust us"
```

### 5. Work-Life Balance
```
Job posting:
"Passionate rockstar ninja wanted"

Translation:
Work 80 hours/week
Get paid for 40
No equity
Pizza Fridays tho
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Image Generation** | Python + Pillow (PIL) |
| **Caption Writing** | Claude Sonnet 4.5 |
| **Content Scheduling** | Custom queue system |
| **Posting** | Manual (Instagram limitations) |
| **Design Automation** | Dynamic text rendering, auto-wrapping |
| **Language** | Python 3.8+ |

---

## 📋 How It Works

```
┌──────────────────┐
│  Claude Sonnet   │
│  (Generate Joke) │
└────────┬─────────┘
         │
         v
┌──────────────────┐
│  Joke Validator  │
│  (Check tone)    │
└────────┬─────────┘
         │
         v
┌──────────────────┐
│  Image Generator │
│  (Pillow/PIL)    │
└────────┬─────────┘
         │
         v
┌──────────────────┐
│  Export Manager  │
│  (Save 1080x1080)│
└────────┬─────────┘
         │
         v
┌──────────────────┐
│  Manual Review   │
│  (Instagram post)│
└──────────────────┘
```

---

## 🎯 Content Philosophy

### What We Are
- ✅ Satirical but accurate
- ✅ Relatable to tech workers
- ✅ Brutally honest
- ✅ Observational humor
- ✅ Dry and deadpan

### What We're Not
- ❌ Mean-spirited
- ❌ Punching down at individuals
- ❌ Motivational fluff
- ❌ Engagement bait
- ❌ Over-explained jokes

### The Ughh AI Voice

**Tone:** Exhausted tech worker who's seen it all

**Perspective:** Inside the industry, calling out the BS

**Humor Style:** Dry, observational, slightly cynical but not bitter

**Example:**
> "Just another day pretending AI will solve problems that are actually about communication and management" — that's our vibe

---

## 🚀 Setup & Usage

### Prerequisites
- Python 3.8+
- Pillow (PIL)
- Anthropic API key (for caption generation)

### Installation

```bash
# Clone repository
git clone https://github.com/yourusername/ughh-ai

# Install dependencies
pip install pillow anthropic python-dotenv

# Configure
cp .env.example .env
# Add your ANTHROPIC_API_KEY
```

### Generate a Meme

```bash
# Generate with random topic
python engines/meme_generator.py --brand ughh_ai

# Generate with specific topic
python engines/meme_generator.py --brand ughh_ai --topic "AI hype"

# Generate batch
python engines/meme_generator.py --brand ughh_ai --batch 5
```

### Output

```
outputs/20260127_143022_ai_hype/
├── meme.png              # 1080x1080 Instagram-ready
├── caption.txt           # Suggested caption
├── metadata.json         # Generation info
└── README.md             # Post instructions
```

---

## 📁 Project Structure

```
ughh_ai/
├── config.json              # Brand settings
├── captions.md              # Caption library
├── rankings.json            # Post performance data
├── output/                  # Generated memes
└── README.md                # This file
```

---

## 📊 Performance Metrics

| Metric | Target |
|--------|--------|
| **Posts/Week** | 10-15 |
| **Avg. Saves** | 50+ |
| **Engagement Rate** | 8-12% |
| **Follower Growth** | 100-200/week organic |

**Why it works:** Tech workers share relatable content that makes them feel seen.

---

## 🎓 Content Strategy

### Weekly Mix
- **Monday**: Work-life balance meme (start of week pain)
- **Tuesday-Thursday**: AI hype, coding culture, or startup nonsense
- **Friday**: Tech layoffs or CEO contradictions (end-of-week catharsis)
- **Weekend**: Lighter content or AI ethics

### Avoid
- Trending topics just for virality
- Overused meme formats
- Political takes (keep it tech-focused)
- Engagement bait ("Tag a PM who...")

### Best Performers
1. **Relatable pain points** (debugging, meetings, legacy code)
2. **Hypocritical leadership** (CEO says X, does Y)
3. **AI hype deflation** (marketing vs reality)
4. **Startup culture absurdity** (ping pong tables > salaries)

---

## 🔧 Configuration

Edit `config.json`:

```json
{
  "content_pillars": [
    "AI hype vs reality",
    "Coding culture",
    "Tech layoffs"
  ],
  "image_settings": {
    "width": 1080,
    "height": 1080,
    "font_size": 68,
    "background_color": "#000000",
    "text_color": "#FFFFFF"
  }
}
```

---

## 📈 Roadmap

- [x] Automated meme generation
- [x] Custom font support
- [x] Multi-tone text rendering
- [ ] Instagram API integration (when available)
- [ ] A/B testing captions
- [ ] Reels/video format
- [ ] Cross-post to Twitter
- [ ] Community submissions

---

## 🤝 Contributing

Have a brutal tech observation? Submit ideas:
- Open an issue with your joke/observation
- Keep it relatable and accurate
- Avoid punching down
- No hate speech or discrimination

---

## 📄 License

MIT License - See LICENSE file for details

---

## 🔗 Links

- **Instagram**: [@ughh_ai](https://instagram.com/ughh_ai)
- **Examples**: [See output/](output/)

---

## 💡 Why We Exist

Tech deserves honest commentary. AI hype is exhausting. Startup culture has lost its mind. We're here to call it out, one meme at a time.

For tech workers, by tech workers. 😤

---

Made with 😤 and honesty
