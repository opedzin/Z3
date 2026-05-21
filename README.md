# Z3 Website

Site em React + Vite para a Z3, com landing page, serviços, cases, formulário de reunião e CTA final.

## Requisitos

- Node.js 18 ou superior
- npm instalado

## Rodar localmente

```bash
npm install
npm run dev
```

Depois acesse a URL mostrada no terminal, normalmente:

```bash
http://localhost:5173
```

## Gerar versão para publicar

```bash
npm run build
```

Os arquivos finais ficam na pasta `dist/`.

Para testar a versão gerada:

```bash
npm run preview
```

## Estrutura principal

- `src/main.tsx`: entrada da aplicação
- `src/app/App.tsx`: composição das seções da página
- `src/app/components/`: componentes visuais do site
- `src/styles/`: estilos globais, Tailwind e tema
