![BotBox Banner](https://raw.githubusercontent.com/Ziqx/botbox/main/banner.png)

# BotBox

BotBox is an open-source app designed for exploring various AI chatbots and staying updated with the latest articles related to AI. It provides a collection of AI chatbots, including ChatGPT and Google Bard, and a curated list of articles in the AI field. The app encourages community participation, allowing users to contribute to the bots' data and the articles feed.

## Features

- Explore and interact with AI chatbots like ChatGPT, Google Bard, and more.
- Stay up to date with the latest articles on AI from various sources.
- Open-source project where users can contribute to the bots' data and the articles feed.

## Installation

Clone/Fork the repository: 
```sh
git clone https://github.com/Ziqx/botbox.git
```
[![Fork](https://img.shields.io/github/forks/Ziqx/botbox?label=Fork%20Now&style=for-the-badge)](https://github.com/Ziqx/botbox/fork)

## Contributing

We welcome contributions from the community to enhance the app and keep it up to date. To contribute, please follow these guidelines:

### Contributing to Bot Data

1. Bot data is stored in the `data.json` file.
2. To add a new bot, open `data.json` and follow the existing format:

```json
{
  "name": "Bot Name",
  "icon": "bot-icon.png",
  "link": "https://bot-website.com"
}
```
3. Place the bot icon in the `/icons` folder.
4. Submit a pull request with your changes.

## Contributing to Feeds
1. Feeds data is stored in the `feeds/data.json` file.
2. To add a new article to the feed, open `feeds/data.json` and follow the existing format:
```json
{
  "title": "Article Title",
  "author": "Author Name",
  "link": "https://article-link.com",
  "thumb": "https://link-to-thumbnail.com/thumb.jpg",
  "category": "Machine Learning"
}
```
3. Submit a pull request with your changes.

## License
This project is licensed under the MIT License.

## Contact
If you have any questions or suggestions regarding **BotBox**, feel free to contact us at _fathah@ziqx.in_.
