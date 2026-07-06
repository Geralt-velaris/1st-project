# Cursor Project Guide

এই ফোল্ডারে একটি **Node.js + TypeScript** প্রজেক্ট তৈরি করা হবে।

## Project Overview

- **Folder:** Cursor documents
- **Runtime:** Node.js
- **Language:** TypeScript
- **Purpose:** _(এখানে প্রজেক্টের উদ্দেশ্য লিখুন)_

## Tech Stack

| Layer | Technology |
|-------|------------|
| Runtime | Node.js |
| Language | TypeScript |
| Package Manager | npm |
| Build | `tsc` (TypeScript Compiler) |
| Dev Runner | `tsx` বা `ts-node` |
| Linting | ESLint |
| Formatting | Prettier |

## AI Instructions

Cursor Agent এই নির্দেশগুলো অনুসরণ করবে:

1. **TypeScript** — সব নতুন কোড TypeScript-এ লিখবে; `any` এড়িয়ে সঠিক টাইপ ব্যবহার করবে
2. **Node.js** — CommonJS/ESM কনভেনশন প্রজেক্ট সেটআপ অনুযায়ী মেনে চলবে
3. **Scope** — শুধু প্রয়োজনীয় ফাইল ও কোড পরিবর্তন করবে
4. **Conventions** — বিদ্যমান কোড স্টাইল, ফোল্ডার স্ট্রাকচার ও প্যাটার্ন মেনে চলবে
5. **Dependencies** — নতুন প্যাকেজ যোগ করার আগে প্রয়োজনীয়তা যাচাই করবে

## Project Structure

```
Cursor documents/
├── src/              # TypeScript সোর্স কোড
│   └── index.ts      # Entry point
├── dist/             # Compiled JavaScript (build output)
├── package.json
├── tsconfig.json
├── .eslintrc.json
├── .prettierrc
└── cursor.md
```

## Scripts (planned)

```json
{
  "dev": "tsx watch src/index.ts",
  "build": "tsc",
  "start": "node dist/index.js",
  "lint": "eslint src --ext .ts",
  "format": "prettier --write \"src/**/*.ts\""
}
```

## Notes

_(এখানে গুরুত্বপূর্ণ নোট, API ডকুমেন্টেশন বা রেফারেন্স যোগ করুন)_
