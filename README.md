# yume
![banner](https://i.postimg.cc/y8z3Dx0s/66.png)
yume simplifies the creation and deployment of intelligent, character-driven social media AI agents. Whether you're automating interactions, growing accounts, or building unique online personas, yume provides everything.


Follow us on X for updates and insights: [@YumeFramework](https://x.com/YumeFramework)

---


## Key Features
### Autonomous Engagement
- Creates relevant, original posts
- Responds intelligently to mentions and messages
- Smart filtering to prioritize meaningful interactions
- Ensures natural and fluid conversation flow
### Advanced Memory Management
- Persistent interaction history
- Context-aware responses
- Tracks relationships with other users
### Platform Integration
- Rate limiting and scheduling for seamless automation
- Natural posting patterns with random delays
- Full integration with Twitter API v2
### Modular and Scalable
- Decoupled core logic and integrations
- Extensible character trait system
- Pluggable provider framework
- Optimized memory usage for high performance
---
## Prerequisites
- Latest stable version of Rust
- API Keys:
  - Anthropic Claude API
  - Twitter API v2 credentials (OAuth 1.0a)
---
## Installation
1. Clone the repository:
```bash
git clone https://github.com/YumeAgentCreation/Yume
cd Yume
```
2. Create a `.env` file with the required credentials:
```env
ANTHROPIC_API_KEY=your_api_key
TWITTER_CONSUMER_KEY=your_key
TWITTER_CONSUMER_SECRET=your_secret
TWITTER_ACCESS_TOKEN=your_token
TWITTER_ACCESS_TOKEN_SECRET=your_token_secret
CHARACTER_NAME=your_character_name
```
3. Set up your character:
   - Create a new directory: `characters/{CHARACTER_NAME}/`
   - Add the character definition in `character.json`
## Character Configuration
Define characters in a structured JSON format:
```json
{
  "instructions": {
    "base": "Base character instructions",
    "suffix": "Additional instructions"
  },
  "adjectives": ["trait1", "trait2"],
  "bio": {
    "headline": "Character headline",
    "key_traits": ["trait1", "trait2"]
  },
  "lore": ["background1", "background2"],
  "styles": ["style1", "style2"],
  "topics": ["topic1", "topic2"],
  "post_style_examples": ["example1", "example2"]
}
```
## Usage
Run the agent:
```bash
cargo run
```
   ```bash
   git clone https://github.com/yourusername/yume
   cd Aoi
## Contributing
Contributions are welcome! If you have ideas for improving yume, feel free to fork the repository, make changes, and submit a pull request.
