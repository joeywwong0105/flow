# Flow (Mobile) — minimal scaffold

Flow 是一款轻盈、极简的生活记录 APP：用“Flow Pulse（今日节奏建议）”帮助用户在记录中获得松弛感与自我觉察。

## 目录结构

```text
1234/
  apps/
    mobile/
      src/
        screens/
          TodayScreen.tsx
        components/
          FlowPulse.tsx
        lib/
          ganzhi.ts
          api.ts
    api/
      src/
        ai/
          buildLifeAdvicePrompt.ts
        routes/
          todayAdvice.ts
        types/
          energy.ts
  packages/
    schema/
      prisma/
        schema.prisma
```

## 你关心的四项交付

- **Schema**：`packages/schema/prisma/schema.prisma`
- **Today 页面 React 逻辑**：`apps/mobile/src/screens/TodayScreen.tsx` + `apps/mobile/src/components/FlowPulse.tsx`
- **AI Prompt 函数 + API 逻辑**：`apps/api/src/ai/buildLifeAdvicePrompt.ts` + `apps/api/src/routes/todayAdvice.ts`
- **目录结构图**：见本 README

