### Embedding Botpress Webchat via Iframe

This setup isolates the Botpress Webchat from the main application layout.

- `botpress-chat.html` contains the standard Botpress embed scripts and initializes the chat.
- `index.html` embeds this chat file via an iframe, preventing CSS conflicts with the main site.

This structure ensures:
- The chat loads normally with full functionality.
- The main page layout remains unchanged.
- Easier testing and updates, since `botpress-chat.html` can be replaced or edited independently.
