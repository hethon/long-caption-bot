# long-caption-bot
Free users can't send captions longer than 1024 characters, while Premium users can go up to 4096. Any message sent by a Premium user can be forwarded or copied to anyone, including free users. This means media with a long caption can reach free users without restriction. This bot leverages that to let anyone effectively send long captions.

## How It Works

1. User sends media.
2. User replies to the media with the text they want as a caption.
3. Bot posts the media with the text as a caption in a bot-controlled Telegram channel via a Premium account.
4. Bot copies the resulting message back to the user.

### to-do
- support caption for media group (we can check media_group_id in a small timeframe to bind the pack together)