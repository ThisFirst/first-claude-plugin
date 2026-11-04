# First

First helps engaged couples in the US make a prenup (a prenuptial agreement) together. This plugin connects Claude to First.

Ask general questions, such as "Do I need a prenup?" or "What does a prenup cover?", and get answers from Clara, the First assistant. Continue your prenup in Claude: answer the questions of each module, add your assets and family members, review the choices of you and your partner, read your agreement and documents, and see what to do next. Payment, signing, and the lawyer review stay in the First app.

First gives general information, not legal advice.

## What the plugin contains

- The First MCP server, `https://mcp.thisfirst.com/mcp`. The plugin connects to no other server.
- The `get-started` skill. It tells Claude when to use First and which tool to call first.

The plugin runs no code on your computer.

## What the plugin sends to First

- **Before you sign in:** only `ask_clara` works. It sends your question to First. First keeps the question and the answer.
- **After you sign in:** you sign in to your First account, or make one, with OAuth, and you accept the First consent page. Claude then sends the data of each tool call to First, for example your answers, your assets, and your family members. First keeps this data in your account.

First does not get your whole chat, only what Claude sends in a tool call. To disconnect, go to **Connected AI assistants** in the account menu of the First app.

## Links

- Website: https://www.thisfirst.com
- Privacy policy: https://www.thisfirst.com/privacy-policy
- Terms of service: https://www.thisfirst.com/terms-of-service
- Support: heretohelp@thisfirst.com

## License

MIT. See [LICENSE](LICENSE).
