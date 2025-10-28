# Support Bot Frontend

A React-based helpdesk chat interface built with Vite and modern UI components.

## Features

- Real-time chat interface
- Modern UI components using Tailwind CSS
- Message bubbles with avatar support
- Loading states with spinner animation
- Service-based architecture

## Screenshots

### Chat Interface
![Chat Interface](/public/screenshots/chat-interface.png)

### Chat Home
![Chat Home](/public/screenshots/chat-home.png)

> Note: To add your screenshots:
> 1. Take screenshots of your application
> 2. Save them in the `/public/screenshots` folder
> 3. Name them `chat-interface.png` and `chat-home.png` respectively
> 4. Commit and push them to see them displayed here

## Tech Stack

- React with Vite
- Shadcn UI (Component Library)
- Tailwind CSS
- UUID for unique identifiers

## Project Structure

```
src/
├── components/
│   └── ui/
│       ├── avatar.jsx
│       ├── button.jsx
│       ├── card.jsx
│       ├── input.jsx
│       ├── MessageBubble.jsx
│       ├── scroll-area.jsx
│       ├── separator.jsx
│       └── spinner.jsx
├── pages/
│   ├── Chat.jsx
│   └── ChatHome.jsx
├── services/
│   └── chat.service.js
└── lib/
    └── utils.js
```

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/kumargourav07/support-bot-frontend.git
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

## Development

The project uses Vite as the build tool and development server. Two official Vite plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

The main scripts available are:

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details
