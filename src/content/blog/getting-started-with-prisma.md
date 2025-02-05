---
author: Jesse De Lira
pubDatetime: 2025-01-27T12:00:00.000Z
title: Getting Started with Prisma
slug: "getting-started-with-prisma"
featured: true
ogImage: ../../assets/images/AstroPaper-v4.png
tags:
  - database
  - prisma
  - bun
  - typescript
description: "Getting Started with Prisma using Bun"
---

Hot new platform? Niche corner of the internet? Or one specific to your area? This post will guide you through how to add a new social icon to the theme.

## Table of contents

# Getting Started with Prisma using Bun

## What is Prisma?

Prisma is an open-source database toolkit for Node.js and TypeScript. It provides a modern database client, easy schema management, and automatic data migration.

## Why Bun?

Bun is a fast, modern JavaScript runtime that is designed to be a drop-in replacement for Node.js. It is built with V8, the same engine that powers Google Chrome, and it is designed to be faster and more efficient than Node.js.

```bash
npx prisma init
```

```bash
npx prisma migrate dev
```

```bash
npx prisma generate
```

```typescript
const prisma = new PrismaClient();
```
