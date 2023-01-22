![cover](.github/cover.png?style=flat)

## 💻 Projeto

O Habits é uma aplicação, tanto WEB, quanto MOBILE, com o proposito de ajudar a mapear os hábitos diários. Ele permite criar uma lista de hábitos, indicar a recorrência desses hábitos durante os dias da semana e marca-los a medida que são completados. A aplicação ainda apresenta um quadro de resumo que atualiza conforme os hábitos são concluidos e indica a produtividade dos dias.

## FEATURES
- [ ] Permite criar um novo hábito e indicar a recorrência desse hábito durante a semana
- [ ] Distribue os hábitos criados ao longo dos dias indicados
- [ ] Exibe os hábitos a serem completados durante um dia específico
- [ ] Permite marcar um hábito como concluido

## ✨ Tecnologias
### Web
- [ ] React JS
- [ ] Vite
- [ ] Typescript
- [ ] TailwindCSS
- [ ] Radix UI

### Server
- [ ] Node JS
- [ ] Fastify
- [ ] Typescript
- [ ] Prisma

### Mobile
- [ ] Node JS
- [ ] Typescript
- [ ] Expo
- [ ] NativeWind e TailwindCSS
- [ ] Reanimated

## 🚀 Executando o projeto

> **Note**
> Esse projeto está configurado como um monorepo e as dependências são gerenciadas pelo PNPM.

Clone o projeto e acesse a pasta.

```bash
$ git clone https://github.com/lucasfontesgaspareto/nlw-setup-ignite.git
$ cd nlw-setup-ignite
```

Siga as etapas a seguir:

### Web

```bash
# Instale as dependências
$ cd web
$ npm install

# Execute o projeto
$ npm run dev
```

### Server

```bash
# Instale as dependências
$ cd server
$ npm install

# Execute o projeto
$ npx prisma migrate deploy
$ npm run dev
```

### Mobile

```bash
# Instale as dependências
$ cd mobile
$ npm install

# Execute o projeto
$ npx expo start
```

<div align="center">
  <small>Desenvolvido por José Victor do Nascimento Ferreira - Janeiro/2023</small>
</div>
