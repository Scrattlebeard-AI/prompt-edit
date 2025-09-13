# Prompt Edit

A prompt editing PWA with planned LLM-powered features via WebGPU and Transformers.js.

## Stack

- Vite
- React 18
- TypeScript
- Monaco Editor
- Zustand
- PWA-ready

## Setup

```bash
npm create vite@latest . -- --template react-ts
npm install
npm install @monaco-editor/react zustand @radix-ui/themes
npm install -D @types/node vite-plugin-pwa
```

## Development

```bash
npm run dev     # Start dev server
npm run build   # Build for production
npm run preview # Preview production build
```

## Structure

```
src/
├── components/     # UI components
│   ├── Editor/
│   ├── Sidebar/
│   └── Layout/
├── lib/           # Core logic
│   ├── stores/    # Zustand stores
│   ├── types/     # TypeScript types
│   ├── ml/        # Future LLM features
│   └── utils/
└── App.tsx
```

## Roadmap

- [ ] Basic prompt editor with Monaco
- [ ] Prompt templates and variables
- [ ] PWA installation
- [ ] Local storage persistence
- [ ] WebGPU model loading
- [ ] Transformers.js integration
- [ ] ONNX runtime support

## License

Apache-2.0
