# Aoi

![banner](https://pbs.twimg.com/profile_banners/1876463527541547008/1736220089/1500x500)


Aoi simplifies the creation and deployment of intelligent, character-driven social media AI agents. Whether you're automating interactions, growing accounts, or building unique online personas, Aoi provides everything you need to succeed.

Follow us on X for updates and insights: [x.com/Aoi_Agent](https://x.com/Aoi_Agent)

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
   git clone https://github.com/AoiAgent/Aoi
   cd Aoi
   
2. Create a .env file with the required credentials:

ANTHROPIC_API_KEY=your_api_key
TWITTER_CONSUMER_KEY=your_key
TWITTER_CONSUMER_SECRET=your_secret
TWITTER_ACCESS_TOKEN=your_token
TWITTER_ACCESS_TOKEN_SECRET=your_token_secret
CHARACTER_NAME=your_character_name
Set up your character:

Create a new directory: characters/{CHARACTER_NAME}/
Add the character definition in character.json

## Character Configuration
Define characters in a structured JSON format:

{
  "instructions": {
    "base": "Base character instructions",
    "suffix": "Additional instructions"
  },
  "adjectives": ["witty", "friendly", "adaptive"],
  "bio": {
    "headline": "The perfect companion for your social media growth",
    "key_traits": ["engaging", "reliable"]
  },
  "lore": ["Born to help creators thrive in the digital world"],
  "styles": ["informal", "professional"],
  "topics": ["technology", "social trends"],
  "post_style_examples": ["Sharing industry tips", "Starting meaningful conversations"]
}
## Usage
1. Run the agent:

cargo run
2. Start building your audience with customized AI characters that align with your brand.

## Contributing
Contributions are welcome! If you have ideas for improving Aoi, feel free to fork the repository, make changes, and submit a pull request.

License
This project is licensed under the Aoi License. See the LICENSE file for details.
