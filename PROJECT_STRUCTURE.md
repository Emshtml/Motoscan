motoscan-ai/
├── README.md           # Descrição do projeto, badges, instalação
├── LICENSE             # Licença MIT
├── package.json        # Dependências e scripts
├── tsconfig.json       # Configuração TypeScript
├── public/
│   ├── index.html      # HTML base
│   └── logo.png        # Logo do projeto
├── src/
│   ├── App.tsx         # Componente principal
│   ├── index.tsx       # Entry point React
│   ├── assets/
│   │   └── icons/      # Ícones do dashboard e scanner
│   ├── components/
│   │   ├── ui/         # Botão, Card, Input
│   │   └── charts/     # Gráficos em tempo real
│   ├── pages/
│   │   ├── Dashboard.tsx
│   │   ├── Scanner.tsx
│   │   ├── History.tsx
│   │   └── Reports.tsx
│   ├── hooks/
│   │   └── useBluetooth.ts
│   ├── lib/
│   │   └── diagnostics.ts
│   └── styles/
│       └── globals.css
└── tests/
    ├── diagnostics.test.ts
    └── ui.test.tsx
